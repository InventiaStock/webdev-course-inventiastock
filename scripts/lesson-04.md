# Lección 4: Introducción a CSS y estilo simple

**Duración:** ~11 minutos · **Herramienta:** JSFiddle · **Práctica:** `starter-files/lesson-04`

**Objetivo:** que el estudiante escriba reglas de CSS, use selectores de etiqueta y de clase, cambie colores y letra, centre texto y use bordes y espacios.

> **Pantalla** es lo que se muestra y se hace; **Voz** es el texto que se pega en el generador de voz. Los valores de color y las propiedades se escriben **en pantalla**; la voz no los deletrea. En JSFiddle el CSS se escribe en la caja de CSS; en los archivos del repo está en `styles.css`.

---

## Escena 1 · 0:00–0:19 · Repaso

**Pantalla:** El fiddle con la página de la lección 3 sin estilo (cajas HTML y CSS visibles, CSS vacío).

**Voz:**
> En la lección anterior hiciste que tu página tuviera listas, imágenes y enlaces. Pero se ve muy simple, ¿verdad? Hoy vas a darle estilo con ce ese ese.

---

## Escena 2 · 0:19–1:24 · La regla de CSS

**Pantalla:** Tarjeta con `h1 { color: blue; }` y cuatro recuadros de colores: «Selector», «Propiedad», «Valor», «Punto y coma». Después escribir esa regla en la caja de CSS y mostrar cómo cambia el color del título.

**Voz:**
> El ce ese ese se escribe con reglas. Una regla tiene cuatro partes. Primero el selector, que dice a qué elemento le vamos a dar estilo. Después, unas llaves. Dentro de las llaves va la propiedad, que dice qué queremos cambiar, por ejemplo el color. Luego dos puntos, y el valor, que dice cómo lo queremos. Y al final, un punto y coma. Escribamos una: hache uno, llaves, color, dos puntos, blu, punto y coma. Blu se escribe blue y significa azul en inglés. Mira cómo el título cambió de color. Ese punto y coma es muy importante: si lo olvidas, la regla puede dejar de funcionar.

---

## Escena 3 · 1:24–1:48 · Leer una regla en voz alta

**Pantalla:** Mostrar la regla `h1 { color: blue; }` y debajo, como subtítulo, la frase «A todos los h1, ponles el color azul».

**Voz:**
> Una forma fácil de entender una regla es leerla como una frase. Esta regla dice: a todos los títulos hache uno, ponles el color azul. Así de simple. Selector, propiedad y valor: quién, qué y cómo.

---

## Escena 4 · 1:48–2:51 · Dónde va el CSS

**Pantalla:** Mostrar la caja de CSS del fiddle. Después, una tarjeta con dos archivos: `index.html` y `styles.css`, y la línea `<link rel="stylesheet" href="styles.css">` dentro de la zona `head`. Texto en pantalla: «En el editor en línea: caja de CSS» y «En un sitio real: archivo styles.css».

**Voz:**
> ¿Y dónde se escribe el ce ese ese? En este editor en línea, en la caja que dice ce ese ese. Ahí escribes tus reglas y el navegador las aplica automáticamente. En un sitio web real, el ce ese ese se guarda en un archivo aparte, por ejemplo styles punto ce ese ese. Y para conectarlo con la página, dentro del head se escribe una etiqueta llamada link. Con ella le decimos al navegador: usa este archivo de estilos. En el repositorio de este curso verás los dos archivos separados: uno para el hache te eme ele y otro para el ce ese ese.

---

## Escena 5 · 2:51–3:48 · Selectores: etiqueta y clase

**Pantalla:** Escribir `h2 { color: darkslateblue; }` y mostrar que todos los títulos `h2` cambian. Después, en el HTML, agregar `class="destacado"` al segundo párrafo. En el CSS, escribir `.destacado { background-color: lemonchiffon; }` y mostrar que solo ese párrafo cambia. Marcar con un recuadro el punto delante de `destacado`.

**Voz:**
> El selector más simple es el nombre de la etiqueta. Si escribo hache dos, el estilo se aplica a todos los títulos hache dos. Pero, ¿y si queremos darle estilo solo a un párrafo especial? Para eso existen las clases. Primero, en el hache te eme ele, le agregamos al párrafo el atributo class igual a destacado. El nombre lo elegimos nosotros. Después, en el ce ese ese, escribimos un punto antes del nombre. Ese punto significa: busca los elementos con esa clase. Y ahora cualquier elemento con la clase destacado recibirá ese estilo.

---

## Escena 6 · 3:48–5:06 · Colores y letras

**Pantalla:** Escribir la regla `body` con `font-family: Arial, sans-serif;`, `background-color: aliceblue;`, `color: darkslategray;` y `padding: 20px;` (este último se explica en la escena 6; puede escribirse allí). Luego `p { font-size: 18px; }`. Texto en pantalla con cada propiedad y su significado: «color = color del texto», «background-color = color de fondo», «font-family = tipo de letra», «font-size = tamaño del texto». Mostrar cómo cambia toda la página.

**Voz:**
> Veamos cuatro propiedades muy útiles. Color cambia el color del texto. Background color cambia el color de fondo. Font family cambia el tipo de letra; usaremos Arial, que se ve igual en todos los navegadores. Y font size cambia el tamaño del texto. Para que afecten a toda la página, las escribimos en la regla del body. Le pongo la letra Arial, un fondo celeste muy claro y un texto gris oscuro. Y mira cómo cambia toda la página. Después, en los párrafos, subo un poco el tamaño de la letra. Los colores se pueden escribir con su nombre en inglés, como blue, green u orange (que se leen blu, grin y oranch), o con un código que empieza con un numeral. Por ahora, puedes elegir los colores que quieras.

---

## Escena 7 · 5:06–5:52 · Probar y experimentar

**Pantalla:** Cambiar varias veces el valor de una propiedad (por ejemplo, tres colores distintos para el título) y mostrar el resultado cada vez. Texto en pantalla: «Cambia un valor y mira qué pasa».

**Voz:**
> La mejor forma de aprender ce ese ese es probando. Cambia un valor, mira el resultado, cambia otro. Si no te gusta, deshaces y listo. No puedes romper nada. Los navegadores conocen más de ciento cuarenta colores con nombre en inglés, y en internet hay páginas de referencia donde puedes verlos todos. Si quieres un color exacto, puedes usar un código que empieza con un numeral, pero con los nombres ya puedes hacer mucho.

---

## Escena 8 · 5:52–6:58 · Estilo simple: centrar, bordes y espacios

**Pantalla:** Escribir `h1 { color: royalblue; text-align: center; }` y mostrar el título centrado. Después `h2 { border-bottom: 2px solid darkslateblue; }`. Mostrar un dibujo simple de una caja con las capas «Contenido», «Padding», «Borde» y «Margin». Completar `.destacado` con `border: 2px solid orange; padding: 10px; margin: 20px 0;` y mostrar cómo el párrafo parece una tarjeta. Agregar `body { padding: 20px; }` si no se escribió antes.

**Voz:**
> Ahora vamos con tres ideas para dar forma a tus elementos. Primero, centrar el texto: text align, center. Lo aplicamos al título. Segundo, los bordes: border, seguido del grosor, el tipo de línea y el color. Por ejemplo, dos píxeles, línea sólida y color naranja. Tercero, el espacio. Imagina que cada elemento es una caja. Padding es el espacio de adentro, entre el texto y el borde. Margin es el espacio de afuera, entre esta caja y las demás. Probemos con la clase destacado: le ponemos un borde naranja, diez píxeles de padding, y veinte píxeles de margin arriba y abajo. Mira cómo ahora el párrafo parece una tarjeta.

---

## Escena 9 · 6:58–7:45 · Un ejemplo completo

**Pantalla:** Mostrar la página completa con todo el estilo aplicado y recorrerla de arriba abajo con recuadros: título centrado, títulos con línea, párrafo destacado, imagen con borde.

**Voz:**
> Miremos cómo queda la página con todo junto. El título está centrado y en azul. Cada título hache dos tiene una línea debajo. El párrafo destacado parece una tarjeta con su borde y su espacio. Y la imagen tiene un borde azul. Todo esto con unas pocas reglas. Fíjate que no cambiamos nada del hache te eme ele, salvo la clase destacado. Esa es la gran idea de ce ese ese: separar el contenido del estilo.

---

## Escena 10 · 7:45–8:31 · Errores típicos de CSS

**Pantalla:** Mostrar tres ejemplos con error y la corrección: falta el punto y coma, falta el punto antes del nombre de la clase, propiedad mal escrita (`colour`). Texto en pantalla: «Los navegadores no adivinan».

**Voz:**
> Antes de terminar, tres errores típicos de ce ese ese. Uno: olvidar el punto y coma al final de una línea. Dos: olvidar el punto antes del nombre de una clase, y entonces el navegador la busca como si fuera una etiqueta. Y tres: escribir mal el nombre de una propiedad. Los navegadores solo entienden las palabras exactas, y la propiedad se escribe color, no colour. Si algo no funciona, revisa estas tres cosas primero.

---

## Escena 11 · 8:31–10:34 · Práctica

**Pantalla:** Aviso grande «⏸️ Pausa el video y practica». Texto en pantalla: «1. Cambia el color del título», «2. Cambia el fondo de la página», «3. Agrega la clase destacado a un párrafo y dale borde». Dejar 90 segundos con el fiddle abierto y sin voz.

**Voz:**
> Tu turno. Abre el link de la descripción. Tienes la página de la lección anterior, sin estilo. Cambia el color del título, el fondo de la página y el tipo de letra. Después agrega la clase destacado a un párrafo y dale un borde y un espacio. Pausa el video y practica.

*(Silencio de 90 segundos.)*

---

## Escena 12 · 10:34–11:05 · Cierre

**Pantalla:** Tarjeta «Lo que aprendiste hoy»: «Una regla = selector + propiedad + valor», «Selectores de etiqueta y de clase», «color, fondo, letra, centrar, borde y espacios». Después, «Siguiente: Lección 5, Crear una página web sencilla».

**Voz:**
> Lo que aprendiste hoy: una regla de ce ese ese tiene un selector, una propiedad y un valor. Puedes elegir elementos por su etiqueta o por su clase, y cambiar colores, letras, bordes y espacios. En la próxima lección juntaremos todo para crear una página de perfil. ¡Hasta pronto!