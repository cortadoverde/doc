Análisis SEO
============

Primero que nada debo aclarar que la propuesta no se basa en linksharing, ni publicación de 
anuncios pagos totalmente inútiles para mejorar el posicionamiento, el objetivo de la propuesta
es hacer una análisis profundo sobre la arquitectura del contenido, y como se puede mejorar, con
técnicas honestas que busquen destacar el contenido y ponerlo a disposición del usuario, así como
también de los motores de búsqueda.

No existe una solución mágica para esta tarea, requiere de un estudio constante sobre la información que 
se maneja en el sitio web. Ni tampoco existe el posicionamiento inmediato.

Introducción
------------
Los puntos claves para una buena calificación en el posicionamiento son:

1. Estructura de datos semánticas. ( implementación de microformatos o HTML5 )
2. Velocidad y optimización de recursos. ( Tenga en cuenta que los analizadores de contenido no son usuarios y no están dispuestos a esperar mas de 2 segundos ) 
3. Honestidad en las disposición de contenido, no recurrir a técnicas para colocar palabras claves solo para sumar un punto en el algoritmo, ya que no solo se analizan las palabras sino el contexto en el que se las utiliza.

Plan de accion
--------------
1. Utilizar JSON-LD para la descripción de los productos, utilizando el para ello schema.org

		{
		  "@context" : "http://schema.org",
		  "@type" : "Product",
		  "name" : "Mazas Circus Stage Fluorescentes de...",
		  "image" : "http://malabarestrabalam.es/54-home_default/mazas-circus-stage-fluorescentes-de-beard-juggling.jpg",
		  "description" : "Uno de nuestros productos más",
		  "offers" : {
		    "@type" : "Offer",
		    "price" : "15,70 €"
		  }
		}

2. Estructurar al igual que los productos los datos del sitio.

3. Unificar los estilos y scripts, minificar y utilizar compresion gzip para mejorar la velocidad de carga.

4. Optimizar las imágenes, esta utilizando imagenes de 300px de ancho y en el diseño el máximo que se muestra es de 200px, 100px menos por cada imagen sumado a una mejor compresion es una buena forma de ahorrar tiempo de carga, adicionalmente propongo la carga asincronica de imagenes, para que el DOM se genere instantaneamente sin tener que esperar a que descargue todas las imagenes, tenga en cuenta que tiene un ecommerce y eso significa muchas imagenes. La carga asincronica bien lograda no es perceptible por una usuario, ya que el dom tarda microsegundos en cargarse, una vez que se logra inmediatamente se hace un barrido
de arriba hacia abajo ya con el contenido en su lugar.

Otros factores a tener en cuenta
--------------------------------
Se debera hacer modificaciones en el theme que usa prestashop para poder lograr estos objetivos

Tiempo estimado
---------------
7 días hábiles a partir de la confirmación. 

Operativa de trabajo
--------------------
Se generará un reporte diario sobre los avances del plan de acción 

Costos
------
70 euros por día.

** Total: 490 euros **
