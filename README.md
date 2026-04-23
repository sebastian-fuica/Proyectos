Portafolio Personal HTML y CSS:
Este proyecto corresponde a un portafolio personal desarrollado como una página web de una sola vista. Fue construido con HTML y CSS, siguiendo una estructura semántica y organizada, con el objetivo de presentar información personal, habilidades, proyectos y un formulario de contacto.

La página está pensada para funcionar como una presentación profesional básica, mostrando distintas secciones dentro de un mismo sitio y utilizando estilos visuales para mejorar la apariencia, la distribución del contenido y la experiencia del usuario.

¿Cómo funciona el proyecto?:
El proyecto funciona a partir de dos archivos principales:

index.html: contiene toda la estructura y el contenido de la página.
estilos.css: contiene los estilos visuales que le dan diseño a la web.
Además, existe una carpeta llamada Imagenes, que almacena los archivos de imagen utilizados en el sitio, especialmente en la sección de proyectos.

Cuando se abre el archivo index.html en el navegador, este carga la estructura de la página y luego aplica los estilos definidos en estilos.css. Después, busca las imágenes en la carpeta correspondiente para mostrarlas en pantalla.

Estructura general del sitio:
La página está dividida en varias secciones, cada una con una función específica:

Header y navegación:
En la parte superior se encuentra el encabezado del sitio junto con la barra de navegación. Esta sección permite desplazarse a distintas partes de la página mediante enlaces internos.

La navegación funciona usando anclas, es decir, cada enlace del menú apunta al id de una sección específica del sitio. De esta manera, al hacer clic en una opción del menú, el navegador lleva directamente a esa parte de la página.

Sección “Sobre mí”:
Esta sección presenta información personal y una breve descripción profesional. Aquí se usan títulos, párrafos y etiquetas de texto para mostrar de forma clara quién es la persona del portafolio, qué está estudiando y cuáles son sus intereses.

También incluye un bloque complementario con datos personales, organizado para separar la información principal de la información adicional.

Sección “Habilidades”:
Esta parte muestra las tecnologías y competencias del portafolio. Se organiza mediante una tabla para representar información de forma estructurada, y además incluye listas ordenadas y desordenadas para mostrar competencias técnicas y ruta de aprendizaje.

También se agregaron barras visuales de progreso para representar el nivel de dominio de algunas tecnologías. Estas barras no funcionan con programación, sino con HTML y CSS: una parte actúa como fondo y otra parte como relleno, indicando visualmente el porcentaje de avance.

Sección “Proyectos”:
En esta sección se muestran algunos trabajos o ejemplos de proyectos. Cada proyecto se presenta como una tarjeta visual con imagen, título y descripción.

Para organizar esta parte se utilizó una estructura con figure y figcaption, lo que permite relacionar correctamente una imagen con su contenido descriptivo.

La distribución de las tarjetas se hizo con CSS Grid, de manera que los proyectos se ordenan en columnas y se ven más limpios visualmente.

Sección “Contacto”
Aquí se incluye un formulario de contacto con campos para nombre, correo, asunto y mensaje. También contiene un botón para enviar la información.

El formulario cuenta con validación básica de HTML5 mediante atributos como required, por lo que el navegador exige completar los campos antes de enviarlo.

Además, al lado del formulario se muestra un bloque con información de contacto, como correo, ciudad, teléfono y GitHub.

Footer
En la parte final se encuentra el pie de página. Esta sección cumple la función de cerrar visualmente el sitio e incluir información general, como nombre, derechos reservados y accesos a redes o enlaces externos.

Diseño y estilos:
Todo el diseño visual del sitio fue realizado en el archivo estilos.css. Allí se definieron colores, tamaños, espacios, bordes, sombras y distribución de los elementos.

El CSS permite que el contenido no solo se vea ordenado, sino también más profesional y cercano a una maqueta real de portafolio.

Se utilizaron dos técnicas importantes de diseño

Flexbox:
Flexbox fue utilizado para alinear y distribuir elementos en secciones donde convenía trabajar en fila o columna, como la navegación, el contacto y otras zonas del sitio.

CSS Grid
Grid fue utilizado especialmente en la galería de proyectos, para ordenar las tarjetas en columnas y mantener una estructura visual limpia.

Diseño responsive
El sitio también incluye adaptación para distintos tamaños de pantalla. Esto se logró mediante media queries, permitiendo que la página cambie su distribución cuando se visualiza en tablet o celular.

Por ejemplo, una sección que en computador se muestra en varias columnas puede pasar a mostrarse en una sola columna en pantallas más pequeñas, mejorando la lectura y la navegación.

Uso de imágenes
Las imágenes del proyecto están guardadas dentro de la carpeta Imagenes. Estas se llaman desde el HTML mediante la ruta correspondiente.

Para que funcionen correctamente, el nombre de la carpeta y de cada archivo debe coincidir exactamente con lo escrito en el código. Si hay diferencias en mayúsculas, minúsculas o extensiones, las imágenes no se mostrarán.

Tecnologías utilizadas
Este proyecto fue desarrollado utilizando:

HTML5
CSS3
Visual Studio Code

Objetivo del proyecto:
El objetivo principal de este trabajo es aplicar conocimientos básicos y medios de desarrollo web front-end, utilizando etiquetas HTML semánticas, estilos con CSS, estructura visual organizada, formulario, tablas, listas, imágenes y control de versiones con GitHub.

También busca representar un portafolio personal funcional, visualmente claro y alineado con los contenidos aprendidos en clases y el uso de apuntes subidos en la intranet de INACAP.

Cómo visualizar el proyecto:
Para ver el proyecto, basta con abrir el archivo index.html en un navegador web. Es importante que el archivo CSS y la carpeta de imágenes se mantengan dentro del mismo proyecto para que todo cargue correctamente.

Conclusión:
Este portafolio es una página web construida para reunir distintos elementos fundamentales del desarrollo front-end en un solo proyecto. Combina estructura, contenido, diseño y organización, permitiendo presentar información personal de manera clara, ordenada y visualmente atractiva.