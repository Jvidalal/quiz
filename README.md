# Quiz
 Proyecto de servidor web de preguntas y respuestas desarrollado para la asignatura Computación en Red de 3º del Grado en Ingeniería de Servicios y Sistemas de Telecomunicación.
## Autor
	Juan Vidal Alegría

## Descripción
 El proyecto consiste en un servidor de preguntas y respuestas realizado con express y node js. Este servidor te permite crearte una cuenta para poder publicar tus propias preguntas, añadir fotos, guardar tus preguntas favoritas, subir comentarios y publicarlos en tus preguntas. Además, los usuarios no registrados podrán también responder a las preguntas y escribir comentarios (aunque posteriormente el dueño de dicha pregunta o un usuario administrador debería publicarlo para que quede visible).

## Desarrollo
 Para el desarrollo del servidor se ha utilizado nodejs y concretamente se ha empleado express-generator para generar el proyecto como un proyecto express y después se le han ido añadiendo las diferentes funcionalidades usando bibliotecas como:
 	- Sequelize para definir y manejar las bases de datos.
 	- Crypto para el encriptado de las contraseñas.
 	- Express-session para el control de sesión.
 	- Otras.

## Despliegue y Ejecució
 Esta aplicación se puede ejecutar directamente en local con nodejs descargando el proyecto. Además se ha realizado un despliegue en Heroku al que podréis acceder a través del siguiente link: https://quiz-jvidal.herokuapp.com/