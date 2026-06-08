# Musicaweb
1. Título del Proyecto
músicawebebg

3. Descripción General
¿De qué trata el proyecto?

El proyecto es un portafolio web editorial y dinámico bautizado como "ICONS", diseñado bajo el concepto de una Single Page Application (SPA). Su objetivo es explorar la identidad visual, biografía, discografía, logros y curiosidades de cinco de los artistas más influyentes del Pop, R&B alternativo y Dream Pop contemporáneo (Joji, The Weeknd, The Neighbourhood, Chase Atlantic y Lana Del Rey).

¿Qué problema resuelve o qué simula?

El proyecto simula una revista digital premium de alta fidelidad o una plataforma de streaming cultural. Resuelve la necesidad de ofrecer una experiencia de usuario fluida e inmersiva sin tiempos de carga entre secciones, empaquetando un gran volumen de información biográfica y archivos visuales de manera organizada, atractiva y responsiva en un solo lugar.

3. Tecnologías Utilizadas
¿Qué lenguajes, frameworks y herramientas fueron aplicados?

HTML5: Para la estructuración semántica de todo el contenido, las secciones individuales de los artistas y la galería de imágenes.

CSS3 (Vanilla): Para el diseño visual de vanguardia. Se utilizaron variables globales (:root) para la paleta de colores (tonos oscuros, turquesas y rojos neón), tipografías modernas integradas desde Google Fonts (Syne e Inter), Grid Layout y Flexbox para la adaptabilidad responsiva, y transiciones fluidas para los efectos hover.

JavaScript (Vanilla): Para dotar de dinamismo a la interfaz, manejando la lógica del cambio de pestañas, el comportamiento del menú y los componentes interactivos sin depender de librerías externas.

¿Se utilizaron herramientas de Inteligencia Artificial?

Sí. Para el desarrollo y optimización de este proyecto se utilizó asistencia de Inteligencia Artificial (IA) como herramienta colaborativa. La IA ayudó a la co-creación de la arquitectura del código, la unificación del sistema SPA dentro de un único archivo autónomo y la redacción del contenido biográfico de los artistas.

4. Funcionalidades
¿Cuáles son las funcionalidades implementadas en la página web?

Sistema de Navegación Ininterrumpida (SPA Dinámica): La funcionalidad dinámica principal. A través de JavaScript, la web oculta y muestra las "páginas" de los artistas en tiempo real al hacer clic en las tarjetas o en el menú superior, evitando que el navegador tenga que recargar y permitiendo que todo funcione en un solo archivo.

Menú Superior Adaptativo (Sticky Navbar): La barra de navegación se mantiene fija en la parte superior y detecta el scroll del usuario; al bajar, cambia su tamaño y opacidad para mejorar la lectura y dar un aspecto más limpio.

Botón de Retorno Global: Un botón inteligente de "Volver al Inicio" que aparece dinámicamente solo cuando el usuario está dentro de la sección de un artista y desaparece de forma automática cuando regresa a la Landing Home.

Componente de Acordeón Interactivo (Curiosidades): Un sistema desplegable en las secciones de los artistas que permite expandir o colapsar datos curiosos mediante clics, animando la altura del contenedor con JavaScript para una transición suave.

Efecto de Animación al Desplazar (Scroll Reveal): Utiliza la API de JavaScript Intersection Observer para detectar cuándo los elementos entran en la pantalla del usuario y hacerlos aparecer con un desvanecimiento hacia arriba de forma fluida.

Galería Fotográfica Híbrida y Responsiva: Un archivo visual optimizado mediante CSS Grid que reordena de forma automática las imágenes según el tamaño de la pantalla del dispositivo.

5. Instrucciones de Uso

Cómo acceder al sitio desplegado (link a Netlify).
https://musicwebebg.netlify.app/

Cómo clonar y ejecutar el proyecto localmente (si aplica).

6. Estructura del Proyecto (opcional pero recomendado)

Breve explicación de carpetas y archivos principales:
mi-proyecto-icons/
│
├── index.html
├── image_13237f.png
├── image_132643.png
├── image_132662.png
├── image_13267f.png
├── image_1326bf.png
└── image_1326a0.png

index.html (Archivo Núcleo): Es el corazón y único archivo de código del proyecto. Almacena de forma unificada las tres capas fundamentales del desarrollo web:

Estructura (HTML5): Contiene el esqueleto de la página de inicio (Landing Home), las 5 secciones individuales de los artistas, la galería de imágenes y el menú de navegación.

Estilos (CSS3): Integrados dentro de la etiqueta <style>. Define el diseño visual oscuro, las tipografías inmersivas, el diseño responsivo (Grid/Flexbox) y las transiciones.

Interactividad (JavaScript Vanilla): Ubicado dentro de la etiqueta <script> al final del archivo. Controla el enrutamiento virtual entre pestañas, los acordeones interactivos y las animaciones con el scroll.

Archivos de Imagen (.png): Colección de recursos visuales locales que alimentan la interfaz. Incluye las portadas principales de cada artista (Joji, The Weeknd, etc.) y las texturas visuales de la galería, asegurando que el contenido gráfico cargue de manera instantánea junto con la estructura.

7. Autor
Elvis Benavidez Gutiérrez cbbe.elvis.benavidez.gu@unifranz.edu.bo

