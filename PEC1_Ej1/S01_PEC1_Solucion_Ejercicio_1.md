## La aparición de HTML5/CSS3/JS ha supuesto el nacimiento del desarrollo front-end moderno. (0.75 puntos)

• ¿Cuál es la ventaja del uso de etiquetas semánticas? 

- En HTML5, las etiquetas semánticas son elementos específicos diseñados para proporcionar un significado semántico claro al contenido de una página web. Estas etiquetas ayudan a los desarrolladores a estructurar el contenido de manera más significativa para los motores de búsqueda y los usuarios, mejorando la accesibilidad y la usabilidad. Algunas de las etiquetas semánticas más comunes en HTML5 incluyen:

1. <header>: Define una sección de encabezado para la introducción de un contenido o una sección de una página web.
2. <footer>: Define una sección de pie de página para la conclusión de un contenido o una sección de una página web.
3. <nav>: Define una sección de navegación que contiene enlaces de navegación principales.
4. <article>: Define un contenido independiente y autónomo, como una publicación de blog, un artículo de noticias o un comentario.
5. <section>: Define una sección temática dentro de un documento, como capítulos, encabezados o grupos de contenido relacionado.
6. <aside>: Define un contenido relacionado pero no esencial, como una barra lateral, que complementa el contenido principal.
7. <main>: Define el contenido principal de un documento, excluyendo encabezados, pies de página, barras laterales y otras secciones que no son esenciales.
8. <figure> y <figcaption>: <figure> se utiliza para representar contenido independiente, como imágenes, gráficos o diagramas, mientras que <figcaption> proporciona una descripción o leyenda asociada.

El uso de etiquetas semánticas en HTML5 proporciona varias ventajas importantes:

- Mejora de la accesibilidad: Las etiquetas semánticas ayudan a los lectores de pantalla y otros dispositivos de asistencia a comprender la estructura y el significado del contenido de una página web. Esto mejora la accesibilidad para personas con discapacidades visuales u otras necesidades especiales.

- Mejora de la indexación y SEO: Los motores de búsqueda pueden interpretar mejor el contenido de una página web cuando se utiliza una estructura semántica clara. Esto puede resultar en una mejor clasificación en los resultados de búsqueda y una mayor visibilidad en línea.

- Facilita el mantenimiento y la comprensión del código: El uso de etiquetas semánticas hace que el código HTML sea más legible y comprensible para los desarrolladores y otros colaboradores que trabajan en el proyecto. Esto facilita el mantenimiento y la actualización del sitio web en el futuro.

En resumen, el uso de etiquetas semánticas en HTML5 mejora la accesibilidad, la indexación en motores de búsqueda, la legibilidad del código, la experiencia del usuario y la compatibilidad con futuras tecnologías, lo que resulta en un sitio web más efectivo y fácil de mantener.


• Cita al menos 3 APIs HTML5 y explica brevemente su funcionalidad.

Una **API** (Interfaz de Programación de Aplicaciones) es un conjunto de reglas y protocolos que permite a diferentes aplicaciones y sistemas comunicarse entre sí. En términos simples, una API define cómo interactuar con un sistema o servicio específico, proporcionando una interfaz estandarizada que permite a los desarrolladores acceder y manipular los recursos y funcionalidades de ese sistema de manera programática.

**HTML5**, como estándar de marcado para páginas web, no proporciona APIs específicas, ya que se centra en la estructura y presentación del contenido web. Sin embargo, HTML5 se complementa con otras tecnologías, como JavaScript y las APIs del navegador, que permiten la interacción dinámica y avanzada con el contenido web. A continuación, menciono algunas APIs de navegador que son comúnmente utilizadas junto con HTML5:

1. API de Geolocalización: Permite a los desarrolladores acceder a la ubicación del dispositivo del usuario a través del navegador web. Los desarrolladores pueden utilizar esta información para proporcionar contenido y servicios personalizados basados en la ubicación del usuario, como mostrar mapas locales, encontrar servicios cercanos o personalizar la experiencia de usuario según la región.

2. API de Canvas: Proporciona un lienzo gráfico en el navegador para dibujar gráficos, animaciones y otros elementos visuales de manera dinámica mediante JavaScript. Esta API es útil para crear juegos en línea, visualizaciones de datos interactivas, aplicaciones de dibujo en línea y otras experiencias visuales sofisticadas directamente dentro del navegador, sin necesidad de complementos externos.

3. API de Web Storage: Ofrece una forma de almacenar datos localmente en el navegador del usuario, permitiendo el almacenamiento persistente o de sesión. Se compone de dos mecanismos principales: **localStorage** y **sessionStorage**. El localStorage permite almacenar datos de manera persistente en el navegador, lo que significa que los datos permanecen incluso después de cerrar y volver a abrir el navegador, mientras que el sessionStorage almacena datos de manera temporal durante la sesión de navegación actual. Esta API es útil para almacenar información como preferencias de usuario, datos de inicio de sesión, carritos de compra en línea y otra información relevante para la aplicación web.

• Cita qué opción ofrece CSS3 para conseguir que se apliquen diferentes estilos CSS sobre el mismo elemento en su visualización en diferentes dispositivos (diferentes tamaños de pantalla).

CSS3 ofrece la funcionalidad de Media Queries para lograr que se apliquen diferentes estilos CSS sobre el mismo elemento en su visualización en diferentes dispositivos, especialmente en función del tamaño de pantalla.

Las **Media Queries** permiten especificar condiciones basadas en características del dispositivo, como el ancho de la pantalla, la orientación, la resolución, entre otros, y aplicar estilos CSS específicos en función de esas condiciones.

Por ejemplo, para aplicar diferentes estilos CSS a un elemento con el id "myElement" dependiendo del ancho de la pantalla, puedes usar una Media Query de la siguiente manera:

css
@media screen and (max-width: 768px) {
    #myElement {
        /* Estilos para pantallas con un ancho máximo de 768px */
    }
}

@media screen and (min-width: 769px) {
    #myElement {
        /* Estilos para pantallas con un ancho mínimo de 769px */
    }
}

En este ejemplo, los estilos definidos dentro de la primera Media Query se aplicarán cuando el ancho de la pantalla sea de 768 píxeles o menos, mientras que los estilos dentro de la segunda Media Query se aplicarán cuando el ancho de la pantalla sea de 769 píxeles o más. De esta manera, se pueden adaptar los estilos del mismo elemento según el tamaño de pantalla del dispositivo en el que se está visualizando la página web.


• Cita al menos 4 de las características principales de TypeScript (importante
superset de JavaScript que trataremos en el siguiente capítulo).


2. El lenguaje CSS es muy rígido, poco práctico y ordenado a la hora de programar. Para evitar este problema se han creado los preprocesadores CSS, que ofrecen evidentes
ventajas (0.5 puntos)
• Cita al menos 2 de estos preprocesadores.
• Cita al menos 4 ventajas que ofrecen estos preprocesadores.
• Explica brevemente en qué consisten los sourcemaps.
• Explica qué es un transpilador.

3. El flujo de trabajo profesional en front-end hace indispensable el uso de herramientas
como controles de versiones y herramientas de gestión de módulos (0.75 puntos).
• Cita al menos dos sistemas de control de versiones y dos herramientas de
gestión de módulos.
• Cita y explica al menos 3 comandos de Git.
• Cita y explica brevemente las características más definitorias de WebPack.
