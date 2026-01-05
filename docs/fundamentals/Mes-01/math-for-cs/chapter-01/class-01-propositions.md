# Propositions

**Fecha:** [2025-12-26] | **Estado:** ✅ Completado

## 1. Concepto Central
Una proposición es una afirmación que puede ser verdadera o falsa (pero no ambas). Es la unidad básica de la lógica, sobre la cual se construyen argumentos más complejos.

## 2. Forma Lógica / Matemática
- Notación: letras como \( P, Q, R \)
- Valores de verdad: \( T \) (verdadero) o \( F \) (falso)
- Conectivos lógicos básicos: \( \neg \) (no), \( \land \) (y), \( \lor \) (o), \( \rightarrow \) (implica), \( \leftrightarrow \) (si y sólo si)

## 3. Aplicación a Ingeniería de Redes
- **Análisis de logs:** Cada entrada de log (ej. "Interface Gig0/1 is up") puede tratarse como una proposición cuya veracidad se monitorea.
- **Reglas de configuración:** Una directiva de configuración (ej. "el puerto 80 está abierto") es una proposición que el dispositivo implementa.
- **Verificación de estado:** Los sistemas de monitoreo prueban proposiciones como "el servicio HTTP responde en menos de 200ms".

## 4. Errores Comunes
- Confundir una proposición con una pregunta, orden o exclamación.
- Asumir que afirmaciones vagas o subjetivas son proposiciones.
- Olvidar que una proposición debe tener un valor de verdad bien definido en un contexto dado.

## 5. Conclusión Técnica
En ingeniería de redes, el pensamiento proposicional permite desglosar estados del sistema y configuraciones en componentes binarios verificables. Esto es la base para la automatización de comprobaciones, el troubleshooting sistemático y la definición clara de políticas. Dominar este nivel de abstracción es esencial para interactuar con sistemas formales de verificación y herramientas de automatización.
