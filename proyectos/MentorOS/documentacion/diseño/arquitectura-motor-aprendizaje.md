# Decisión de Arquitectura: Motor de rutas de aprendizaje

## 1. Contexto

MentorOS busca convertirse en una plataforma de aprendizaje personalizada donde los usuarios puedan adquirir conocimientos mediante rutas estructuradas y acompañamiento inteligente.

Para la primera versión del sistema se requiere definir cómo se generarán y administrarán las rutas de aprendizaje.

---

## 2. Problema

Existen dos posibilidades principales:

1. Permitir que la inteligencia artificial genere rutas completamente dinámicas.
2. Utilizar rutas de aprendizaje previamente diseñadas y permitir que la inteligencia artificial adapte la experiencia.

Se requiere elegir una estrategia que permita equilibrio entre calidad educativa, control del contenido y viabilidad técnica.

---

## 3. Decisión tomada

MentorOS utilizará rutas de aprendizaje predefinidas almacenadas en una base de conocimiento.

La inteligencia artificial funcionará como un mentor adaptativo encargado de:

- Guiar al usuario durante la ruta.
- Resolver dudas.
- Explicar conceptos.
- Proporcionar retroalimentación.
- Adaptar la dificultad según el progreso.

---

## 4. Justificación

Esta decisión permite mantener una estructura educativa organizada y evitar que la inteligencia artificial genere rutas incorrectas o incompletas.

Las rutas serán diseñadas considerando una progresión lógica del aprendizaje:

Conceptos básicos → práctica → aplicación → proyectos.

---

## 5. Funcionamiento

El flujo general será:

Usuario define objetivo.

↓

MentorOS identifica la ruta relacionada.

↓

El usuario inicia la primera misión.

↓

La IA acompaña el proceso.

↓

El sistema analiza progreso.

↓

La IA recomienda continuar, reforzar o repasar conceptos.

---

## 6. Ventajas

- Mayor control sobre la calidad educativa.
- Menor dependencia de generación automática.
- Menor costo computacional.
- Permite validar las rutas antes de publicarlas.
- Facilita la mejora progresiva del contenido.

---

## 7. Desventajas

- Requiere crear rutas inicialmente.
- La actualización del contenido debe ser gestionada.
- Puede necesitar más trabajo de diseño educativo.

---

## 8. Impacto en el sistema

Esta decisión afecta los siguientes módulos:

- Motor de rutas de aprendizaje.
- Base de conocimiento.
- Asistente IA.
- Sistema de progreso del usuario.

---

## 9. Futuras mejoras

En versiones posteriores se podría implementar generación dinámica de rutas utilizando inteligencia artificial, combinando rutas existentes con recomendaciones personalizadas.