# Coffee Shop

En este proyecto se trabajó el uso de HTML + CSS, más específicamente del uso de los selectores en CSS y propiedades de tamaño, color, formato tipográfico, medidas relativas y posicionamiento automático, de manera que se creó una organización de una simulación de página de panel introductorio al plan de gobierno sobre el ingreso solidario (de carácter meramente estético, sin ninguna funcionalidad o interactividad con el usuario, exceptuando la posibilidad de llenar campos en un formulario, aunque la información llenada allí no se guarda en ninguna base de datos ni se puede usar para ejecutar otros procedimientos) a partir de un conjunto de archivos preestablecidos y un video de muestra.

**Recursos:** [https://drive.google.com/drive/folders/1QLBdT6aJ5_iCOYoBRRM4dCwIYsBJZKBx?usp=drive_link](https://drive.google.com/drive/folders/1QLBdT6aJ5_iCOYoBRRM4dCwIYsBJZKBx?usp=drive_link)<br/>
**Video de muestra:** [https://drive.google.com/file/d/1eBoiJWL8yxGUpLOF60WDRsaKe2CRA1Bg/view?usp=drive_link](https://drive.google.com/file/d/1eBoiJWL8yxGUpLOF60WDRsaKe2CRA1Bg/view?usp=drive_link)

|Tabla de contenidos|
|--|
|[¿Cómo ejecutar este archivo?](#Ejecucion)|
|[Funcionamiento del programa](#Funcionamiento)|

<a name="Ejecucion"></a>

## ¿Cómo ejecutar este archivo?

Para poder observar la página web creada en este proyecto se puede realizar de dos maneras diferentes:

1. Accediendo directamente a través de este link: https://dante-sal.github.io/Examen_HTML_SalamancaDante/
2. Clonando el repositorio desde una terminal linux a través del comando `git clone https://github.com/Dante-Sal/Examen_HTML_SalamancaDante` y abriendo el archivo index.html con el navegador web de su preferencia.

<a name="Funcionamiento"></a>

## Funcionamiento del programa

En esencia, el funcionamiento de este programa se basa en la modificación de atributos de diferentes elementos a través del uso de selectores CSS como clases, elementos o IDs. Simultáneamente, se hizo uso constante de divisiones anidadas siguiendo la metodología BEM para la asignación de nombres de clases, así como el acceso a estas divisiones mediante una ruta de selectores precisa.

Los primeros pasos de la generación del código HTML siguieron la siguiente lógica: en primer lugar se generó un sistema de organización basado en la segmentación de la página web en partes bien diferenciadas como encabezado, secciones y pie de página. Acto seguido, se estableció una estructura basada en la etiqueta div, diferenciando las distintas partes individuales de la interfaz para su correcto manejo de ubicación o asignación de estilos.

Por ejemplo, en el caso específico del apartado Inicio (sección 1), se tiene un bloque general que abarca lo que sería todo lo que se encuentra posicionado sobre la imagen de fondo (permitiendo el centrado y correcta distribución o separación de las dos subsecciones presentes en el apartado de Inicio), ramificando esta con una nueva división para cada elemento. Cada subsección posee un título, una descripción, unos contenidos y un botón; de forma de cada uno de estos elementos posee su propia etiqueta div aislada, propiciando un código limpio y ordenado que facilita el trabajo con hojas de estilo en cascada. En el caso de la subsección del formulario, encontramos en primera instancia una división para todo el recuadro blanco que contiene la información y dentro de esta un formulario que se subdivide en varios elementos como lo son los inputs, los labels y los textos (cada objeto posee una clase o nombre personalizado que facilita el manejo de estilos en CSS). Por otra parte, en lo que concierne al apartado de Ingreso Solidario / Conocer más, se tiene una división grande que abarca todos los elementos, los cuales son un título, una descripción y un botón. Cada uno de estos está alojado en etiquetas contenedoras para una mejor organización.

A través de atributos como width, height, los diferentes posibles valores de display y medidas relativas como vw y vmax, se pudo hacer un uso eficiente del posicionamiento automático de cada objeto, otorgando la posibilidad de organizar el sitio adecuadamente (tanto para computadores como para celulares). Finalmente, se aplicaron diversas propiedades específicas de diferentes objetos HTML (como background-color o width para los botones; o text-align o text-decoration y sus derivados para elementos de tipo texto como `<p>`, `<a>`, etc.), así como la importación de fuentes tipográficas al inicio del archivo .css.
