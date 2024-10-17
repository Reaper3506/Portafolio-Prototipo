# Portafolio
Descripción breve del proyecto

Este proyecto consiste en la creación de un portafolio profesional en línea que muestra mi experiencia, habilidades y proyectos destacados en el desarrollo de videojuegos y tecnología. El sitio web está compuesto por varias páginas interconectadas que proporcionan información detallada sobre mí, mis proyectos, mi formación académica y formas de contacto. El objetivo principal es presentar de manera atractiva y funcional mi perfil profesional a potenciales empleadores, colaboradores y visitantes interesados.

Tecnologías utilizadas
HTML5 Semántico: Utilicé etiquetas semánticas como header, nav, section, article, footer, entre otras, para estructurar el contenido de manera lógica y mejorar la accesibilidad y el SEO del sitio.
CSS3: Apliqué estilos personalizados para mejorar la apariencia y usabilidad del sitio. Usé selectores, flexbox, animaciones y transiciones para crear una experiencia de usuario agradable.
JavaScript: Implementé funcionalidades interactivas como el efecto de máquina de escribir, el reloj digital en tiempo real, el interruptor de modo oscuro/claro, y el contador de visitas utilizando localStorage.
Font Awesome: Integré iconos para enriquecer la interfaz de usuario, especialmente en los enlaces de contacto y redes sociales.
Google Fonts: Utilicé fuentes personalizadas para mejorar la legibilidad y estética del texto.

Características implementadas en los HTML
Página de Inicio (index.html):
Introducción Personal: Una breve presentación sobre mí y mis intereses profesionales.
Efecto de Máquina de Escribir: El título principal muestra una animación que simula el tecleo de una máquina de escribir.
Reloj Digital: Un reloj que se actualiza cada segundo mostrando la hora actual.
Interruptor de Modo Oscuro/Claro: Permite al usuario cambiar entre temas, mejorando la accesibilidad visual.
Menú de Navegación: Enlaces a las diferentes secciones del sitio.

Página de Proyectos (projects.html):
Listado de Proyectos: Presenta una lista de proyectos en los que he trabajado, incluyendo el rol desempeñado en cada uno.
Imágenes Desplegables: Al hacer clic en el nombre de un proyecto, se muestra u oculta una imagen representativa del mismo.
Modo Oscuro/Claro: También incluye el interruptor para cambiar el tema.

Página "Sobre Mí" (about.html):
Biografía Profesional: Un resumen detallado de mi formación, experiencia laboral, habilidades y logros.
Habilidades Técnicas: Sección con barras de progreso que indican mi nivel de competencia en diferentes tecnologías y herramientas.
Formación Académica y Experiencia Relevante: Información sobre mis estudios y participaciones en eventos como gamejams.

Página de Contacto (contact.html):
Formulario de Contacto: Un formulario sencillo donde los visitantes pueden ingresar su nombre, correo electrónico y mensaje.
Enlaces a Perfiles Profesionales: Iconos y enlaces a mis perfiles de LinkedIn, GitHub y dirección de correo electrónico.

Desafíos enfrentados y cómo los superé
Problemas con la Visualización de Imágenes en GitHub Pages:

Desafío: Las imágenes de los proyectos no se mostraban en GitHub Pages, aunque funcionaban localmente.
Solución: Descubrí que GitHub Pages es sensible a las mayúsculas y minúsculas en los nombres de archivos y rutas. Verifiqué que los nombres de los archivos de imagen y sus referencias en el código coincidieran exactamente, respetando las mayúsculas y minúsculas.
Implementación del Modo Oscuro/Claro en Múltiples Páginas:

Desafío: El interruptor de modo oscuro/claro funcionaba en una sola página y no mantenía el estado al navegar entre páginas.
Solución: Añadí el mismo código JavaScript y el interruptor en todas las páginas, y utilicé localStorage para guardar la preferencia del usuario. Así, el modo seleccionado se mantiene consistente al navegar por el sitio.
Efecto de Máquina de Escribir Duplicado y Desalineado:

Desafío: El efecto de máquina de escribir en el título principal mostraba el texto dos veces y no estaba centrado.
Solución: Eliminé la animación CSS que causaba la duplicación y centré el texto usando CSS. Solo mantuve el efecto implementado con JavaScript para mayor control y evitar conflictos.
