# Contexto compartido — DevTrack

## Identidad del proyecto

- Nombre: DevTrack.
- Descripción: aplicación web de productividad personal para gestionar tareas, hábitos y objetivos.
- Lema: “Tus metas. Tus hábitos. Tu progreso.”
- Repositorio: https://github.com/dayannamb2007-ctrl/devtrack
- Estado: etapa inicial de desarrollo.

## Objetivo

Construir una aplicación funcional, intuitiva y responsive que permita organizar actividades diarias, registrar hábitos, seguir objetivos y consultar estadísticas de progreso. El proyecto también es un espacio de aprendizaje de desarrollo de software y buenas prácticas.

## Funcionalidades previstas

1. Tareas: crear, editar, eliminar, completar y categorizar.
2. Hábitos: crear hábitos, registrar cumplimiento y consultar constancia.
3. Objetivos: definir metas, fechas límite y progreso.
4. Dashboard: resumen diario y estadísticas.

## Estructura actual conocida

```text
devtrack/
├── frontend/
│   ├── assets/
│   │   ├── images/
│   │   └── icons/
│   ├── css/
│   │   └── styles.css
│   ├── js/
│   │   └── app.js
│   └── index.html
├── backend/
│   ├── src/
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   └── services/
│   └── README.md
├── ai-agents/
├── .gitignore
└── README.md
```

## Tecnologías y estado

- Frontend inicial: HTML5, CSS3 y JavaScript.
- Persistencia inicialmente prevista: LocalStorage.
- Backend: carpeta preparada, tecnología todavía no seleccionada ni implementada.
- Git y GitHub: repositorio utilizado para control de versiones.
- No asumir que existe framework, base de datos, API, autenticación ni despliegue hasta que se confirme en el código o en DECISIONS.md.

## Forma de acompañar a la persona desarrolladora

La persona está aprendiendo desarrollo de software y agradece explicaciones claras, sencillas y progresivas. Por eso:

- Explica términos técnicos con ejemplos pequeños.
- Divide el trabajo en pasos verificables.
- Explica qué archivo se modifica y por qué.
- Evita pegar grandes bloques de código sin explicar su función.
- No cambies varias partes del proyecto sin necesidad.
- No supongas conocimientos avanzados.
- Señala riesgos y pide confirmación antes de acciones destructivas.

## Reglas para todos los agentes

1. Lee este contexto y revisa los archivos reales antes de dar instrucciones específicas.
2. El código del repositorio prevalece sobre este resumen si hay diferencias; informa la discrepancia y propone actualizar este documento.
3. Distingue claramente entre estado actual, recomendación y decisión aprobada.
4. No inventes archivos, dependencias, comandos ni resultados de pruebas.
5. Respeta el alcance solicitado y conserva el estilo existente salvo que se acuerde cambiarlo.
6. Al finalizar una tarea, resume archivos modificados, pruebas realizadas y próximos pasos.
7. Si una decisión técnica cambia, actualiza DECISIONS.md; si cambia el progreso, actualiza TASKS.md.
