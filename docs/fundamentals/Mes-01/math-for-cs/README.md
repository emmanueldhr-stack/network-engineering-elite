python3
import datetime
with open('PROGRESS.md', 'r') as f:
    content = f.read()

# Actualizar fecha
from datetime import datetime
new_date = datetime.now().strftime("%Y-%m-%d")
content = content.replace("**Última actualización:**", f"**Última actualización:** {new_date}")

# Agregar sección específica de Math for CS
math_section = """

## 🧮 MATH FOR CS - PROGRESO DETALLADO

### Chapter 1: Proofs and Logic
**Estado:** 🔄 En progreso (60%)

**Checkpoints por clase:**
- Class 1 - Propositions: ✅ Completado
- Class 2 - Quantifiers: ✅ Completado  
- Class 3 - Implications: ✅ Completado 
- Class 4 - Proof by Contradiction: ⏳ Pendiente
- Class 5 - Induction Basics: ⏳ Pendiente

**Próximo checkpoint:** Ver clase de Proof by Contradiction
**Ver detalles completos:** [checkpoint-log.md](/docs/fundamentals/mes1/math-for-cs/progress/checkpoint-log.md)
"""

# Insertar después de la sección del Mes 1
if "### ✅ Mes 1" in content:
    parts = content.split("### ✅ Mes 1")
    content = parts[0] + "### ✅ Mes 1" + parts[1].split("---")[0] + math_section + "\n---" + parts[1].split("---", 1)[1]

with open('PROGRESS.md', 'w') as f:
    f.write(content)

print("✅ PROGRESS.md actualizado con sección de Math for CS")
