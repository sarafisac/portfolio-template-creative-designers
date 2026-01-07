# TÍTULO

Encuentra aquí el proyecto desplegado: [https://sarafisac.github.io/portfolio-template-creative-designers/]
(https://sarafisac.github.io/portfolio-template-creative-designers/)

# Introducción

Este proyecto consiste en el desarrollo de mi portfolio web personal como ilustradora y diseñadora gráfica. El objetivo principal no ha sido únicamente mostrar mis proyectos, sino construir una pieza digital coherente que refleje mi identidad visual y mi manera de entender el diseño.
El proyecto parte de una base técnica proporcionada en clase, que he ido adaptando progresivamente. A lo largo del proceso he tomado decisiones conscientes tanto a nivel visual como técnico, entendiendo el código como un sistema y no como una suma de estilos aislados.

# Enfoque y objetivos

Desde el inicio, el enfoque del proyecto ha sido crear un portfolio claro, legible y editorial, donde el contenido tuviera prioridad y la interfaz acompañase sin imponerse. A nivel técnico, uno de los objetivos ha sido entender y aplicar conceptos como tipografía fluida, variables CSS, responsive design y accesibilidad, asegurándome de que cada decisión tuviera una justificación real y no fuese simplemente estética.

# Proceso de diseño y desarrollo

El primer paso fue analizar el código base proporcionado en clase. Antes de modificarlo, me tomé el tiempo de entender la estructura de los archivos, el uso de variables CSS, la escala tipográfica con clamp() y la organización general del layout. Esto me permitió trabajar sobre una base sólida sin romper el sistema existente.
A partir de ahí, comencé a adaptar el diseño a mi propio proyecto. Uno de los aspectos más importantes fue la creación de un sistema de color flexible, capaz de funcionar tanto en fondos claros como oscuros. Para ello, definí colores base para fondo y texto y los apliqué mediante clases semánticas, lo que me permitió controlar fácilmente la legibilidad en cada sección.

En el hero y en algunas secciones clave decidí utilizar un degradado muy sutil, inspirado en referencias editoriales, para aportar profundidad sin perder limpieza visual. Este degradado está integrado dentro del sistema de variables, de forma que se mantiene coherente con el resto del diseño y puede adaptarse también al modo oscuro.

Por último, decidí inluir un favicon para personalizar del todo la web, así como para recordar y refrescar el método y la forma de hacerlo

# Tipografía y jerarquía

He trabajado con una diferenciación clara entre una tipografía serif de tipo display (Playfair Display) para el hero y los títulos de sección, y una tipografía sans-serif para el texto largo y el contenido funcional. Esta decisión busca reforzar el carácter editorial del portfolio sin comprometer la legibilidad.
Los tamaños tipográficos se han mantenido a lo largo del proyecto mediante una escala fluida con clamp(), lo que permite que el texto se adapte de forma natural a distintos tamaños de pantalla. De este modo, he podido cambiar la personalidad de los títulos sin alterar la estructura ni el equilibrio general del diseño.
También se ha cuidado especialmente la jerarquía de encabezados, utilizando un solo h1 por página y manteniendo una estructura lógica que sea comprensible tanto visualmente como para tecnologías de asistencia.

# Layout y diseño responsive

El layout del portfolio está planteado desde un enfoque mobile-first, asegurando que el contenido sea usable y legible en pantallas pequeñas antes de adaptarse a tamaños mayores. Para ello he trabajado con CSS Grid y Flexbox, apoyándome en un sistema de espaciado fluido basado en variables CSS, lo que permite mantener una jerarquía visual coherente en todos los tamaños de pantalla.
Durante el desarrollo he comprobado el comportamiento del diseño en distintos puntos de ruptura, detectando que los principales inconvenientes aparecían en el apartado del hero. Esta sección estaba inicialmente pensada con una composición editorial orientada a escritorio, lo que en móvil generaba exceso de espacio, una imagen desproporcionada y una lectura menos fluida. Para solucionarlo, decidí no modificar la estructura base del layout de escritorio y aplicar ajustes específicos solo en móvil mediante media queries, reduciendo márgenes, reorganizando el contenido en una sola columna y compactando los elementos sin perder jerarquía.
La imagen del hero se ajustó siguiendo esta misma lógica. En lugar de mantener alturas fijas dependientes del viewport, se controló su proporción mediante object-fit: cover y valores adaptativos, permitiendo que la imagen crezca correctamente en móvil sin deformarse y mantenga un tratamiento más contenido en escritorio.
Algo similar ocurrió con la navegación al implementar el menú hamburguesa. El problema inicial vino de intentar aplicar el comportamiento mobile directamente sobre las clases base del navegador, lo que provocó que el layout de escritorio heredara estilos pensados para móvil y se desajustara. La solución fue aislar completamente estos comportamientos responsive dentro de media queries y clases específicas, manteniendo el layout desktop como estado por defecto.
Como reflexión final, este proyecto me ha ayudado a entender la importancia de separar claramente estilos base y comportamientos responsive, así como a afrontar el diseño adaptable no como una simple reducción del formato de escritorio, sino como una experiencia pensada específicamente para cada contexto. Los errores durante el proceso han sido clave para comprender mejor cómo se relacionan estructura, tipografía y comportamiento en un proyecto web real.

# Interacción, animación y modo oscuro

Las animaciones del proyecto están pensadas como un apoyo al contenido, no como un elemento protagonista. Se han utilizado transiciones y animaciones suaves basadas en transform y opacity, manteniendo un lenguaje común entre el hero, la página 404 y otros elementos interactivos.
Además, se ha tenido en cuenta la preferencia del usuario mediante prefers-reduced-motion, desactivando animaciones cuando es necesario para garantizar una experiencia accesible.
El modo oscuro se ha implementado como parte del sistema de diseño, redefiniendo variables CSS según el tema activo. El cambio entre modo claro y oscuro incluye una transición suave para evitar cambios bruscos y mantener una experiencia agradable. El botón de cambio de modo está diseñado con un enfoque distinto, ya que usa un emoji en lugar de texto, para diferenciar su función del resto en la barra de navegación, ocupando así menos espacio.

# Accesibilidad y buenas prácticas

Desde el inicio del proyecto he intentado integrar la accesibilidad como parte del diseño, no como un añadido final. Se ha trabajado con HTML semántico, contraste de color suficiente, estados de foco visibles, navegación por teclado y textos alternativos en imágenes.
También se ha prestado atención a pequeños detalles como el skip link, la gestión del foco y el respeto a las preferencias de movimiento del usuario. El objetivo ha sido que el portfolio sea usable y comprensible para el mayor número de personas posible.

# SEO y presentación del proyecto

Se ha completado el <head> del documento con los metadatos necesarios para una correcta presentación del proyecto, incluyendo título, descripción, favicon, meta viewport y etiquetas Open Graph. Esto asegura que el portfolio esté preparado tanto para buscadores como para su difusión en redes sociales.
Además, se ha creado una página 404 personalizada que mantiene la coherencia visual del proyecto y guía al usuario de forma clara incluso cuando se produce un error de navegación.

# Conclusión

Este proyecto me ha permitido entender el desarrollo web como un proceso integral, en el que diseño, código y experiencia de usuario están estrechamente relacionados. A lo largo del trabajo he aprendido a tomar decisiones más conscientes, a justificar cada cambio y a pensar el código como un sistema escalable y coherente.
Más allá del resultado final, el valor principal del proyecto ha sido el proceso y el aprendizaje adquirido, tanto a nivel técnico como conceptual.
