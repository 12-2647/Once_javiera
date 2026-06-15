# El Caso Completo

## Introducción

Esta sesión integra todos los conocimientos adquiridos en las clases anteriores dentro de un único proyecto práctico.

La idea central es que:

> El análisis, los requerimientos, la elicitación, la documentación y el diseño no son procesos independientes, sino diferentes perspectivas de un mismo proyecto.

La clase tiene una duración total de **3 horas y 45 minutos**, distribuidas en varios módulos.

---

## Objetivo General

Aplicar de manera integrada todo el ciclo de vida inicial de un proyecto de software utilizando un caso realista y cercano al contexto estudiantil.

---

# Ruta y Estructura de la Clase

## Bienvenida (10 minutos)

### Objetivo

- Presentar la relación entre todas las fases.
- Explicar el flujo completo del proyecto.

---

## Módulo 1: El Caso Completo (60 minutos)

### Objetivo

Analizar paso a paso un proyecto real utilizando las cinco fases estudiadas.

### Importancia

Es el núcleo principal de la clase.

---

## Módulo 2: Las Decisiones Detrás del Ejemplo (30 minutos)

### Objetivo

Comprender las razones detrás de las decisiones tomadas.

### Pregunta Clave

> ¿Por qué se eligió esta solución y no otra?

---

## Módulo 3: Tu Proyecto en Equipo (45 minutos)

### Actividades

- Formación de grupos.
- Selección del tema del proyecto.
- Planeación inicial.

---

## Módulo 4: Plantillas y Checklist (45 minutos)

### Objetivo

Explicar los entregables requeridos.

### Recursos

- Plantillas.
- Formatos.
- Listas de verificación.

---

## Módulo 5: La Sustentación (25 minutos)

### Objetivo

Preparar la presentación final del proyecto.

### Temas

- Comunicación efectiva.
- Organización de la exposición.
- Presentación de resultados.

---

## Cierre (10 minutos)

### Actividades

- Conclusiones.
- Retroalimentación.
- Próximos pasos del portafolio.

---

# Proyecto de Ejemplo

## Sistema de Reserva de la Cancha del Colegio

### Problema Actual

La reserva de la cancha deportiva se realiza mediante una hoja de papel pegada en la puerta.

Esto genera:

- Pérdida de información.
- Conflictos entre estudiantes.
- Desorganización.
- Dificultad para verificar disponibilidad.

### Objetivo

Automatizar la reserva de la cancha mediante una aplicación.

---

# Fase 1: Análisis

## Decisión Metodológica

Se descarta la metodología Cascada porque:

- Los requisitos cambian constantemente.
- Se necesita flexibilidad.
- Los usuarios aportarán nuevas ideas durante el proyecto.

### Metodología Elegida

**Scrum**

---

## Planificación

### Sprint 1

- Comprender el problema.

### Sprint 2

- Construir el primer prototipo.

### Sprint 3

- Realizar pruebas con usuarios.

### Sprint 4

- Corregir errores.
- Entregar el producto.

---

# Fase 2: Requerimientos

## Requerimientos Funcionales

### RF-01

Reservar una franja horaria disponible.

### RF-02

Cancelar una reserva propia.

### RF-03

Mostrar disponibilidad en tiempo real.

### RF-04

Enviar una notificación de confirmación.

---

## Requerimientos No Funcionales

### RNF-01

Permitir un máximo de dos reservas activas por usuario.

### RNF-02

Disponibilidad permanente desde dispositivos móviles.

---

# Fase 3: Elicitación

## Objetivo

Descubrir las necesidades reales de los usuarios utilizando varias técnicas.

---

## Entrevistas

### Participante

Profesor de educación física.

### Información Obtenida

- Reglas informales.
- Horarios.
- Restricciones de uso.

---

## Encuestas

### Herramienta

Google Forms.

### Objetivo

Obtener información cuantitativa de los estudiantes.

---

## Observación Directa

### Actividad

Observar el comportamiento de los usuarios en la cancha.

### Hallazgo Importante

Se descubrió que los principales conflictos ocurrían:

- Entre estudiantes de grado 10° y 11°.
- A las 5:00 p.m.
- Debido a la pérdida frecuente de la hoja física.

Este problema no apareció en las encuestas.

---

# Fase 4: Documentación

## Caso de Uso CU-01

### Nombre

Reservar Cancha.

### Flujo Principal

1. Abrir la aplicación.
2. Consultar horarios disponibles.
3. Seleccionar horario.
4. Confirmar reserva.
5. Registrar información.

### Excepciones

- Horario ocupado.
- Usuario supera el límite de reservas.

---

## Caso de Uso CU-02

### Nombre

Cancelar Reserva.

### Flujo Principal

1. Consultar reservas activas.
2. Seleccionar reserva.
3. Confirmar cancelación.
4. Liberar horario.

### Excepción

Mostrar alerta cuando la cancelación ocurre con menos de 30 minutos de anticipación.

---

# Fase 5: Diseño

## Objetivo

Transformar los requerimientos en interfaces visuales.

---

## Pantalla Home

### Funciones

- Seleccionar día.
- Consultar horarios.
- Elegir franja disponible.

---

## Pantalla de Confirmación

### Funciones

- Mostrar mensaje de éxito.

Ejemplo:

> ¡Listo!

---

## Pantalla Mis Reservas

### Funciones

- Mostrar reservas activas.
- Permitir cancelación directa.

---

# Componentes Interactivos

## Juego de Arrastrar y Soltar

### Objetivo

Relacionar cada artefacto con la fase correspondiente.

### Ejemplos

| Artefacto | Fase |
|------------|--------|
| Entrevistas | Elicitación |
| RF y RNF | Requerimientos |
| Scrum | Análisis |
| Prototipo | Diseño |
| Casos de uso | Documentación |

---

## Mini-Quiz

### Temas Evaluados

- Orden correcto de las fases.
- Técnicas de elicitación.
- Casos de uso.
- Requerimientos.
- Entregables del proyecto.

---

# Conclusión

El caso de la reserva de la cancha demuestra cómo todas las etapas del desarrollo de software se encuentran conectadas.

Cada fase aporta información necesaria para la siguiente:

1. Análisis.
2. Requerimientos.
3. Elicitación.
4. Documentación.
5. Diseño.

El resultado final es una solución organizada, validada y centrada en las necesidades reales de los usuarios.