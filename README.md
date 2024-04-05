# recipApi_frontEnd

## Introduction
Os presento recipApi, mi proyecto final de **FrontEnd** en el que demostraré todo lo que he aprendido lo que llevamos de curso. Se trata de una aplicación web **SPA** de recetas solicitadas a una API. 

## Table of Contents
1. Mobile First
2. Tecnologies
3. Features
4. Design
5. Colaboration

## 1. Mobile First

Hay que destacar la importancia que tiene hoy en día **"mobile-first"**, con ello, se provee al usuario de una buena experiencia para todos los tamaños de pantalla, empezando por una experiencia de usuario que funcione bien para dispositivos pequeños, para posteriormente, basada en dicha experiencia, continuar desarrollando para enriquecer la experiencia de usuario conforme el tamaño de pantalla es mayor. En este caso os muestro lo bien que se adapta mi proyecto a un dispositivo móvil, a un ipad y a un ordenador.

### MOBILE

![Captura de pantalla 2024-04-05 a las 0 07 37](https://github.com/Gemagit/recipApi/assets/143506667/8ecfe2f8-ae6c-46df-af3b-652e9ebf7c95)

### IPAD

![Captura de pantalla 2024-04-05 a las 0 04 16](https://github.com/Gemagit/recipApi/assets/143506667/28d07a76-d353-4bb6-bea5-a8e72fe335cc)

### DESKTOP

![Captura de pantalla 2024-04-05 a las 0 02 27](https://github.com/Gemagit/recipApi/assets/143506667/0427f2a0-d497-42e3-8126-22e47fa21d7f)

## 2. Tecnologies

Las tecnologías usadas en este quiz son las siguientes:
1. HTML
2. CSS
3. JAVASCRIPT


## 3. Features

En primer lugar hice una petición a una **API** que se llama [Mealdb](https://www.themealdb.com/), elegida por mí . Para ello había que realizar un **fetch** desde **Javascript** para hacer la solicitud y seguidamente diseñé distintos algoritmos para que el usuario pudiera navegar y buscar recetas de forma intuitiva a través de mi navegador. Como habéis podido observar en las capturas que os he proporcionado en el **readMe**, mi aplicación consta de dos partes bien diferenciadas. Por un lado; el navegador que tiene varias opciones de redireccionamiento: Home, Recipes, About y un buscador con varias opciones de búsqueda. Aquí he hecho la solicitud a la **API**, filtrando por categorías ( dessert, vegetarian, chicken, beef…).

![Captura de pantalla 2024-04-05 a las 1 00 01](https://github.com/Gemagit/recipApi/assets/143506667/b856c126-d63f-4a50-bf5b-4ea0665561f0)

Por otro lado, tengo el contenido principal que son las recetas con toda su información dentro. Una funcionalidad importante a destacar aquí es que después de cada receta seleccionada, puedes pasar a la siguiente mediante un botón **“Next recipe”**.

![boton_next](https://github.com/Gemagit/recipApi/assets/143506667/93566396-6cfc-4860-b833-14c6b55c749c)

Me gustaría seguir implementando funcionalidades a este proyecto pero el tiempo que he tenido me ha permitido llegar hasta aquí, estoy muy satisfecha con el resultado y con todo lo aprendido.



## 4. Design

Se trata de un diseño web muy sencillo. Consta de un navegador situado en la parte izquierda en el que se encuentran los links que te dirigen al contenido, que después se mostrará en la parte derecha. Los colores elegidos son tonos claros.

![Captura de pantalla 2024-04-04 a las 17 30 28](https://github.com/Gemagit/recipApi/assets/143506667/e7512cb8-a6f3-4752-b194-438b048973f3)

Se trata de colores originales y únicos ya que los he elegido exclusivamente para este proyecto de una paleta de colores de la web de Coloors. Los tonos son crudos, rosas bermellón, azules..
La fuente elegida es Didot, que destaca por su sencillez.

![diseñoLetras](https://github.com/Gemagit/recipApi/assets/143506667/60ac6d03-c69a-443d-bcce-0d757aaeefa1)

Mi aplicación web huye un poco de los artificios ya que quiero que el usuario disfrute de la experiencia de navegar en una web sencilla pero a la vez visualmente atractiva.



## 5. Colaboration

Mi nombre es Gema, y es un placer poder compartir estas recetas con vosotros. He de reconocer que me gusta más comer que cocinar. Pero aún así, cocinar es una de mis grandes pasiones, y si es en buena compañía y con un buen vino, pues mucho mejor. Desde pequeña la cocina ha estado muy presente en mi vida. Mi padre ha tenido varios restaurantes y ha sido un gran cocinero, muy minucioso y siempre creando platos y sabores nuevos. Por otro lado, toda mi familia proviene de Andalucía. Allí hay mucha tradición gastronómica y en los eventos familiares el arroz, un puchero o un buen pescado no podían faltar en el menú. Espero que disfrutéis tanto como yo de esta magnífica colección de recetas.

![Captura de pantalla 2024-03-13 a las 16 15 39](https://github.com/Gemagit/quiz2.0/assets/143506667/4b5a34e0-1914-4145-af1f-a52c3c407f59)

## Cosas a implementar más adelante:

1. Botón de siguiente receta en los filtrados.
2. Firebase
3. LocalStorage
4. Carrito de la compra para almacenar ingredientes
