# Equipo de agentes de IA — DevTrack

Esta carpeta contiene perfiles de trabajo reutilizables para asistir el desarrollo de DevTrack. No son procesos autónomos ejecutándose en segundo plano: son instrucciones que se pueden cargar en un asistente de IA cuando se necesite un rol concreto.

## Cómo utilizarlos

1. Comparte con el asistente el archivo `PROJECT_CONTEXT.md`.
2. Comparte el perfil del agente que necesitas.
3. Pídele que revise el estado actual del repositorio antes de proponer cambios.
4. Para cambios de código, solicita primero un plan breve y después implementa por partes.
5. Al terminar, actualiza la documentación compartida si cambió el estado del proyecto.

## Agentes disponibles

- `AGENT_PROJECT_MANAGER.md`: planificación, prioridades y seguimiento.
- `AGENT_SOFTWARE_ARCHITECT.md`: arquitectura global y decisiones técnicas.
- `AGENT_FRONTEND.md`: HTML, CSS y JavaScript del cliente.
- `AGENT_BACKEND.md`: arquitectura del servidor y datos.
- `AGENT_UI_UX.md`: diseño visual y experiencia de usuario.
- `AGENT_QA.md`: pruebas, revisión y prevención de errores.

## Fuente compartida de contexto

- `PROJECT_CONTEXT.md`: descripción y estado conocido del proyecto.
- `DECISIONS.md`: decisiones técnicas confirmadas.
- `TASKS.md`: trabajo pendiente y progreso.

**Regla:** si un dato no está confirmado en el repositorio, el agente debe preguntarlo o marcarlo como propuesta; nunca presentarlo como una decisión tomada.
