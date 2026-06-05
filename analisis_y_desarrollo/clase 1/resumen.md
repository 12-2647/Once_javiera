# Análisis y Diseño de Software

---

## Módulo 1 — ¿Por qué importan el análisis y el diseño?

- El **análisis** responde *¿QUÉ* se construirá (entender el problema).
- El **diseño** responde *¿CÓMO* se construirá (planear la solución).
- El 66% de los proyectos de software fracasan, principalmente por requerimientos mal definidos.
- **Regla del 1-10-100:** corregir un error cuesta $1 en análisis, $10 en diseño, $100 en programación y $1000+ en producción.

---

## Módulo 2 — Ciclo de vida del software

| # | Fase | Resultado |
|---|------|-----------|
| 1 | Análisis de Requerimientos | Especificación de requerimientos |
| 2 | Diseño | Planos, diagramas, prototipos |
| 3 | Implementación | Software funcionando |
| 4 | Pruebas | Reporte de errores corregidos |
| 5 | Despliegue | Sistema en uso real |
| 6 | Mantenimiento | Versiones mejoradas |

En la práctica el ciclo es **iterativo**, no lineal.

---

## Módulo 3 — Metodologías Estructuradas

Se planifica todo desde el inicio. Fases secuenciales.

- **Cascada (Waterfall):** cada fase termina antes de iniciar la siguiente. Simple, pero rígido.
- **Modelo en V:** igual que cascada, pero cada fase de desarrollo tiene una prueba asociada.
- **Modelo Espiral:** combina cascada con análisis de riesgos; cada vuelta reduce la incertidumbre.

> Ideales para sistemas críticos (aviación, salud, banca) con requerimientos fijos y regulados.

---

## Módulo 4 — Metodologías Ágiles

Basadas en el **Manifiesto Ágil (2001)**: iteraciones cortas, adaptación al cambio.

- **Scrum:** trabajo en *sprints* (1-4 semanas), roles claros (Product Owner, Scrum Master, equipo), demos y retrospectivas.
- **Kanban:** tablero visual de columnas (Por hacer → Haciendo → Probando → Hecho). Limita el trabajo en curso.
- **XP (Extreme Programming):** programación en pares, TDD, refactorización continua.

> Ideales para apps, startups y productos que evolucionan rápido con equipos pequeños.

---

## Módulo 5 — Taller: ¿Estructurada o Ágil?

**Patrón clave para elegir:**

- Más consecuencias críticas + requerimientos fijos → **Estructurada**
- Más incertidumbre + necesidad de cambio rápido → **Ágil**
- También es posible combinar ambas (enfoques **híbridos**).

---

## Módulo 6 — ¿Qué es un requerimiento?

Un requerimiento es la descripción de lo que el sistema debe hacer o cumplir.

**Tipos:**

- **Funcionales:** *¿qué hace?* (ej. "el sistema debe calcular el promedio de notas")
- **No funcionales:** *¿cómo es?* (ej. "debe responder en menos de 2 segundos")

**Buenos requerimientos son SMART:**

> Específicos · Medibles · Alcanzables · Relevantes · Con plazo

**Técnicas para descubrirlos:** entrevistas, encuestas, observación, talleres, análisis de documentos, prototipos.

---

## Módulo 7 — Reto Final

Diseñar los requerimientos de un sistema escolar que incluya:

1. Descripción del problema
2. 5 requerimientos funcionales
3. 3 requerimientos no funcionales medibles
4. 3 personas a entrevistar
5. Decisión de metodología (estructurada o ágil) con justificación

---

> **Idea central del curso:** *Antes de hacer, hay que pensar.* El análisis y diseño son lo que separa a un buen programador de un gran ingeniero.