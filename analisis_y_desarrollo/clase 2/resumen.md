# Requerimientos de Software

## 1. Módulo 1: Profundización del Concepto

### Definición Formal (IEEE 830)
Un requerimiento es una propiedad documentada y una declaración verificable de una funcionalidad, restricción o calidad que un sistema debe poseer para resolver un problema.

### Niveles de Abstracción
Los requerimientos se traducen en una "escalera" desde lo más general hasta lo más específico:

1. **Necesidad del usuario** (Informal/Emocional).
2. **Requerimiento del sistema** (Intermedio).
3. **Especificación técnica** (Formal/API/Código).

### Fuentes de Requerimientos (Stakeholders)
Los requerimientos pueden provenir de:

- Usuarios finales.
- Clientes o patrocinadores.
- Leyes y normas.
- Sistemas externos.

### Cualidades de un Buen Requerimiento
Un requerimiento debe ser:

- Necesario.
- No ambiguo.
- Verificable.
- Consistente.
- Completo.
- Atómico (una sola idea).
- Trazable.

---

## 2. Módulo 2: Requerimientos Funcionales (RF)

### Definición
Describen **qué hace el sistema**, incluyendo acciones, tareas o cálculos concretos ante entradas específicas.

### Cómo Identificarlos
Se reconocen mediante:

- Verbos de acción.
- Entradas y salidas de datos.
- Decisiones lógicas.
- Roles de usuario.

### Plantilla Profesional

> El sistema deberá [acción/verbo] [objeto] [condiciones/restricciones].

### Categorías Comunes

- Autenticación.
- Cálculo.
- Persistencia (CRUD).
- Comunicación (notificaciones).
- Reportes.
- Validación.

---

## 3. Módulo 3: Requerimientos No Funcionales (RNF)

### Definición
Describen **cómo lo hace el sistema**, incluyendo comportamientos y restricciones de calidad.

> Un sistema puede cumplir todas sus funciones y aun así fracasar si es lento, inseguro o difícil de usar.

### Categorías

- Rendimiento (velocidad).
- Seguridad.
- Usabilidad.
- Confiabilidad (disponibilidad).
- Escalabilidad.
- Mantenibilidad.
- Portabilidad y Compatibilidad.
- Legales y Regulatorios.

### Regla de Oro
Todo RNF debe ser:

- Medible.
- Verificable.
- Expresado mediante métricas y umbrales concretos.

### Conflictos (Trade-offs)

Algunos RNF pueden entrar en conflicto:

| RNF 1 | RNF 2 | Ejemplo |
|--------|--------|----------|
| Seguridad | Usabilidad | Más autenticación puede dificultar el acceso. |
| Escalabilidad | Costos | Mayor capacidad implica más inversión. |

---

## 4. Módulo 4: Atributos de Calidad (ISO/IEC 25010)

### Diferencia entre Atributo de Calidad y RNF

- **Atributo de calidad:** Categoría general (ejemplo: Seguridad).
- **RNF:** Aplicación específica, concreta y medible de ese atributo.

### Principales Atributos de Calidad según ISO/IEC 25010

1. Adecuación funcional.
2. Eficiencia de desempeño.
3. Compatibilidad.
4. Usabilidad.
5. Confiabilidad.
6. Seguridad.
7. Mantenibilidad.
8. Portabilidad.

---

## 5. Módulo 5: Taller de Análisis de Necesidades

### Objetivo
Aplicar el flujo de trabajo de un analista profesional para transformar necesidades en requerimientos.

### Actividades

1. Identificar a los stakeholders correctos.
2. Seleccionar técnicas de elicitación según el contexto.
3. Convertir necesidades informales en:
   - Requerimientos Funcionales (RF).
   - Requerimientos No Funcionales (RNF).
4. Priorizar los atributos de calidad según las necesidades del negocio.

---

## 6. Módulo 6: Historias de Usuario

### Definición
Descripción breve y simple de un requerimiento desde la perspectiva del usuario.

Se utilizan principalmente en metodologías ágiles como:

- Scrum.
- Extreme Programming (XP).

### Fórmula Mágica

> Como **[tipo de usuario]**, quiero **[acción o funcionalidad]**, para **[beneficio u objetivo]**.

### Criterios de Calidad (INVEST)

Una buena historia de usuario debe ser:

- **I** → Independiente.
- **N** → Negociable.
- **V** → Valiosa.
- **E** → Estimable.
- **S** → Small (pequeña).
- **T** → Testable (comprobable).

### Criterios de Aceptación

Toda historia de usuario debe incluir criterios de aceptación para definir claramente cuándo se considera terminada.

---

# Resumen General

| Concepto | Pregunta que responde |
|-----------|---------------------|
| Necesidad | ¿Qué problema existe? |
| Requerimiento Funcional (RF) | ¿Qué debe hacer el sistema? |
| Requerimiento No Funcional (RNF) | ¿Cómo debe comportarse el sistema? |
| Atributo de Calidad | ¿Qué característica de calidad se busca? |
| Historia de Usuario | ¿Qué necesita el usuario y para qué? |