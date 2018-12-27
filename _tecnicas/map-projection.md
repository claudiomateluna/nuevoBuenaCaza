---
layout: articulos
titulo: Proyección de los Mapas
img: img/tecnicas/map-projection.png
categoria: [Tecnicas, pionerismo]
resumen: cuando se trata de extensiones grandes como las de un país un continente o de todo el globo se requieren otros tipos de proyecciones que eviten al mínimo la distorsión
orden: 42
---
**DIVERSOS TIPOS DE PROYECCIÓN**

Hemos visto que para territorios pequeños, no existen grandes distorciones debidas a la proyección, pero cuando se trata de extensiones grandes como las de un país, un continente o de todo el globo, se requieren otros tipos de proyecciones, que eviten al mínimo la distorsión.

**Proyección de Mercator**

Si consideramos a la tierra como un globo transparente y en el centro de la misma colocáramos una lámpara, si colocamos alrededor del globo un cilindro semi-transparente, veríamos que los meridianos son proyectados como líneas verticales colocadas a la misma distancia entre sí; en cambio, los paralelos también aparecerían como líneas paralelas horizontales entre sí, pero se irían separando al avanzar desde el ecuador a los polos, distorsionando enormemente las regiones cercanas a los polos, haciéndolas aparecer mayores de lo que son en realidad.  

La proyección de Mercator es por lo tanto muy útil para representar casi todo el globo en un plano, pero no puede representar las regiones polares. Por otro lado, sólo se considera exacta en las regiones cercanas al ecuador.

<div class="col col-12 sm-col-6 md-col-4 lg-col-3 mr1">

<amp-img src="{{site.baseurl}}/img/tecnicas/map-projection1.png" width="476" height="331" alt="proyección de Mercator" layout="responsive" class="rounded"></amp-img>

</div>

**Proyección Cilíndrica**

Si en lugar de proyectar sobre el cilindro semitransparente a todos los paralelos y meridianos, partiendo del centro de la tierra como en la proyección de Mercator, los proyectamos desde el eje terrestre y perpendiculares a él, obtenemos una proyección en la cual los paralelos aparecen como líneas paralelas y equidistantes pero ahora los meridianos aparecen como líneas paralelas que se van acercando entre sí, conforme nos alejamos del ecuador hacia los polos.

<div class="col col-12 sm-col-6 md-col-4 lg-col-3 img_right ml1">

<amp-img src="{{site.baseurl}}/img/tecnicas/map-projection2.png" width="486" height="328" alt="Proyección Cilíndrica" layout="responsive" class="rounded"></amp-img>

</div>

Otro tipo común de proyección global es la que se obtendría viendo a la tierra desde el espacio a una gran distancia desde una nave espacial, pero sólo muestra la mitad de la cara de la tierra.

**Proyecciones para Escala Media**

Cuando se trata de representar extensiones grandes, como un país o un continente, pero no todo el globo, se utilizan proyecciones hechas sobre planos o secciones de un cono, por ser más fáciles de realizar y representan algunas ventajas.

**Proyección Cónica**

<div class="col col-12 sm-col-12 md-col-6 lg-col-6 center">

<amp-img src="{{site.baseurl}}/img/tecnicas/map-projection3.png" width="541" height="539" alt="Proyección Cónica" layout="responsive" class="rounded"></amp-img>

</div>

<div class="col col-12 sm-col-12 md-col-8 lg-col-6 center">

<amp-img src="{{site.baseurl}}/img/tecnicas/map-projection4.png" width="608" height="272" alt="Proyección Cónica" layout="responsive" class="rounded"></amp-img>

</div>

<div class="col col-12 sm-col-8 md-col-6 lg-col-4 img_right ml1">

<amp-img src="{{site.baseurl}}/img/tecnicas/map-projection5.png" width="329" height="387" alt="Proyección de Bonne" layout="responsive" class="rounded"></amp-img>

</div>

**Proyección de Bonne**

La proyección de Bonne proyectada a partir de un punto central en donde se cortan un meridiano y un paralelo, sobre un plano tangente a este punto.

**Proyección de Lambert**

La proyección de Lambert es una variante mejorada de la proyección cónica. Está basada en la proyección de una porción de territorio sobre un cono que tiene su cúspide más alta que su base, que es tangente al paralelo medio de la región.

<div class="col col-12 sm-col-6 md-col-4 lg-col-3 mr1">

<amp-img src="{{site.baseurl}}/img/tecnicas/map-projection6.png" width="291" height="605" alt="Proyección de Lambert" layout="responsive" class="rounded"></amp-img>

</div>

Dos convenciones que perfeccionan y complementan a una proyección simple son:

1a.- Los meridianos están representados por líneas que, partiendo de la cúspide del cono, cortan al paralelo medio en el punto donde el cono de desarrollo es tangente al meridiano que representa. Las deformaciones en longitud son nulas sobre el paralelo de origen pero aumentan rápidamente cuando uno se aleja hacia el norte o sur del mismo.

2a.- Los paralelos se representan por círculos concéntricos que parten de la cúspide del cono.

Los mapas de la República Mexicana que edita el Instituto Nacional de Estadística, Geografía e Informática, (INEGI) que depende de la Secretaría de Programación y Presupuesto a una escala de 1:5’000,000, utilizan este tipo de proyección.

**Proyecciones para Áreas Pequeñas**

En pequeñas porciones de terreno se utilizan planos topográficos, en los que no aparece la redondez de la tierra como un dato importante. Sin embargo, para unir varios planos y que haya correspondencia entre ellos, se utiliza comúnmente la proyección de Mercator, pero modificándola, para sacar ventaja del hecho que no deforma grandemente a las regiones cercanas al ecuador.

**Proyección Universal Transversa de Mercator**

La figura 1 muestra la proyección convencional de Mercator como la hemos visto; en la figura 2 aparece la proyección transversa, o sea la proyección no del ecuador, sino de un meridiano cualquiera.

Si proyectamos únicamente una área de 3 grados a los lados del meridiano medio como en la figura 3, las áreas representadas tienen muy poca deformación.

En lugar de ser tangente al ecuador (1) 

el cilindro es tangente al meridiano (2)

<div class="col col-12 sm-col-6 md-col-4 lg-col-3 mr1">

<amp-img src="{{site.baseurl}}/img/tecnicas/map-projection7.png" width="142" height="233" alt="Proyección Universal Transversa de Mercator" layout="responsive" class="rounded"></amp-img>

</div>

<div class="col col-12 sm-col-6 md-col-4 lg-col-3 mr1">

<amp-img src="{{site.baseurl}}/img/tecnicas/map-projection9.png" width="224" height="177" alt="Proyección Universal Transversa de Mercator" layout="responsive" class="rounded"></amp-img>

</div>

<div class="col col-12 sm-col-6 md-col-4 lg-col-3 mr1">

<amp-img src="{{site.baseurl}}/img/tecnicas/map-projection8.png" width="149" height="180" alt="Proyección Universal Transversa de Mercator" layout="responsive" class="rounded"></amp-img>

</div>

La tierra está recortada en 60 husos de 6º.

Cada huso posee su meridiano medio (línea punteada).

En esta forma obtenemos la proyección de un gajo de 6º de ancho únicamente, pero si hacemos girar 60 veces al cilindro, obtenemos la proyección de toda la tierra, como vemos en la figura 4.

El cilindro (A, B. C) gira alrededor de la tierra —60 veces— para formar los husos (A’, B’, C’).

La República Mexicana está comprendida entre los gajos o husos del 11 al 16, con paralelos medios de 117º, 111º, 105º, 99º 93º y 87º.

Los mapas de la República a una escala de 1:50,000 son parte de una proyección de este tipo. Cada huso se divide en cuadros de 4º de latitud, o sea que abarcan una superficie comprendida entre 6º de longitud por 4º de latitud.

Cada uno de estos cuadros, se subdivide a su vez en cuatro cuadrantes de 3º por 2º, denominados con las letras A, B, C, y D.

Por último, los cuadrantes están formados por "cartas" que abarcan únicamente 20 minutos de longitud por 15 de latitud.

<div class="col-12 sm-col-12 md-col-8 lg-col-6 center">

<amp-img src="{{site.baseurl}}/img/tecnicas/map-projection10.png" width="532" height="593" alt="Proyección Universal Transversa de Mercator" layout="responsive" class="rounded"></amp-img>

</div>