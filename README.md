# DIU20
Prácticas Diseño Interfaces de Usuario 2019-20 (Economía Colaborativa) 

Grupo: DIU1_Cohete.  Curso: 2019/20 

Proyecto: Pazifika

Descripción: Pretendemos desarrollar una aplicación para poder buscar compañeros de viaje de una manera sencilla y ágil, con muchas opciones para filtrar por viajes y una interfaz clara y limpia.

Logotipo: ![Pazifika](img/logo.png)

Miembros
 * :bust_in_silhouette:   Francisco Domínguez Lorente     :octocat:     
 * :bust_in_silhouette:  Miguel Ángel Posadas Arráez     :octocat:

----- 

En esta práctica estudiaremos un caso de plataforma de economía colaborativa y realizaremos una propuesta para su diseño Web/movil. Utilizaremos herramientas y entregables descritos en el siguiente CheckList (https://github.com/mgea/UX-DIU-Checklist) 


Qué es economia colaborativa: Martínez-Polo, J. (2019). **El fenómeno del consumo colaborativo: del intercambio de bienes y servicios a la economía de las plataformas**, *Sphera Publica, 1*(19), 24-46. http://sphera.ucam.edu/index.php/sphera-01/article/view/363/14141434

>>> Este documento es el esqueleto del report final de la práctica. Aparte de subir cada entrega a PRADO, se debe actualizar y dar formato de informe final a este documento online. 


# Proceso de Diseño 

## Paso 1. UX Desk Research & Analisis 

![Método UX](img/Competitive.png) 1.a Competitive Analysis
-----

Pazifiko es una plataforma que permite buscar compañeros de viaje, tanto organizar un viaje de modo que usuarios de la plataforma se unan,
como buscar viajes ya organizados por otros usuarios. Se puede leer el análisis completo a través de [este enlace](https://github.com/migue99angel/DIU20/blob/master/P1/README.md).

![Método UX](img/Persona.png) 1.b Persona
-----
![Persona 1](img/persona1.jpg)
![Persona 2](img/persona2.jpg)

Se detalla la decisión de incluir estar personas en el informe disponible a través de [este enlace](https://github.com/migue99angel/DIU20/blob/master/P1/README.md).

![Método UX](img/JourneyMap.png) 1.c User Journey Map
----
![Journey Map Jose Luis](img/journeyMap_JoseLuis.jpg)
![Journey Map Maria Teresa](img/journeyMap_MariaTeresa.jpg)

Se comenta brevemente cada User Journey Map en el [siguiente enlace](https://github.com/migue99angel/DIU20/blob/master/P1/README.md).

![Método UX](img/usabilityReview.png) 1.d Usability Review
----
- [Enlace al documento](https://github.com/migue99angel/DIU20/blob/master/P1/Usability-review-complete.pdf)
- Valoración final (numérica): 66
- Comentario sobre la valoración: Tras un exhaustivo análisis, el cual queda reflejado en [este documento](https://github.com/migue99angel/DIU20/blob/master/P1/Usability-review-complete.pdf), hemos llegado a la conclusión de que la página ofrece una experiencia de usuario aceptable, sin fallos sustanciales de diseño, pero cuenta con  problemas de disponibilidad que perjudican a su imagen y a los usuarios.


## Paso 2. UX Design  


![Método UX](img/feedback-capture-grid.png) 2.a Feedback Capture Grid
----

| **Interesante**<br>                                                                                                                                                                                                                                                    | **Críticas**<br>                                                                                                                                                                                                                                                                                                                                                 |
|-----|-----|
| - Diseño limpio. Se destaca lo importante y utiliza una paleta de colores agradable a la vista.<br>- Interfaz amigable. La información está concentrada y se destaca lo importante.<br>- El panel de control de usuario destaca las opciones importantes y es claro. | - Añadir un sistema de mensajes para poder establecer contacto de manera más fácil con compañeros de viaje.<br>- Permitir la búsqueda de viajes por varios aspectos.<br>- Permitir añadir en la descripción el número de integrantes que se buscan y los integrantes que buscan compañeros.<br>- Algunos botones requieren de haber iniciado sesión o haberse registrado previamente en la aplicación para poder utilizarlos.                                                                             |
| <div align="center">**Preguntas**</div>                                                                                                                                                                                                                                 | <div align="center">**Nuevas ideas**</div>                                                                                                                                                                                                                                                                                                                       |
| - Hay un fallo a la hora de mostrar el mapa de ubicación. ¿Se podría mejorar?<br>- ¿Se podrían añadir más opciones para filtrar viajes?<br>- Estaría bien tener una opción adicional para hacer amigos en la plataforma y poder hacer viajes conjuntos.              | - Mostrar ejemplos de viajes que estén activos actualmente, de diferentes categorías.<br>- Intentar que cuando un usuario se registre, este consiga publicar un viaje o se inscriba en uno existente en las primeras visitas del usuario.<br>- La plataforma no cuenta con redes sociales de ningún tipo. No se puede contactar con ellos más allá del correo. |
  
  
Proponemos una aplicación que incluya una gran variedad de opciones de búsqueda, así como poder publicar un viaje con las etiquetas suficientes para que personas con gustos similares puedan encontrar tu viaje más fácilmente.

Incorporamos también una galería de imágenes donde los viajeros puedan publicar las imágenes de sus viajes y otros usuarios puedan admirar los lugares donde recientemente han ido otros usuarios que han usado la plataforma.

Con la incorporación de filtros adicionales de búsqueda y la posible mejora de los botones en relación a Publicar Viaje *(hay que iniciar sesión o registrarse antes de poder publicar un viaje)* se solventan los problemas propuestos por los usuarios anteriormente.

![Método UX](img/Sitemap.png) 2.b Tasks & Sitemap 
-----

**Matriz de Tareas/Usuarios**

| Grupos de Usuarios           | Usuario Logueado | Usuario No Logueado |
|------------------------------|------------------|---------------------|
| Iniciar Sesión               |                  | H                   |
| Registrarse                  |                  | M                   |
| Publicar Viaje               | M                |                     |
| Apuntarse a Viaje            | M                |                     |
| Consultar viajes disponibles | H                | M                   |
| Contactar con Soporte        | H                | M                   |
| Publicar un comentario       | M                |                     |

</div>
<br>

**Sitemap**  
![Sitemap](P2/sitemap.png)


![Método UX](img/labelling.png) 2.c Labelling 
----

| Etiqueta | Nota                                                                                                       |
|----------|------------------------------------------------------------------------------------------------------------|
| Buscar   | Herramienta para filtrar por viajes según a unos criterios que estima el usuario                           |
| Galería  | Recopilación de imágenes realizadas durante los distintos viajes de la plataforma que ya han tenido lugar  |
| Contacto | Página en la que se incluyen los distintos medios de contacto con el soporte técnico de la plataforma      |
| Viajes   | Sección donde se publican y se pueden ver los distintos viajes que se pretenden organizar en la plataforma |
| Perfil   | Sección donde se sitúan todas las opciones de configuración disponibles para el usuario                    |
| Iniciar Sesión  | Procede a la identificación de los usuarios ya registrados previamente en la plataforma             |
| Registrarse   | Procede a dar de alta a un usuario en la plataforma                                                   |

![Método UX](img/Wireframes.png) 2.d Wireframes
-----

<div align="center">

**Página principal**  
![Sitemap](P2/Boceto/Index.html.png)  
<br>

</div>

[Resto de wireframes](https://github.com/migue99angel/DIU20/tree/master/P2)

## Paso 3. Mi equipo UX-Case Study 


![Método UX](img/moodboard.png) 3.a ¿Como se cuenta un UX-Case Study?
-----


Cuando una empresa empieza a diseñar una aplicación, primeramente hace un estudio previo sin tener en cuenta la opinión de los usuarios. Posteriormente, una vez hayan planteado
el esquema inicial de la aplicación, se entrevistan con los usuarios y obtienen los problemas y las preocupaciones reales de los usuarios potenciales. A continuación, comienzan
a desarrollar los mockups y bocetos en base a eso. 

En el siguiente enlace accedemos a una descripción más detallada. [Enlace a la especificación detallada](P3/README.md)

![Método UX](img/landing-page.png)  3.b Logotipo
----

El logotipo diseñado es el siguiente:  
![Pazifika](img/logo.png)

Hemos usado una herramienta online de logos prefabricados y la hemos adaptado a nuestras necesidades. La resolución empleada es la mejor que ofrecía la página mencionada
y creemos que es suficiente para la página. El logotipo se podría usar como foto de perfil en las redes sociales, pero se necesitarían más diseños para cubrir las cabeceras
y otros aspectos de los perfiles.

![Método UX](img/guidelines.png) 3.c Guidelines
----

Hemos optado por aplicar los patrones *Call-to-Action Buttoms* para que el usuario tenga siempre presente que acciones puede realizar, así como *Progress Trackers* en los formularios ya que es importante conocer el progreso realizado miestras estos son rellenados y *Search Resulsts Design* ya que un buen diseño de la página de resultados en fundamental. 

En el siguiente enlace detallamos mucho más lo anteriormente comentado, así como comentar los detalles que hemos utilizado siguiendo la guideline de Google y especificación de la paleta de colores y fuente utilizada. [Enlace a la especificación detallada](P3/README.md)

![Método UX](img/mockup.png)  3.d Vídeo
----

https://drive.google.com/open?id=1sPXz_SW_37V6XT4Jr1sQY5hqU069t2Sx


## Paso 4. Evaluación 


![Método UX](img/ABtesting.png) 4.a Casos asignados
----


### Caso 1

Para el primer caso los compañeros han analizado una plataforma de economía colaborativa para la organización de viajes o incluso la búsqueda de compañero de viaje. Como propuesta de valor sobre la página que han analizado en la práctica 1 proponen principalmente una mejora del deiseño de la página principal.   

[Repositorio](https://github.com/raulsoria98/DIU20) || [Hoja de evaluación](https://github.com/migue99angel/DIU20/blob/master/P4/DIU1.HOOKAH_review.xlsx)

### Caso 2

Para este caso 2, el compañero ha analizado una aplicación para alquiler de pisos por habitaciones o completos, incluyendo una agenda cultural para ver los eventos cercanos a los nuevos alojamientos. Como propuesta de valor, se aporta que la agenda cultural sea más completa de modo que se puedan añadir eventos a la misma así como observar los eventos antes de alquilar una habitación, de modo que estos eventos aporten un valor añadido a cada habitación. También propone la introducción de ayudas como comandos de voz.

[Repositorio](https://github.com/Jovalga/DIU20) || [Hoja de evaluación](https://github.com/migue99angel/DIU20/blob/master/P4/DIU2.JVG_review.xlsx)

### Caso 3

Para el caso 3 los compañeros han analizado una aplicación para aprender a cocinar en vivo, degustar comida y hacer tours gastronómicos. Como propuesta de valor los compañeros proponen la creación de un diseño en el que prime la eficiencia y la velocidad del sistema ya que en el análisis de la práctica 1 han detectado que el principal problema de la plataforma que analizaban era el tiempo invertido por parte del usuario en el uso de la aplicación. 

[Repositorio](https://github.com/Mxgang/DIU20) || [Hoja de evaluación](https://github.com/migue99angel/DIU20/blob/master/P4/DIU3.Crescendum_review.xlsx)

![Método UX](img/usability-testing.png) 4.b User Testing
----

Hemos escogido como persona ficticia a [María Teresa](https://github.com/migue99angel/DIU20/raw/master/img/persona2.jpg). Recordamos que esta persona ficticia tenía pareja y un hijo. Vive con su pareja en Madrid, es fisioterapeuta y le gustan los viajes tranquilos.

### Experiencia 1
A María Teresa le surge la misma preocupación que con Pazifika. Ella y su familia desea hacer un viaje con otra pareja de estructura similar: una pareja con un hijo. María Teresa no sabe si PlanBClub tendrá las opciones y los filtros disponibles para poder satisfacer todas sus necesidades.

### Experiencia 2
María Teresa y su familia han alquilado un piso cerca de una zona céntrica de su próximo viaje a Budapest. No tienen mucho tiempo que perder ya que será un viaje corto. Ella y su familia ya han mirado los eventos cercanos e incluso habían obtenido las entradas de varios eventos. Cuando ya están en Budapest, se preparan para ir a uno de esos eventos en el teatro. Una vez llegan allí, les informan de que la obra se había cancelado varias horas antes por enfermedad de varios actores. No han tenido forma de saber que eso iba a pasar y la aplicación no les ha informado de la situación.

### Experiencia 3
María Teresa y su familia quieren probar un sitio nuevo para cenar cerca de su urbanización. Un amigo de la pareja de María Teresa le recomienda una aplicación llamada SweetIt! Inicialmente ilusionados la pareja comienza a mirar los diversos restaurantes por categorías en los que pueden hacer una reserva. A medida que van viendo más restaurantes, se dan cuenta que en muy pocos de ellos se incluye una opción clara de "Menú Infantil", quizás directamente porque no tienen menú infantil en el restaurate, o porque no figura en la aplicación. Al final acaban recurriendo a una de las opciones de siempre al no tener información clara sobre el menú infantil para su hijo.


![Método UX](img/Survey.png) 4.c Ranking
----

Para concluir con la práctica, creemos que ha sido una práctica interesante de realizar porque hemos tenido que mirar en detalle el trabajo de nuestros compañeros: su propuesta de valor, cómo han efocado el diseño de su aplicación, los bocetos y una de las partes más interesantes: el vídeo de introducción a su propuesta de valor.

También nos ha parecido interesante el tener distintas temáticas entre los diferentes grupos. Con el primero de los grupos, al ser el mismo que el nuestro teníamos algo más de experiencia y familiarización, pero con los otros dos, al ser nuevos y tratar de temáticas algo diferentes ha sido curioso analizarlos y ver cómo han planteado sus prácticas.

Por último, para concluir con un pequeño ranking, queremos destacar el [Caso 2](https://github.com/Jovalga/DIU20), por su completitud y de una buena extensión y cuidando los detalles sobre todo del vídeo de introducción y de los bocetos. Los otros dos casos los ponemos un poco por debajo, pero ambos también son muy buenos y merecen también su reconocimiento.


## Paso 5. Rediseño de práctica  
La versión anterior de las prácticas de la asignatura se encuentra disponible, según lo especificado en el guión de la entrega adicional en la branch **_beta_**. Se puede acceder a ella seleccionándola en el menú superior o a través de [este enlace](https://github.com/migue99angel/DIU20/tree/beta).

Este rediseño de la práctica se realiza siguiendo las evaluaciones de nuestros compañeros, así como del checklist proporcionado por el profesor. Se adjuntan enlaces a cada una de ellas:

- Evaluación de DIU1.Cereza: [PDF](https://github.com/DavidGmezHdez/DIU20/blob/master/P4/DIU1.COHETE_review.pdf)/[Excel](https://github.com/DavidGmezHdez/DIU20/blob/master/P4/DIU1.COHETE_review.xls)
- Evaluación de DIU2.EscuadrónMapache: [PDF](https://github.com/Galactic-O/DIU20/blob/master/P4/UXCaseStudyReview-DIU1Cohete.pdf)/[Excel](https://github.com/Galactic-O/DIU20/blob/master/P4/UXCaseStudyReview-DIU1Cohete.xls)
- Evaluación de DIU3.AMRM: [PDF](https://github.com/suribel/DIU20/blob/master/P4/COHETE.pdf)/[Excel](https://github.com/suribel/DIU20/blob/master/P4/COHETE.xlsx)
- Checklist: [PDF](https://github.com/migue99angel/DIU20/blob/master/Bonus/A1_DIU_Checklist-A1_Cohete.pdf)

### 5.1 Rediseño del análisis competitivo
Obtenemos información tanto del checklist elaborado por el profesor tanto de las tres evaluaciones de nuestros compañeros de que el análisis competitivo es algo pobre y escaso de información. Tienen razón estas valoraciones y por tanto hemos hecho un análisis competitivo de algunas otras aplicaciones que podrían hacer competencia a Pazifika.

Se puede leer el análisis completo a través de [este enlace](https://github.com/migue99angel/DIU20/blob/master/P1/README.md).

### 5.2 Mejoras en Personas y User Journey Map
Otro de los posibles puntos de mejora que se detallan tanto en el checklist proporcionado por el profesor como por los compañeros de clase son las Personas ficticias propuestas y los User Journey Map correspondientes.

En cuanto a las personas, algunos detallan que María Teresa es una Persona adecuada, que encaja perfectamente y no tiene ninguna incosistencias. Sin embargo, en cuanto a José Luis consideran que es una Persona ficticia demasiado forzada para encajar en el propósito de la propuesta de valor y que debería ser cambiada.

En cuanto a esta persona, a José Luis, hemos considerado que no tiene mucho sentido utilizar una Persona que tiene grandes capacidades para socializarse porque esta persona se adaptaría a cualquier circustancia, sería más interesante que sea una persona con menos capacidades sociales con objetivo de observar como se desarrollaría su uso en una aplicación de este estilo. 

Para los User Journey Maps hemos recibido críticas de que estos carecen de conflictos de uso. Hemos mejorado acordemente los Journey Maps para reflejar cambios más relevantes y situaciones más realistas.

Los cambios en las imágenes y algunas conclusiones adicionales están disponibles en [P1/README.md](https://github.com/migue99angel/DIU20/blob/master/P1/README.md).

### 5.3 Mejora del Usability Review

Para la mejora de este apartado se han tenido en cuenta las anotaciones que el profesor propone en la checklist "Conclusion no acorde con puntuacion", y es que en nuestra conclusión inicial poníamos una calificación de 66 y en la conclusión nos centrabamos demasiado en los errores de rendimiento. 

Consideramos que la calificación es la misma (66 puntos - Moderate) ya que el análisis se realizó correctamente, pero efectivamente la conclusión era bastante mejorable, ahora hacemos hincapié en que efectivamente la página tiene un diseño correcto, sin olvidar aquellos problemas de disponibilidad que lastran un poco a la plataforma.

Con respecto a las indicaciones propuestas por nuestros compañeros como valoración de este apartado en concreto hay disparidad de opiniones, un grupo nos lo califica como excelente, 
argumentando que está bien realizado y que ha servido para detectar errores. Por otro lado nos encontramos a dos grupos que lo califican como pobre y muy pobre, uno de ellos no aporta ningún comentario realizando una crítica constructiva y el otro grupo dice que es muy breve.

Pensamos que es posible que estos dos últimos grupos hayan enfocado su análisis en la conclusión que aparece en el README, sin haber consultado el documento incluido en la carpeta de la Práctica 1 donde se elabora un análisis detallado.

### 5.4 Mejora del Feedback Capture Grid
Uno de los principales factores que también requerían mejoras según el checklist del profesor era el Feedback Capture Grid. Como punto bueno, identificaba los problemas correctamente y en general estaba bastante bien, pero le faltaba un punto importante y del que casi carecía de sentido si no se incluía: ¿resuelve los conflictos de los usuarios planteados en la primera parte del estudio?

Evidentemente en nuestras primeras versiones esto no se contemplaba, y ahora se ha mejorado para incluir y mejorar los problemas que los usuarios se han encontrado según lo comentado en los User Journey Maps. Este Feedback Capture Grid mejorado se puede encontrar anteriormente en este documento.

Adicionalmente, también se nos indica que no se incluye una propuesta de valor. Cabe indicar que esto se habló con el profesor en una tutoría y se incluyó posteriormente.

### 5.5 Labelling y Sitemap
Se han aplicado pequeñas mejoras al belling, que incluyen el inicio de sesión y el registro.

El sitemap también se ha mejorado para que sea más acorde a lo que se pide como sitemap. Tanto en el checklist como en las evaluaciones de los compañeros, se argumenta que el sitemap aportado anteriormente era bastante pobre.

Por tanto, está disponible anteriormente en este documento el *sitemap* actualizado. Además, también se puede acceder a través de [este enlace](https://github.com/migue99angel/DIU20/blob/master/P2/sitemap.png).

### 5.6 Wireframes
En cuanto a los wireframes proponemos a continuación dos nuevos bocetos que contienen algunos cambios que venían reflejados tanto en la checklist proporcionada por el profesor como por las evaluaciones delos compañeros. Hemos decidido dejar en la sección correspondiente los wireframes antiguos, y solo proponer dos versiones de los mismos. Los cambios realizados *(listados abajo)* se aplicarían idealmente para todos los wireframes, pero consideramos que no es necesario volver a hacerlos todos de nuevo.

<p align="center">

**Página principal**  
![Sitemap](Bonus/index.png)  
<br>

**Contacto**  
![Sitemap](Bonus/contacto.png)  
<br>

</p>

La diferencia con respecto a los wireframes anteriores es que se ha añadido la navegación *(las tres barras horizontales que hacen las veces de menú en versión móvil)*, los botones de inicio de sesión y registrarse en la página principal, así como u buscador simple y una sección de footer. Consideramos que ahora los bocetos se adaptan mejor al rediseño propuesto.

Estos bocetos también están disponibles a través de [este elace](https://github.com/migue99angel/DIU20/tree/master/Bonus).

### 5.7 Conclusiones de la Práctica de Bonus
Para concluir con este documento, dejamos una conclusiones finales sobre la realización de esta práctica extra de la asignatura.

En primer lugar hemos podido observar cómo hemos ido mejorando conforme realizamos las prácticas. Concretamente la Práctica 1, según la checklist y las evaluaciones de nuestros compañeros estaba muy mejorable. La Práctica 2 estaba algo mejor, pero aún había algunas cosas que mejorar bastante y otros detalles. Finalmente, la Práctica 3 es que la generalmente ha gustado más y estaba mejor hecha.

La opción de poder subir nota y mejorar algunos aspectos que nos parecían necesarios para que las prácticas estuviesen mejor, nos ha dado una oportunidad para pulir esos aspectos que el profesor había comentado previamente en clase y que nuestros compañeros también nos indicaron a través de sus evaluaciones.

También cabe destacar que gracias a toda la información que tenemos ya disponible de la asignatura y más concretamente de la realización de las Prácticas, no ha sido una tarea especialmente difícil mejorar los aspectos comentados en esta sección del documento.
