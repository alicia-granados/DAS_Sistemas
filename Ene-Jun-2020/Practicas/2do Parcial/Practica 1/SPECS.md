# Práctica 1

### Objetivo

* Mejorar el aprendizaje y conocimiento sobre [contenedores de Linux](https://linuxcontainers.org/) y [Docker](https://www.docker.com/).
* Involucrarse con la parte práctica de los primeros temas de Arquitectura de Software.

### Especificaciones

* Crear un fork del siguiente repositorio https://github.com/AnhellO/pokepy. Después de crear el fork, deberás clonar éste a tu máquina local (es decir, tu propio fork del repositorio).
* Deberás de modificar el código existente para que cumpla con los siguientes requisitos:
  * Agregar el soporte al código para mostrar todos los pokemon existentes en la [API](https://pokeapi.co/), no solamente los primeros 151 pokemon como está actualmente en el código.
  * Aparte del nombre y la imágen del pokemon, deberás de mostrar al menos `10` campos más de información para el pokemon en cuestión. Puedes utilizar los campos que tu quieras para cumplir con este requisito.
  * Deberás de modificar el [template actual](https://github.com/AnhellO/pokepy/blob/master/templates/index.html) para que esta nueva información se muestre en una etiqueta [`<table>`](https://www.w3schools.com/html/html_tables.asp). También deberás de actualizar el aspecto de la página a que use diferentes colores, fuentes y demás atributos. Lo anterior es a gusto propio, pero debe de ser diferente al template original.
  * Agrega soporte para que ahora sea posible obtener la información de un pokemon en base a un [parámetro en la URL](https://en.wikipedia.org/wiki/Query_string), en vez de obtener la información de un pokemon aleatoriamente en cada carga, ejemplo `http://0.0.0.0:5050/?pokemon=alakazam`.
* Una vez que tu práctica este actualizada y ya que hayas probado que todo funciona correctamente, crea una nueva imagen de docker, con la version `1.0`, y publicala a tu cuenta de [Dockerhub](https://hub.docker.com/). Asegurate de compartir la URL final de la ubicación de tu imagen, es decir `https://hub.docker.com/r/anhellojz/pokepy` como resultado para este punto.

### Recursos

* Tutoriales de Docker que ya se han compartido email y durantes las mismas clases.

### Deadline

* `Domingo 5 de Abril a las 11:00pm`.