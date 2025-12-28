# 📘 Math for Computer Science — Chapter 1 Notes

Este repositorio documenta mi avance en el estudio del curso **MIT 6.042J – Mathematics for Computer Science**, enfocado en construir una base sólida de razonamiento lógico aplicable a **ingeniería, redes, seguridad y sistemas**.

El objetivo no es memorizar definiciones, sino **entender cómo se razona correctamente**, detectar errores lógicos y evitar fallos críticos en diseño e implementación.

---

## 1️⃣ Propositions (Proposiciones)

Una **proposición** es una afirmación que puede ser evaluada como **verdadera (V)** o **falsa (F)**, pero no ambas al mismo tiempo.

Ejemplos:
- “El paquete fue entregado correctamente.” → Proposición
- “¿El paquete llegó?” → No es proposición (es una pregunta)

### Ideas clave:
- Las proposiciones permiten modelar reglas, estados y condiciones.
- En ingeniería, muchas decisiones dependen de proposiciones mal o bien formuladas.
- Una afirmación universal debe cumplirse **en todos los casos**, sin excepción.

### Contraejemplo:
Si una proposición afirma algo para *todos* los casos, **un solo contraejemplo** es suficiente para invalidarla por completo.

Esto es fundamental en:
- verificación de sistemas
- pruebas de correctitud
- validación de protocolos
