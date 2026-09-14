# Prompt para Claude Design — Landing Page "Alma de Poeta"

Diseña una landing page de una sola página para **Alma de Poeta**, un café + librería + restaurante en Lima, Perú, con concepto "un espacio de familia, amigos y libros". El sitio debe sentirse hecho a mano y con identidad propia, nunca como una plantilla genérica de restaurante.

## 1. Contexto del negocio

- Nombre: Alma de Poeta
- Concepto: café, librería y restaurante en un mismo espacio, ambiente familiar y literario
- Dirección: Jr. Arístides del Carpio Muñoz 1679, Urb. Los Cipreses, Cercado de Lima
- Mapa: https://www.google.com/maps/place/Alma+de+Poeta+café+%26+libros/@-12.0571421,-77.0804995,17z/data=!3m1!4b1!4m6!3m5!1s0x9105c9bfa6baf231:0x847c43fdd0a41bed!8m2!3d-12.0571421!4d-77.0779192!16s%2Fg%2F11ty0n6j30
- Horario: lunes a miércoles 5:00pm–10:00pm, jueves a sábado 5:00pm–11:00pm, domingo cerrado
- Redes sociales (mismo usuario en las tres): Instagram, TikTok y Facebook → @almadepoetaperu

## 2. Dirección de diseño

El cliente eligió una combinación de dos estilos:

- **Cálido y literario**: tonos tierra, tipografía con carácter, ambiente de café de libros, acogedor
- **Rústico y bohemio**: texturas de madera, colores tierra, sensación hecha a mano

Fusiona ambos: papel envejecido, textura de madera, calidez tipo librería antigua, nada de líneas frías ni minimalismo corporativo. El logo del negocio es un line-art del local en trazo fino con el nombre en script elegante — usa ese lenguaje gráfico (ilustraciones lineales, trazo de pluma) como hilo visual del sitio.

## 3. Paleta de colores con selector interactivo

El cliente tiene tres variantes de logo y quiere poder alternarlas en la landing:

1. **Clásica**: fondo blanco/crema, logo y tipografía en negro/carbón
2. **Verde intenso + dorado**: fondo verde (más intenso y saturado que un verde bosque estándar — el cliente pidió explícitamente que el verde sea más fuerte), texto y acentos en dorado/mostaza
3. **Dorado + verde**: fondo dorado/mostaza, texto y acentos en verde

Agrega un botón de acción visible en la landing (ícono de paleta o de pluma, ubicado en el header o como botón flotante) que permita alternar entre estas tres paletas en tiempo real. El cambio debe aplicarse con una transición suave tipo crossfade (400–600ms, ease-in-out) a fondo, tipografía, botones y acentos de forma coherente en toda la página, no solo en un bloque.

## 4. Tipografía

- **Carta (menú)**: conserva el espíritu caligráfico/script del menú físico original, pero mejora la legibilidad. Usa la fuente script solo para los nombres de los platos (impacto visual y personalidad), y una serif limpia y muy legible para descripciones y precios. El menú original es difícil de leer por exceso de cursiva — corrige eso sin perder el carácter.
- **Resto del sitio**: queda a tu criterio de diseño, pero debe ser coherente con la dirección cálido + rústico + literario elegida arriba — piensa en un serif editorial con carácter para títulos de sección, combinado con una sans-serif cálida y legible para cuerpo de texto y navegación.

## 5. Estructura de secciones

1. Hero / portada con el logo y una frase de bienvenida ("un espacio de familia, amigos y libros")
2. Sobre nosotros: el concepto café + librería + restaurante, ambiente familiar
3. Ubicación y horario: mapa embebido (usar el link de Maps de arriba) y el horario destacado de forma clara
4. Carta: preview atractivo con botón para abrir la vista completa (ver sección 6)
5. Redes sociales: íconos enlazando a @almadepoetaperu en Instagram, TikTok y Facebook
6. Contacto: botón de WhatsApp visible

## 6. La carta interactiva (la parte más importante)

En la landing, muestra un preview de la carta como una tarjeta con textura de papel envejecido (como el menú físico real), con 2-3 platos destacados y un ícono de libro o menú invitando a "Ver la carta completa".

Al hacer click:

- La carta se abre en una vista ampliada tipo overlay/modal
- El fondo de la página se difumina (backdrop-filter: blur) y se oscurece levemente
- La carta aparece con una animación de entrada suave (fade + scale o slide-up), sin saltos bruscos
- Debe mostrar la carta completa organizada por categorías, con scroll interno donde haga falta
- Al hacer click en cualquier parte del área difuminada fuera de la carta, esta se cierra con la animación inversa
- Junto a la carta (por ejemplo al lado del título o en una esquina) agrega una ilustración de una **pluma de tinta** (pluma estilográfica con un pequeño trazo o gota de tinta) con su propia animación sutil — un leve efecto de "escritura" o un brillo de tinta — para reforzar la personalidad literaria de la marca

Para el contenido de la carta: usa el PDF adjunto (Carta_Principal.pdf) como fuente completa y exacta — nombres de platos, descripciones y precios tal cual aparecen ahí, sin resumir ni inventar. Las categorías a organizar son: Entradas, Ensaladas, Sánguches, Hamburguesas, Tacos y Platos a la Carta, Postres, Bebidas Frías (jugos, milkshakes, smoothies), Té e Infusiones, Cafés (calientes y fríos) y Desayunos.

## 7. Animaciones y navegación

- Scroll suave entre secciones (smooth scroll)
- Header/navegación fija que cambia de fondo sutilmente al hacer scroll
- Micro-interacciones en botones y tarjetas al pasar el cursor, con transiciones suaves, sin ser recargadas
- Entrada de secciones al hacer scroll con fade-in o slide-in sutil (nada exagerado)
- Timing de animaciones entre 300–600ms con curvas ease-in-out, coherente con una identidad elegante y no genérica

## 8. Responsive

El sitio debe verse impecable en celular, ya que la mayoría de clientes llegarán buscando el local desde Google en su teléfono. Prioriza la experiencia móvil en el diseño, no solo como adaptación de la versión de escritorio.

## 9. Elementos técnicos adicionales

- Botón de WhatsApp visible o flotante para contacto directo
- Sección de ubicación con el link de Maps funcionando
- Íconos de redes sociales enlazando a @almadepoetaperu
- Todo el sitio debe sentirse como una sola identidad coherente, no como secciones desconectadas
