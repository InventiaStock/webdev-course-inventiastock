# Lección 6: Errores comunes y próximos pasos

**Duración:** ~10 minutos · **Herramienta:** JSFiddle · **Práctica:** `starter-files/lesson-06` (página con errores)

**Objetivo:** que el estudiante reconozca cinco errores típicos, aprenda a buscarlos, use el validador y sepa cómo seguir aprendiendo.

> **Pantalla** es lo que se muestra y se hace; **Voz** es el texto que se pega en el generador de voz. El fiddle `starter-files/lesson-06` tiene los cinco errores; `completed-examples/lesson-06` es la versión corregida. Los dos validadores del W3C (HTML y CSS) se muestran con el código completo de `starter-files/lesson-06`.

---

## Escena 1 · Introducción

**Pantalla:** Tarjeta «Lección 6: Errores comunes y próximos pasos». Después, el fiddle con la página con errores.

**Voz:**
> Ya creaste tu primera página. Ahora vamos a ver los errores que casi todas las personas cometen al empezar, y cómo encontrarlos rápido.

---

## Escena 2 · Los errores son normales

**Pantalla:** Texto en pantalla: «Todo el mundo se equivoca al empezar». Mostrar un código con varios errores y una flecha que dice «Es parte del proceso».

**Voz:**
> Primero, algo importante: equivocarse es parte de aprender. Las personas que programan hace muchos años también cometen errores todos los días. La diferencia es que saben buscarlos rápido. Eso es lo que vas a aprender hoy.

---

## Escena 3 · Cinco errores comunes

**Pantalla:** Mostrar la página con errores en el fiddle. Para cada error: primero el síntoma en el resultado (recuadro rojo), luego la línea del código que lo causa (recuadro) y por último la corrección. Antes de cada error, una pausa corta «Pausa y adivina» (la voz plantea el síntoma y se deja 10 s en silencio). Texto en pantalla con el número y el nombre de cada error: «Error 1: etiqueta sin cerrar», «Error 2: falta un punto y coma», «Error 3: imagen sin alt», «Error 4: ruta equivocada», «Error 5: nombre mal escrito».

**Voz:**
> **[Pausa y adivina 1]** Empecemos con un reto. Mira la página: algo se ve raro en la lista de hobbies. Pausa el video y piensa qué puede estar pasando. *(10 segundos de silencio con el resultado fijo en pantalla.)*
>
> Error número uno: una etiqueta sin cerrar. Mira esta lista de hobbies: se ve enorme y en negrita, como si fuera un título. Revisamos el código y vemos que el hache dos de Mis hobbies no tiene su etiqueta de cierre. El navegador pensó que todo lo que sigue era parte del título. Agregamos la etiqueta de cierre, y la lista vuelve a verse normal. Regla: cada vez que abras una etiqueta, ciérrala de inmediato.
>
> **[Pausa y adivina 2]** Segundo reto. Los títulos deberían tener color y una línea debajo, pero se ven normales. Pausa el video y piensa qué puede faltar. *(10 segundos de silencio con el resultado fijo en pantalla.)*
>
> Error número dos: olvidar un punto y coma en el ce ese ese. Aquí queremos que los títulos tengan color y una línea debajo, pero no pasa nada. Revisamos la regla del hache dos: falta el punto y coma después del color. El navegador junta las dos líneas, no las entiende, y las ignora. Lo agregamos, y funciona.
>
> **[Pausa y adivina 3]** Tercer reto, y este es más difícil. La imagen se ve bien, pero falta algo importante en el código. Pausa el video y piensa qué puede ser. *(10 segundos de silencio con el resultado fijo en pantalla.)*
>
> Error número tres: olvidar el atributo alt en una imagen. Este error no se ve a simple vista, y por eso es peligroso. La imagen aparece bien, pero una persona que usa un lector de pantalla no sabrá qué hay en ella. Agregamos un alt que describa lo que se ve.
>
> **[Pausa y adivina 4]** Cuarto reto. Fíjate en la imagen: aparece un ícono roto. Pausa el video y piensa por qué no se muestra. *(10 segundos de silencio con el resultado fijo en pantalla.)*
>
> Error número cuatro: una ruta equivocada. Esta imagen muestra un ícono roto. El ese erre ce apunta a una carpeta llamada imágenes, pero ese archivo no existe. Si la imagen está en internet, copia la dirección completa y comprueba que abre en una pestaña nueva.
>
> **[Pausa y adivina 5]** Último reto. Este párrafo debería verse destacado, pero se ve normal. Pausa el video y piensa qué está pasando. *(10 segundos de silencio con el resultado fijo en pantalla.)*
>
> Error número cinco: un nombre mal escrito. En el hache te eme ele escribimos destacdo, sin la o, pero en el ce ese ese la clase se llama destacado. Para el navegador son nombres distintos, y por eso no aplica el estilo. Los nombres deben ser idénticos, letra por letra.

---

## Escena 4 · Cómo buscar un error

**Pantalla:** Tarjeta con cinco pasos que aparecen uno a uno. Después, abrir el validador de HTML del W3C («Validate by Direct Input»), pegar el código de `starter-files/lesson-06/index.html` y mostrar la lista de mensajes con el número de línea; marcar el mensaje del `h2` y el del `alt`. Abrir el validador de CSS, pegar el CSS y mostrar el mensaje del punto y coma. Texto en pantalla: «El validador no encuentra todos los errores: el nombre mal escrito y la ruta se descubren mirando el resultado».

**Voz:**
> Cuando algo falla, sigue estos pasos. Uno: respira y mira qué se ve distinto de lo que esperabas. Dos: revisa la parte del código relacionada, línea por línea. Tres: cambia una sola cosa a la vez y mira el resultado. Cuatro: usa un validador, una página gratuita que revisa tu código y te dice dónde hay errores. Para el hache te eme ele existe el validador del W3C. Pegas tu código, das clic en check, y te muestra la lista de mensajes con el número de línea. Mira: nos avisa del título sin cerrar y de la imagen sin alt. Para el ce ese ese hay otro validador, y nos avisa del punto y coma que falta. Pero ojo: los validadores no lo encuentran todo. El nombre mal escrito y la ruta equivocada los descubres mirando el resultado. Y cinco: si sigues atascado, pregunta a alguien y muéstrale tu código.

---

## Escena 5 · El inspector del navegador

**Pantalla:** Hacer clic derecho sobre un título en el resultado y elegir «Inspeccionar». Mostrar el panel con el hache te eme ele y los estilos que se aplican. Texto en pantalla: «Clic derecho → Inspeccionar» y «Funciona en Chrome, Firefox y Edge».

**Voz:**
> Tu navegador tiene una herramienta secreta para encontrar errores: el inspector. En Chrome, Firefox y Edge, haz clic derecho sobre cualquier elemento y elige Inspeccionar. Se abre un panel que muestra el hache te eme ele tal como lo entendió el navegador, y los estilos que se están aplicando a ese elemento. Si un estilo no se aplica, ahí lo verás tachado o no lo verás. Es como mirar con rayos equis por dentro de la página.

---

## Escena 6 · Buenas prácticas

**Pantalla:** Tarjeta con cinco consejos que aparecen uno a uno: «Sangría: deja espacios para ver qué está dentro de qué», «Nombres claros para las clases», «Siempre escribe el alt», «Guarda y prueba seguido», «Comenta tu código con `<!-- -->`». Mostrar un ejemplo corto de código con y sin sangría.

**Voz:**
> Algunos hábitos te ahorrarán muchos errores. Deja espacios al inicio de las líneas, para ver qué está dentro de qué. Elige nombres claros para tus clases. Escribe siempre el alt en tus imágenes. Guarda y prueba tu página después de cada cambio pequeño, no al final. Y usa comentarios para dejarte notas dentro del código. Tu futuro yo te lo agradecerá.

---

## Escena 7 · Cómo pedir ayuda

**Pantalla:** Mostrar un mensaje de ejemplo bueno: «Mi título no cambia de color. Esta es mi regla de CSS y esta es mi página». Contrastar con un mensaje malo: «No funciona».

**Voz:**
> Si sigues atascado, pedir ayuda es parte del camino. Pero hazlo bien. En lugar de decir: no funciona, cuenta qué esperabas que pasara, qué pasó en realidad, y muestra tu código. Con esa información, cualquier persona te podrá ayudar mucho más rápido.

---

## Escena 8 · Mini repaso

**Pantalla:** Tres preguntas en pantalla, una por una, con 7 segundos de silencio después de cada una. Al final, una tarjeta con las tres respuestas.

**Voz:**
> Antes de practicar, hagamos un repaso rápido de un minuto. Te haré tres preguntas. Después de cada una, pausa el video y piensa tu respuesta.
>
> Pregunta uno. Si abres una etiqueta y no la cierras, ¿qué puede pasar? *(7 s de silencio.)*
>
> Pregunta dos. ¿Para qué sirve el atributo alt en una imagen? *(7 s de silencio.)*
>
> Pregunta tres. ¿Qué haces si un estilo del ce ese ese no se aplica? *(7 s de silencio.)*
>
> Respuestas. Uno: el navegador puede mezclar lo que sigue con esa etiqueta, y la página se ve rara. Dos: el alt describe la imagen para quien no puede verla. Tres: revisa si falta un punto y coma, si el nombre está bien escrito y mira el inspector del navegador. ¡Muy bien! Ahora sí, a practicar.

---

## Escena 9 · Práctica

**Pantalla:** Aviso grande «⏸️ Pausa el video y practica». Texto en pantalla: «Abre el link: es la misma página con los 5 errores» y «Corrígelos sin mirar el video». Dejar 150 segundos (2 min 30 s) con el fiddle abierto y sin voz.

**Voz:**
> Es tu turno. Abre el link de la descripción. Es la misma página con los cinco errores. Intenta corregirlos sin mirar el video, usando los pasos que acabas de aprender. Pausa el video y practica.

*(Silencio de 150 segundos.)*

**Después de la práctica — Voz:**
> ¿Cómo te fue? Abre ahora el link de la versión resuelta, que también está en la descripción, y compara tu código con el nuestro. Si encontraste los cinco errores, ¡excelente! Y si te faltó alguno, no te preocupes: eso también es aprender.

**Pantalla:** abrir el fiddle «Lección 6 - Completed» y señalar los cinco cambios.

---

## Escena 10 · Qué sigue

**Pantalla:** Tarjeta con tres ideas: «Documentación de MDN en español», «Crea otra página: una receta, tu club o tu equipo favorito», «Lo que sigue: diseño adaptable y JavaScript». Mostrar la página principal de la documentación de MDN en español.

**Voz:**
> ¿Qué sigue? Primero, visita la documentación de eme de ene, en español. Es una biblioteca de consulta gratuita donde puedes buscar cualquier etiqueta o propiedad. Segundo, practica con proyectos propios: crea una página sobre una receta, tu club o tu equipo favorito. Y tercero, cuando te sientas listo, aprende a hacer que tus páginas se vean bien en cualquier pantalla, y después descubre JavaScript, el lenguaje que le da vida a las páginas.

---

## Escena 11 · Despedida

**Pantalla:** Tarjeta «Lo que aprendiste en el curso» con seis líneas, una por lección. Después, una pantalla final: «¡Gracias por completar el curso!».

**Voz:**
> Lo que aprendiste en estas seis lecciones: qué es una página web, cómo se escribe el hache te eme ele, cómo agregar listas, imágenes y enlaces, cómo darle estilo con ce ese ese, cómo crear una página completa y cómo corregir errores. Eso es mucho. Ya sabes crear una página web desde cero. ¡Gracias por completar el curso, y sigue practicando!
