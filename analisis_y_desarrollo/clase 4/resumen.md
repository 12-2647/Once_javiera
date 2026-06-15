# Documentación de Requerimientos

## Introducción

La documentación de requerimientos consiste en transformar los requerimientos descubiertos durante la elicitación en documentos formales, claros y estructurados siguiendo estándares reconocidos en la industria del software.

---

## 1. ¿Por Qué Documentar?

### Riesgos de No Documentar

La ausencia de documentación puede generar:

- Olvido de detalles importantes.
- Pérdida de conocimiento cuando el personal abandona el proyecto.
- Dificultades para realizar auditorías.
- Malentendidos con el cliente.
- Sobrecostos.
- Retrasos en el desarrollo.

### Las 5 Funciones de la Documentación

#### 1. Acuerdo o Contrato
Sirve como compromiso formal entre el cliente y el equipo de desarrollo.

#### 2. Guía
Proporciona instrucciones claras para diseñadores y desarrolladores.

#### 3. Verificación
Permite a los testers comprobar que el sistema cumple los requerimientos.

#### 4. Conocimiento
Conserva la memoria histórica del proyecto.

#### 5. Legal
Funciona como evidencia ante auditorías, conflictos o disputas.

### Regla de Oro

> A mayor riesgo del proyecto, mayor debe ser el nivel de documentación.

**Ejemplos de proyectos de alto riesgo:**

- Sistemas médicos.
- Sistemas bancarios.
- Sistemas aeronáuticos.
- Sistemas gubernamentales.

---

## 2. El Estándar IEEE 830 (SRS)

### Definición

El estándar IEEE 830 define la estructura de un documento de:

**SRS (Software Requirements Specification)**

Su objetivo es permitir que cualquier profesional pueda comprender los requerimientos del sistema de manera uniforme.

---

### Estructura del Documento SRS

#### Sección 1: Introducción

Contiene:

- Propósito del documento.
- Alcance del sistema.
- Funciones incluidas.
- Funciones excluidas.
- Definiciones y glosario.
- Referencias técnicas y legales.

---

#### Sección 2: Descripción General

Describe el contexto del sistema.

Incluye:

- Perspectiva del producto.
- Funciones generales.
- Características de los usuarios.
- Restricciones.
- Suposiciones y dependencias.

##### Restricciones Comunes

- Presupuesto.
- Tiempo.
- Legislación.
- Tecnología disponible.

---

#### Sección 3: Requisitos Específicos

Es la parte más importante del documento.

Contiene:

##### Requerimientos Funcionales

- RF-001
- RF-002
- RF-003
- ...

##### Requerimientos No Funcionales

- RNF-001
- RNF-002
- RNF-003
- ...

##### Interfaces Externas

- Interfaces de usuario.
- Interfaces de hardware.
- Interfaces de software.
- Interfaces de comunicación.

##### Casos de Uso

Descripción detallada de las interacciones del sistema.

---

#### Sección 4: Apéndices

Incluye información complementaria.

Por ejemplo:

- Diagramas.
- Mockups.
- Bocetos de pantallas.
- Tablas de trazabilidad.

---

## 3. Casos de Uso

### Definición

Un caso de uso es una descripción paso a paso de cómo un actor interactúa con el sistema para alcanzar un objetivo.

### Diferencia entre Requerimiento y Caso de Uso

| Requerimiento | Caso de Uso |
|--------------|-------------|
| Describe qué hace el sistema | Describe cómo ocurre la interacción |
| Una frase breve | Narración completa |
| Orientado a funcionalidades | Orientado a procesos |

---

### Componentes de un Caso de Uso

#### Actor

Entidad que interactúa con el sistema.

Puede ser:

- Persona.
- Sistema externo.
- Dispositivo.

#### Sistema

Límite o frontera donde ocurren las acciones.

#### Objetivo

Resultado que desea obtener el actor.

#### Escenario

Secuencia ordenada de pasos para alcanzar el objetivo.

---

### Relaciones UML

#### <<include>> (Incluye)

Se utiliza cuando un caso de uso siempre requiere otro caso de uso.

**Ejemplo:**

Reservar libro  
→ incluye → Iniciar sesión

Características:

- Obligatorio.
- Reutilizable.
- Siempre ocurre.

---

#### <<extend>> (Extiende)

Representa comportamiento opcional o condicional.

**Ejemplo:**

Reservar libro  
→ extiende → Pagar multa

Características:

- Opcional.
- Ocurre bajo ciertas condiciones.
- Amplía el flujo principal.

---

## 4. Plantilla Aplicada: Biblioteca Escolar

### Caso de Estudio

Sistema de Gestión de Biblioteca Escolar (SGBE).

Objetivo:

- Reemplazar registros físicos.
- Automatizar préstamos.
- Mejorar el control de libros.

---

### Identificadores Únicos (IDs)

Cada elemento del sistema debe tener un identificador único.

#### Ejemplos

##### Requerimientos Funcionales

- RF-001
- RF-002
- RF-003

##### Requerimientos No Funcionales

- RNF-001
- RNF-002

##### Casos de Uso

- CU-001
- CU-002
- CU-003

---

### Importancia de los IDs

Los identificadores permiten:

- Mantener trazabilidad.
- Relacionar requerimientos y pruebas.
- Facilitar auditorías.
- Controlar cambios.
- Seguir el ciclo de vida del proyecto.

---

## Características de un Buen Documento de Requerimientos

Un documento de requerimientos debe ser:

- Correcto.
- No ambiguo.
- Completo.
- Consistente.
- Verificable.
- Trazable.

---

# Resumen General

| Concepto | Propósito |
|-----------|------------|
| Documentación | Registrar formalmente los requerimientos |
| IEEE 830 (SRS) | Estructurar la especificación de software |
| Casos de Uso | Describir la interacción actor-sistema |
| UML Include | Funcionalidad obligatoria reutilizable |
| UML Extend | Funcionalidad opcional o condicional |
| IDs | Garantizar la trazabilidad |
| Trazabilidad | Seguir requerimientos durante todo el proyecto |

## Idea Principal

La documentación de requerimientos convierte las necesidades descubiertas durante la elicitación en especificaciones formales, verificables y trazables que sirven como base para el desarrollo, las pruebas, la gestión y el mantenimiento del software.