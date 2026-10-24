# Kanban (Evaluación Final)

> **Instrucciones:** Al finalizar el Día 3, cuando todas las tarjetas de código estén en la columna "Hecho", reúnanse como equipo, discutan las siguientes preguntas y escriban sus respuestas aquí. Al terminar, hagan un último `commit` y `push` con este archivo actualizado.

**1. Visibilidad del Flujo**

¿Cómo les ayudó tener el tablero visual en GitHub Projects para saber en qué estaba trabajando cada miembro del equipo sin tener que preguntarse a cada rato?

**Respuesta:** Tener el tablero en GitHub Projects nos ayudó a ver de un vistazo el estado de cada tarea. Con las columnas Backlog, Desarrollo, Revisión y Hecho, y una tarjeta por cada tarea de `TAREAS.md`, era fácil saber qué estaba pendiente, qué estaba en proceso y qué ya estaba terminado, sin tener que preguntarnos entre nosotros. Quien se encargó de crear y organizar el tablero lo dejó listo desde antes de empezar a programar, y eso nos dio una guía clara de qué hacer y en qué orden. En general, la visibilidad del flujo nos permitió llevar el control del avance, evitar que se nos olvidara alguna tarea y coordinarnos mejor.

**2. Límites de Trabajo en Curso (WIP)**

¿Cuál fue el límite WIP que establecieron para la columna "Desarrollo"? ¿Sintieron que esta restricción redujo el estrés o el *multitasking* en comparación con trabajar sin reglas?

**Respuesta:** Definimos un límite por columna: **Backlog: 10, Desarrollo: 3, Revisión: 3 y Hecho: 10**. El límite de 3 en Desarrollo nos permitía tener varias tarjetas en curso sin saturar el tablero. Como las tareas eran pequeñas y se avanzaron rápido, el límite no llegó a sentirse como una restricción fuerte, pero sí nos ayudó a terminar lo que ya estaba empezado antes de tomar trabajo nuevo, lo que redujo el multitasking. Creemos que en un proyecto más largo o con tareas más grandes, el límite WIP sería todavía más útil para evitar que se acumule trabajo a medias.

**3. Gestión de Cuellos de Botella**

Durante la práctica, ¿tuvieron alguna tarea que se quedó bloqueada o estancada mucho tiempo? Si fue así, ¿cómo se organizó el equipo para ayudar a destrabarla y mantener el flujo continuo?

**Respuesta:** No tuvimos ninguna tarea bloqueada ni estancada, por lo que nunca fue necesario marcar una tarjeta como [BLOQUEADO] ni detenernos a ayudar a destrabar algo. Las tareas eran pequeñas y estaban bien descritas en `TAREAS.md`, así que se completaron sin problemas. También ayudó seguir un orden lógico: primero las funciones de base de datos (`obtenerMenu` y `guardarComanda`), de las que depende la lógica del frontend, y después la lógica y el diseño. En un proyecto más grande, es probable que sí aparezcan dependencias que generen cuellos de botella, y en ese caso usaríamos la etiqueta [BLOQUEADO] y detendríamos el trabajo para resolverlo en equipo.

**4. Mejora Continua**

Si este proyecto del restaurante continuara durante todo el semestre, ¿qué política explícita nueva agregarían a su tablero o qué cambiarían de su límite WIP para ser más eficientes?

**Respuesta:** Si el proyecto continuara todo el semestre, agregaríamos tres políticas explícitas. **Primero**, una *Definición de Hecho*: una tarjeta solo pasa a "Hecho" si el QA la probó en el navegador sin errores en consola y el código ya está subido con un commit claro. **Segundo**, repartir las tarjetas entre todos los integrantes desde el inicio (sistema *pull*) para que el tablero refleje de verdad quién hace qué y el trabajo se distribuya mejor. **Tercero**, agregar una columna "Bloqueado" y reducir el límite WIP de Desarrollo a 2 si vemos que Revisión se llena, para que el QA no se convierta en el cuello de botella. También revisaríamos los límites cada semana y los ajustaríamos según cómo fluya el trabajo.


