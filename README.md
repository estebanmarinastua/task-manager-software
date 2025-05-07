📋 Task Manager - CRUD
Este proyecto es una aplicación web simple de gestión de tareas (Task Manager) desarrollada en HTML, CSS y JavaScript puro, que permite realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) con persistencia de datos utilizando localStorage del navegador.

✅ Funcionalidades principales
Agregar tarea: Escribe una tarea en el campo de entrada y haz clic en "Agregar" para añadirla a la lista.

Ver tareas: Las tareas se muestran automáticamente en la interfaz al cargar la página.

Editar tarea directamente: Haz clic sobre el nombre de una tarea y edítala directamente desde el panel. Al salir del campo de texto, la tarea se actualizará automáticamente.

Marcar como completada: Haz clic en el botón "Completado" para marcar una tarea como realizada (aparece tachada y cambia de color).

Eliminar tarea: Haz clic en "Eliminar" para borrar una tarea de la lista.

Persistencia de datos: Las tareas se guardan en el localStorage, por lo que no se pierden al recargar la página.

🏗️ Estructura del proyecto
Solo necesitas un archivo HTML (no requiere dependencias externas):

bash
Copy
Edit
/index.html
Todo el HTML, CSS y JavaScript están integrados en este archivo.

🚀 Cómo usarlo
Descarga o copia el archivo index.html.

Ábrelo en cualquier navegador web moderno (Chrome, Firefox, Edge, etc.).

Comienza a gestionar tus tareas directamente.

📂 Explicación del código
🖥️ HTML
Contiene la estructura de la app:

Título

Campo de entrada

Botón "Agregar"

Lista de tareas dinámicamente generada

🎨 CSS
Diseño simple y responsivo.

Estilo visual agradable:

Caja blanca centrada

Botones con colores y hover

Tareas completadas con fondo verde y texto tachado

⚙️ JavaScript
Implementa todas las funcionalidades CRUD:

Función	Descripción
loadTasks()	Carga las tareas desde localStorage y las muestra en la lista.
addTask()	Agrega una nueva tarea al localStorage y la muestra.
toggleTaskStatus()	Cambia el estado completado/incompleto de una tarea.
removeTask()	Elimina una tarea del localStorage y de la lista.
editTask()	Selecciona el texto del input de la tarea al hacer clic (para edición directa).
updateTask()	Actualiza el nombre de una tarea en localStorage al salir del campo de texto.

📝 Consideraciones
No requiere frameworks ni bibliotecas externas.

Funciona offline.

Solo usa localStorage para persistir datos en el navegador actual.

Compatible con navegadores modernos.

💡 Mejoras posibles
Agregar filtro de tareas completadas/pending.

Integrar una base de datos externa para persistencia multiusuario.

Añadir validaciones más avanzadas (por ejemplo, nombres duplicados).

Implementar notificaciones o confirmaciones al eliminar tareas.

🧑‍💻 Autor
Desarrollado por Esteban Marín Astúa
