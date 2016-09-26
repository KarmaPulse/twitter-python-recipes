# 21 Recetas con Python y Twitter

## Introducción

A continuación presento un reporte donde recopilo la informacion mas interesante de cada receta asi como las herramientas mas relevantes que utiliza cada una de ellas.

## Usando OAuth para accesar las APIs de Python

### Resumen

En esta receta se muestra como autenticarse para poder consumir las APIs de Twitter. Para lograr esto se necesita registrar un app en esta direccion http://dev.twitter.com/apps. Despues de haberla registrado nos dara una consumer key y una consumer secret que utilizaremos para solicitar acceso a twitter a la informacion de un usuario. Posteriormente obtendremos una URL con la cual el usuario se podra autenticar y asi obtendremos el access token y el access token secret con los cuales ya podremos hacer uso de la API de Twitter.

### Herramientas

- pip install twitter ** Libreria para consumir las APIs de Twitter.**

## Buscando Trendig topics

### Resumen

Aqui se muestra un ejemplo de como realizar un seguimiento de los trending topics por medio del API de Twitter. Un dato importante es que el seguimiento se hace por region y la region se identifica por medio de este standard de Yahoo http://woeid.rosselliot.co.nz/lookup/mexico.

## Buscando Tweets

### Resumen

Aqui se muestra un ejemplo de como solicitar tweets por medio del API de search. Para solicitar los tweets se utiliza un Query similar a los usados GNIP.

## Grafos

### Resumen

En estas recetas se muestra como generar un grafo a partir de los tweets. Los mas interesante de este capitulo realmente son las herramientas utilizadas para generar el grafo y para visualizar la informacion.

### Herramientas

- networkx
- Graphviz
- Protovis

## Realizar peticiones robustas al API de twitter

## Resumen

En esta receta se ejemplifica como realizar peticiones al API. El objetivo de este capitulo es mostrar como capturar los posibles errores que puede regresar el API como rate limit. Realmente lo recomendado por la receta es hacer un sleep y atrapar la excepcion.

## Resumiendo paginas ligadas a un Tweet

### Resumen

En esta receta se muestra como conseguir un resumen del contenido de una pagina web programaticamente.

### Herramienta

- nltk
- BeautifulSoup

## Obtener Influencer Potencial

### Resumen

En esta receta se muestra como calcular la popularidad de un twitero por medio de la tecnica breadth-fisrt traversal. En resumen el proceso genera una cola Q1 que tiene una o mas semillas se visitan sistematicamente cada uno de los nodos relacionados a la semilla  y se ubican en una cola Q2, cuando Q1 se vacia se rehace el proceso a la inversa. Una vez que cierta profundidad es alcanzada se termina el proceso. Con este proceso podemos generar un grafo a cierto nivel de profundidad de los usuario relacionados en la busqueda.

## Visualizar informacion geoespacial con un Cartograma Dorling

### Resumen

Aqui se muestra como encontrar relaciones entre las ubicaciones de los usuarios por medio de un cartograma de dorling.

### Herramientas

- Dorling Cartogram
- Protovis
