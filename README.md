# Proyecto Inicial

## Idea a Implementar

El proyecto consta de varias etapas en las cuales se van a agregando funcionalidades deseables.
La primera etapa consiste en la implementación de varias aplicaciones que permitan por un lado administrar una tienda y por otro lado buscar los productos disponibles en dicha tienda.
El usuario encargado de la aplicación que maneja los datos de la tienda será el administrador y el usuario que realiza las consultas será el cliente.

Se espera:
-	Contar con una base de datos de los productos disponibles en la tienda.
-	Poder administrar dicha base de datos, agregando, modificando o dando de baja productos.
-	Poder cargar imágenes de los productos para facilitar la búsqueda y el reconocimiento del producto por parte del cliente.
-	Hacer una búsqueda de los productos a través de varios filtros disponibles en la aplicación o a través de búsqueda por nombre.
-	Poder consultar dichos productos obteniendo una descripción de estos, así como otros datos de interés como stock disponible, precio, etc.

Sería deseable en esta etapa que los productos se puedan filtrar por categorías. Es decir, que, por cada categoría existente en los productos, esto se pueda utilizar como filtro. Por ejemplo, se pueden crear productos con las categorías ‘bebidas’, ‘panificados’, ‘embutidos’, etc. y esto se va a visualizar como una lista de categorías para elegir.

En la segunda etapa se pretende que la aplicación provea medios para hacer una selección de productos a comprar por parte del cliente y que esto se genere como un pedido en la vista del administrador, el cual puede ver el pedido hecho por dicho cliente y gestionarlo. El cliente puede consultar el estado de su pedido para saber si ya está listo.

El pedido puede tener los siguientes estados:
-	En espera: el cliente hizo el pedido y la tienda todavía no lo está preparando (en este caso el cliente todavía puede hacer modificaciones.
-	En proceso: la tienda está preparando el pedido.
-	Listo: el pedido ya esta preparado y listo para retirar o enviar al cliente.
-	Enviado: el pedido fue enviado al cliente.
-	Finalizado: el pedido ya fue entregado al cliente.

Se espera:
-	Poder crear una orden de compra seleccionando productos de la tienda.
-	Hacer un pedido por los productos seleccionados.
-	Consultar el estado de dicho pedido.
-	El administrador debe poder ver los pedidos y modificar el estado de los mismos.


## Tema y conexión

La idea del proyecto aplica al tema ‘Comida’, ya que se trata de una tienda de venta de productos alimenticios. 

## Diagrama ER

![Proyecto-Inicial-2 0](https://user-images.githubusercontent.com/14023314/115551716-d8fef300-a281-11eb-8db9-b41dc8e0b99c.png)


## Actualizaciones a los datos

El Proyecto Framework PHP – Laravel permitirá:

A usuarios con el rol de administrador:

Primera etapa:

-	Agregar, actualizar o dar de baja productos.
-	Administrar usuarios.

Segunda etapa:
-	Actualizar el estado de los pedidos.

A usuarios con el rol de cliente:

Segunda etapa:
-	Agregar, actualizar o dar de baja un pedido.

Repositorio de este proyecto: https://github.com/MartinQuijano/laravel-esenciales

## Información del Servicio Web

Qué información será accesible desde el servicio web y de qué manera.

El Servicio Web permitirá:

Primera etapa:
-	Acceder a los datos de los productos.

Segunda etapa:
-	Acceder a la información de los pedidos.

Repositorio de este proyecto: https://github.com/MartinQuijano/servicio-web-esenciales

## Visualización y Acceso a la Información

La aplicación obtenida con el proyecto Javascript – React permitirá ver los productos disponibles en la tienda y proveerá menús desplegables los cuales permitirán filtrar los productos de acuerdo a las categorías. Además, contará con un buscador de productos por tipo o marca.

Se mostrará información sobre los productos más vendidos. También se podrá visualizar para cada categoría o tipo, los precios en un orden particular.

Repositorio de este proyecto: https://github.com/MartinQuijano/react-esenciales
