Parte 2: Analiza una página web existente
Página analizada: Ejemplo: Wikipedia (www.wikipedia.org)
1. Elementos HTML reconocidos
•	<header>: Contiene el logo y la barra de búsqueda.
•	<nav>: Menú superior con enlaces como "Portada", "Artículos", "Discusión".
•	<main>: Contiene el contenido principal (artículos o destacados del día).
•	<div>: Usado ampliamente para agrupar secciones (ej: contenedores de texto, imágenes).
•	<img>: Para mostrar imágenes (como el logo o ilustraciones en artículos).
•	<footer>: Pie de página con enlaces a políticas, información legal, etc.
•	<a>: Enlaces a otras páginas o secciones.
•	<ul>/<li>: Listas (ej: menús desplegables o enlaces en el footer).
•	<span>: Para estilizar fragmentos de texto (ej: palabras resaltadas).
2. Estructura de la página
1.	Encabezado (<header> + <nav>):
o	Logo y barra de búsqueda centrada.
o	Menú horizontal con categorías principales.
2.	Contenido principal (<main> + <div>):
o	Sección destacada con un artículo o imagen prominente.
o	Columnas o tarjetas con enlaces a contenidos secundarios.
3.	Barra lateral (opcional):
o	En algunos sitios, hay un <aside> con menús adicionales (ej: "Otros proyectos").
4.	Pie de página (<footer>):
o	Enlaces legales, redes sociales y copyright.
________________________________________
Observaciones adicionales
•	Uso de clases y IDs: Las etiquetas suelen tener atributos como class="nombre-clase" para aplicar estilos CSS.
•	Jerarquía: El HTML está anidado (ej: <div> dentro de <section> dentro de <main>).
•	Responsive: Elementos como <meta name="viewport"> indican que la página está diseñada para móviles.
Parte 3: Investigación
1. YouTube
🔹 Elementos HTML reconocibles:
•	<header>: Barra superior con logo, barra de búsqueda e iconos de usuario.
•	<nav>: Menú lateral con categorías (Inicio, Explorar, Suscripciones, etc.).
•	<main>: Contenedor principal con vídeos recomendados.
•	<section> o <article>: Cada vídeo mostrado como una tarjeta.
•	<iframe>: Para incrustar los vídeos.
•	<footer>: Enlaces a políticas, configuración y copyright.
🔹 Organización de la información:
•	Jerárquica y centrada en contenido multimedia.
o	Barra lateral fija para navegación.
o	Contenido principal en cuadrícula de vídeos (responsive con CSS Grid/Flexbox).
o	Barra superior para búsqueda y acciones del usuario.
________________________________________
2. Wikipedia
🔹 Elementos HTML reconocibles:
•	<header>: Logo y barra de búsqueda.
•	<nav>: Menú lateral con herramientas y enlaces a portales.
•	<main>: Artículo principal con <h1>, <p>, <ul>, y <table>.
•	<aside>: Sección "En otros idiomas" o "Artículos relacionados".
•	<footer>: Información legal y enlaces a proyectos hermanos.
🔹 Organización de la información:
•	Estructura lineal y textual, enfocada en lectura.
o	Menú lateral con accesos rápidos.
o	Artículo organizado en secciones (<h2>, <h3>).
o	Enlaces internos (hipertexto) para navegación contextual.
________________________________________
3. Twitter (X)
🔹 Elementos HTML reconocibles:
•	<header>: Logo y botones de navegación (Inicio, Explorar, Notificaciones).
•	<main>: Timeline central con tweets (usando <article> para cada uno).
•	<aside>: Barra lateral con tendencias y sugerencias.
•	<form>: Para publicar nuevos tweets (textarea + botón).
•	<footer>: Enlaces a términos y políticas.
🔹 Organización de la información:
•	Flujo continuo (feed) con elementos interactivos.
o	Tres columnas: navegación (izq), contenido central (tweets), y widgets (derecha).
o	Énfasis en interacción (likes, retweets) mediante botones con eventos JS.
