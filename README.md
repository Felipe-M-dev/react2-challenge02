# Desafío - Natural Pic

● Para realizar este desafío debes haber estudiado previamente todo el material disponible correspondiente a la unidad.

● Una vez terminado el desafío, comprime la carpeta que contiene el desarrollo de los requerimientos solicitados y sube el .zip en el LMS.

● Este desafío es de carácter sumativo, es decir, lleva una calificación.

● Puntaje total: 10 puntos.

● Desarrollo desafío:

  ○ El desafío se debe desarrollar de manera Individual/Grupal.

  ○ Para la realización del desafío necesitarás apoyarte del archivo ___Apoyo Desafío - Natural Pic.___

## Habilidades a evaluar

● Mostrar y editar el estado global utilizando Context API.

## Contextualización

Natural Pic es una nueva plataforma dedicada a fotógrafos que promueve el interés por el cuidado ambiental y las fotos de paisajes naturales sin filtros. En este desafío estarás trabajando en el sistema de likes usando Context API para el manejo de estado global y React Router para la creación de las vistas __Home__ y __Favoritos__.

Para este desafío descarga el material de apoyo en donde encontrarás una aplicación base con React Router que deberás completar incluyendo lo correspondiente a Context API.

A continuación, te mostramos imágenes de la aplicación y su funcionamiento.

<p align="center">
  <img src="https://github.com/Felipe-M-dev/react2-challenge02/blob/main/public/01.png?raw=true?raw=true" alt="Imagen 01"><br>
Imagen 1. Home<br>
Fuente: Desafío Latam
</p>

<p align="center">
  <img src="https://github.com/Felipe-M-dev/react2-challenge02/blob/main/public/02.png?raw=true?raw=true" alt="Imagen 02"><br>
Imagen 2. Fotos con Likes en Home<br>
Fuente: Desafío Latam
</p>

<p align="center">
  <img src="https://github.com/Felipe-M-dev/react2-challenge02/blob/main/public/03.png?raw=true?raw=true" alt="Imagen 03"><br>
Imagen 3. Vista Favoritos<br>
Fuente: Desafío Latam
</p>

Los datos que deberás utilizar en este desafío los podrás consumir del archivo ___fotos.json___ disponible en la carpeta ___public___ del proyecto, utiliza fetch o axios para esto.

La información guardada en el JSON proviene de la plataforma Pexels a través de su [API](https://www.pexels.com/es-es/api/). Siéntete libre de cambiar la temática del desafío si lo prefieres obteniendo otras imágenes luego de registrarse en la plataforma y obtener tu API KEY.

<p align="center">
  <img src="https://github.com/Felipe-M-dev/react2-challenge02/blob/main/public/04.png?raw=true?raw=true" alt="Imagen 04"><br>
Imagen 4. API de Pexels<br>
Fuente: <a href="https://www.pexels.com/es-es/api/">Pexels</a>
</p>

## Requerimientos

1. Crear un contexto con Context API que se pueda importar desde cualquier componente de la aplicación. __(2 Puntos)__

2. Usar el contexto creado como un componente para envolver toda la aplicación. __(2 Puntos)__

3. Asignar como valor del Provider un estado creado con el hook useState. __(3 Puntos)__

4. Hacer uso del hook useContext para acceder al estado global desde los componentes que lo necesiten. __(3 Puntos)__

<p align="center">
  <strong>😊¡Mucho éxito!</strong>
</p>

## Solución

1. Descargar el proyecto.

2. Desde una terminal, posicionarse sobre la carpeta del proyecto y lanzar el siguiente comando:

```npm install```

3. Al terminal la instalación de los módulos del proyecto, levantar servidor con el siguiente comando:

```npm start```

4. Cuando el server ya se encuentre arriba, ingresar al navegador y validar sitio en la siguiente URL:

```http://localhost:3000/```

## Sitio desplegado en Netlify

__URL:__

https://natural-pic.netlify.app/
