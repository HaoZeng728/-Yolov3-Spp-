 <img src="https://github.com/paulast/AIVA_2022-Reconocimiento-de-texto-en-crotales-/blob/main/images/cv-solutions.png?raw=true" width="150" height="150" align="center"/>

 
 #  <p align="center"> Proyecto: Reconocimiento de texto en crotales </p>
 

## Problema planteado


<p align="justify">  El término trazabilidad en el sector ganadero hace referencia a la capacidad de rastrear a un animal productor de alimentos durante todas las etapas de producción, elaboración y distribución que conforman la cadena alimentaria, constituyendo por tanto, un elemento indispensable para conceder garantías relativas a la seguridad de los alimentos y preservar la sanidad de las personas y animales.  </p>

<p align="justify">En el caso específico del ganado bovino, la trazabilidad se garantiza entre otros, por medio de dos sistemas fundamentales:</p>
<p align="justify"> - <b>Crotal:</b> Etiqueta generalmente de material plástico que se coloca en las orejas del animal y que permite su identificación individual. La información recogida en los crotales puede observarse en la imagen mostrada a continuación. </p>

<p align="center">
  <img src="https://github.com/paulast/AIVA_2022-Reconocimiento-de-texto-en-crotales-/blob/main/images/crotal.jpg?raw=true" width="700">
</p>

<p align="justify">  - <b>Documento de Identificación de Bovinos (D.I.B)</b>, en el que figuran los datos propios del animal y de la explotación ganadera a la que pertenece. Las características propias de este documento son detalladas en la siguiente imagen.</p>

<p align="center">
  <img src="https://github.com/paulast/AIVA_2022-Reconocimiento-de-texto-en-crotales-/blob/main/images/DIB.JPG?raw=true" width="600">
</p>

<p align="justify">La evolución tecnológica que ha experimento la sociedad en las últimas décadas ha conducido a un incremento exponencial en la automatización de los procesos en la industria, siendo éste el principal detonante del surgimiento de este proyecto, cuyo principal cometido consiste en el <b>reconocimiento de texto en crotales de ganado bovino, por medio de un algoritmo basado en Visión Artificial</b>, pretendiendo automatizar la identificación de animales principalmente en mataderos.</p>

## Producto propuesto

Ante la problemática previamente descrita nuestra empresa propone el siguiente producto:

<p align="center">
  <img src="https://github.com/paulast/AIVA_2022-Reconocimiento-de-texto-en-crotales-/blob/main/images/eartag.png?raw=true" width="300">
</p>

<p align="justify">Eartag Decoder, reconocerá los dígitos identificativos de los crotales y proporcionará estos números al responsable pertinente para mejorar la trazabilidad de los animales en la ganadería y los mataderos. De esta forma, se comprobará que los datos del animal se ajustan a los existentes en el Documento de Identificación de Bovinos (D.I.B.). El objetivo de este proceso será garantizar al consumidor la veracidad de los datos, además de servir como herramienta fundamental para garantizar la seguridad de los alimentos, las personas y los animales.</p>

<p align="justify"> En lo relativo a la funcionalidad del producto propuesto, ésta puede observarse de forma esquematizada en el siguiente diagrama.
</p>

<p align="center">
  <img src="https://github.com/paulast/AIVA_2022-Reconocimiento-de-texto-en-crotales-/blob/main/images/diagrama.PNG?raw=true" width="900">
</p>

<p align="justify"> Como puede observarse, para acceder al sistema, el usuario deberá registrase e iniciar sesión. Tras esto, accederá a las imágenes obtenidas con el sistema de visión que se posea bajo unas condiciones de iluminación determinadas. Posteriormente, podrá iniciar el reconocimiento automático de las imágenes, que devolverá un archivo CSV con el número del crotal y el nombre de la imagen. 
</p>

<p align="justify"> Adicionalmente, si el cliente lo desea, se podrá integrar en el sistema de la empresa para poder realizar un control diario de la trazabilidad del ganado y emitir una alarma en caso de una predicción errónea que no corresponda con alguno de los crotales existentes.  
</p>
