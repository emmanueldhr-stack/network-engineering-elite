## 2️⃣ Quantifiers (Cuantificadores)

Los cuantificadores permiten expresar proposiciones sobre conjuntos completos de elementos.

### Cuantificadores principales:
- **∀ (para todo)**
- **∃ (existe al menos uno)**

### Diferencia crítica de orden:

- `∀x ∃y`  
  Para cada elemento `x`, existe un `y` que depende de `x`.

- `∃y ∀x`  
  Existe un único `y` que debe funcionar para todos los `x`.

Cambiar el orden **cambia completamente el significado**.

### Ejemplo práctico (seguridad):
- `∀ usuario ∃ clave` → Cada usuario tiene su propia clave.
- `∃ clave ∀ usuario` → Una sola clave para todos (riesgo crítico).

### Conclusión:
Una mala interpretación de cuantificadores puede generar:
- fallos de autenticación
- errores de control de acceso
- vulnerabilidades graves

