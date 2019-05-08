# weman_3.2_services
## Práctica de servicios en el backend

En este repositorio se incluye un terminador de front end y un ejemplo para correr en el lado de servidor. Deberá de servir como base para que las estudiantes creen respuestas personalizadas según el tipo el de petición. Los ejercicios a resolver deben cumplir al menos la siguiente lista, pero se espera que se haga alguno más.

* GET
  * Debe de recibir una palabra a través de GET y debe de responderla con las letras invertidas.
  * Recibirá una palabra y responderá con el correspondiente saludo, dependiendo de la hora del servidor, y la palabra que haya recibido a través de la petición; entre las 06:00 y las 12:00 "Buenos días", entre las 12:01 y las 18:00 "Buenas tardes" y después de ello, "Buenas noches"

* POST
  * Debe recibir el contenido de un ```<TEXTAREA></TEXTAREA>``` y guardarlo en un archivo en el servidor.
  * Debe de recibir un nombre de usuario y una contraseña, comprobar que sean iguales a los establecidos en el servidor y enviar la respuesta adecuada al cliente.
  
## Práctica avanzada.

Quizás noten que cuando se usa el form, la página entera cambia y sustituye el contenido por el resultado. Existe un método que permite evitar esta molestia, ese método es conocido como "llamdas asíncronas" o AJAX. En el archivo index.js viene un ejemplo de función asíncrona. Pueden usarla para hacer los mismos ejercicios.
  
## Referencias recomendadas:

https://www.w3schools.com/nodejs/default.asp

https://nodejs.org/api/synopsis.html

https://www.w3.org/Protocols/rfc2616/rfc2616-sec9.html
