# B2.180 - Programación de aplicaciones web de mapas (Programación II)

Esta asignatura de cinco semanas forma parte de la especialziación de [Programación de sistemas de información geográfica](http://estudios.uoc.edu/es/masters-posgrados-especializaciones/especializacion/informatica-multimedia-telecomunicacion/programacion-desarrollo-sistemas-informacion-geografica/), de la [UOC]. 

*Créditos totales de la especialización*: 12 ECTS

*Inicio especialización*: 18 marzo 2015

Este repositorio complementa las actividades docentes de la asignatura. Aquí puedes encontrar [ejemplos y ejercicios](http://cgranell.github.io/course-webmapping/) sencillos de programación de aplicaciones web de mapas con JavaScript .  

*Créditos totales de la asignatura*: 5 ECTS (5 semanas)

*Inicio asignatura*: 30 Abril 2015 

*Fin asignatura*: 3 Junio 2015 

## Objetivos
El objetivo principal es que los estudiantes conozcan buenas prácticas para la creación de aplicaciones web de mapas. No se trata de aprender programación  en JavaScript (existen montones de tutoriales y recursos en línea para ello), sino de conocer una serie de pasos sencillos para diseñar una visualización, ya que los aplicaciones de mapas son visualizaciones de datos con el fin de informar a su audiencia. 

No todo es diseño, porque los usuarios *adoran* las aplicaciones reales, y no sobre papel. Veremos qué herramientas de desarrollo web tenemos a nuestro alcance y sobre todo utlizaremos la librería JavaScript [Leaflet.js](http://leafletjs.com/) para la creación de aplicaciones de ejemplo.  

## Contenido

### Semana 1: Kit de desarrollo
Videos:
* [1.1-intro](https://www.dropbox.com/s/nqmognaba6omzj0/uoc-1.1-intro.mp4?dl=0) (5:45): presentación curso y materiales docentes.
* 1.2-dev-tools (<5 min): Presentation videos JS y herramientas de desarrollo (Sublime Text 3, Chrome Dev Tools). 
* Videos de JavaScript basico del canal YouTube [ProgramaloTu - ProgramItYourself](https://www.youtube.com/playlist?list=PLA505F7842858BD06):
    * Conceptos básicos: [configuración navegador y la etiqueta script](https://www.youtube.com/watch?v=i5gZvW99WHU), [declaraciones y comentarios](https://www.youtube.com/watch?v=xkIezoi2JEM), [declaración de variables](https://www.youtube.com/watch?v=Exjy8Mnlao4) y [tipos de variables](https://www.youtube.com/watch?v=Gyjd7CI52Og&list=PLA505F7842858BD06&index=4), y  [operadores matemáticos y concatenación de cadenas (+)](https://www.youtube.com/watch?v=dP1KVNJxauA&list=PLA505F7842858BD06&index=5).
    * Funciones: [function](https://www.youtube.com/watch?v=4catKCNXFe0&index=6&list=PLA505F7842858BD06), [parámetros](https://www.youtube.com/watch?v=z3T0KOckcPM&list=PLA505F7842858BD06&index=7), [llamada a funciones](https://www.youtube.com/watch?v=fMTkPyAPil8&list=PLA505F7842858BD06&index=8), [variables locales y globales](https://www.youtube.com/watch?v=xQNPddQi_q0&list=PLA505F7842858BD06&index=9).
    * Condicionales [if](https://www.youtube.com/watch?v=H7duRLcaBT4&list=PLA505F7842858BD06&index=10), y [if-else](https://www.youtube.com/watch?v=o1drbk7KWak&list=PLA505F7842858BD06&index=11), y bucles [for](https://www.youtube.com/watch?v=gNNAuh9SUbw&index=16&list=PLA505F7842858BD06).
    * Eventos: [concepto de eventos](https://www.youtube.com/watch?v=Cj9Mhab0R0g&index=19&list=PLA505F7842858BD06), y [funciones que escuchan eventos](https://www.youtube.com/watch?v=MWxwZirp77g&index=20&list=PLA505F7842858BD06).
    * Arrays: [estructura de datos](https://www.youtube.com/watch?v=OqyeScn8nBk&index=27&list=PLA505F7842858BD06), [iterar un array](https://www.youtube.com/watch?v=raIMZdjx-aY&index=29&list=PLA505F7842858BD06), [métodos y propiedades de los arrays](https://www.youtube.com/watch?v=ukVj5wJz724&index=30&list=PLA505F7842858BD06). 
* 1.3-viz (<5 min): una mapa es una visualización para informar, explicar. Webs de ejemplo 

### Semana 2: Leaflet.js 
Videos:
* [2.1-intro](https://www.dropbox.com/s/pgp0c4uuas15upr/uoc-2.1-intro.mp4?dl=0) (6:52): presentación y navegación por la web de ejemplos y ejercicios para las semanas 2 y 3. 
* 2.2-leaflet (<5min): descripción ejemplo 01 de Leaflet "Carga y muestra un mapa base sobre un mapa".
* 2.3-leaflet (<5min): descripción ejemplo 04 de Leaflet "Carga datos (puntos) en csv desde un fichero".

Ejercicios: 
* [leaflet-01](http://cgranell.github.io/course-webmapping/exercises-leaflet/01-template.html)

### Semana 3: Leaflet.js 
Videos:
* 3.1-leaflet (<5min): descripción ejemplo 07 de Leaflet "Carga datos (puntos) en geojson desde un fichero local".

Ejercicios:
* [leaflet-02](http://cgranell.github.io/course-webmapping/exercises-leaflet/02-template.html)
* [leaflet-03](http://cgranell.github.io/course-webmapping/exercises-leaflet/03-template.html)  


### Semana 4: ESRI Leaflet plugin
Videos:
* 4.1-intro (<3 min): presentación contenido semana 
* 4.2-github (<3 min): navegación por los ejemplos del repositorio. 
* 4.3.esri-leaflet (<5 min): descripción ejemplo 03 de Esri Leaflet "Carga datos desde un servicio web ArcGIS".
* 4.4.esri-leaflet (<5 min): descripción ejemplo 07 de Esri Leaflet "Agrupación (clustering) de geometrías de tipo punto".
* 4.5.esri-leaflet (<5 min): descripción ejemplo 08 de Esri Leaflet "Mapas de calor (heatmaps) a partir de geometrias de tipo de punto".

Ejercicios:
* [esri-leaflet-01](http://cgranell.github.io/course-webmapping/exercises-esri-leaflet/01-template.html)
* [esri-leaflet-02](http://cgranell.github.io/course-webmapping/exercises-esri-leaflet/02-template.html)
* [esri-leaflet-03](http://cgranell.github.io/course-webmapping/exercises-esri-leaflet/03-template.html)
* [esri-leaflet-04](http://cgranell.github.io/course-webmapping/exercises-esri-leaflet/04-template.html)

### Semana 5: Tu problema, tu solución (<100 líneas) 
Videos:
* 5.1-intro (<3 min): presentacion práctica 

## Tareas a entregar
### PEC
La Prueba de Evaluación Continua (PEC) consiste en la realización de 7  ejercicios cortos de programación [marcados claramente en naranja](http://cgranell.github.io/course-webmapping/).

Fecha de entrega: Se recomienda enviar los ejercicios tal como se van completamente. La fecha máxima de entrega será el **ultimo día de la cuarta semana (27 Mayo 2015)**

### Práctica 
La Práctica o proyecto final, [marcado claramente en rojo](http://cgranell.github.io/course-webmapping/), consiste en la programación por parte de los estudiantes de una aplicación web de mapas como proyecto final de la asignatura. Los estudiantes podrán definir la temática del proyecto y deberán combinar varias funcionalidades vistas en las semanas previas en menos de 100 líneas de código. El proyecto final deberá incluir las siguientes características:
* Control de capas.
* Acceso a varias capas de datos (las que quieras).
* Simbología personalizada de los datos (puntos, líneas).
* Uso de popups para mostrar información asociada a la geometría (puntos, líneas).
* Uso de al menos una operación espacial (clustering, heatmap).

Fecha de entrega: **Último día del curso (3 de junio 2015)**

## Evaluación
* Intervenciones en el aula: 10% de la nota final.
* PEC (7 ejercicios propuestos): 40% de la nota final.
* Práctica (proyecto final): 50% de la nota final.

## Referencias
* Página principal de [Leaflet.js](http://leafletjs.com/)
* [Leaflet API](http://leafletjs.com/reference.html)
* Pagina principal de [ESRI Leaflet](https://github.com/Esri/esri-leaflet)
* [Ejemplos de ESRI Leaflet](http://patrickarlt.github.io/esri-leaflet/examples/)
* [ESRI Leaflet API](http://patrickarlt.github.io/esri-leaflet/api-reference/)
* [Eloquent JavaScript, Secodng Edition](http://eloquentjavascript.net/) e sun libro abierto sobre JavaScript y la programación de JS.

## Créditos
Videos de JavaScript basico del canal YouTube [ProgramaloTu - ProgramItYourself](https://www.youtube.com/playlist?list=PLA505F7842858BD06)

Icons made by [Freepik](http://www.flaticon.com/authors/freepik) from [www.flaticon.com](http://www.flaticon.com) is licensed by [CC BY 3.0](http://creativecommons.org/licenses/by/3.0/")

Servicios ArcGIS proporcionados por [UJI Smart Campus](http://smart.uji.es/) 

## Licencia
[Creative Commons Reconocimiento-CompartirIgual 3.0 España](http://creativecommons.org/licenses/by-sa/3.0/es/) (CC BY-SA 3.0 ES)]



