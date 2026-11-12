# Lección 3: Más elementos HTML

**Duración:** ~8 minutos · **Herramienta:** JSFiddle · **Práctica:** `starter-files/lesson-03`

**Objetivo:** que el estudiante agregue listas, una imagen con texto alternativo y un enlace a su página.

> **Pantalla** es lo que se muestra y se hace; **Voz** es el texto que se pega en el generador de voz. Las siglas están escritas como suenan.

---

## Escena 1 · 0:00–0:16 · Repaso

**Pantalla:** El fiddle con la página de la lección 2 (título y dos párrafos).

**Voz:**
> En la lección anterior hiciste tu primera página, con un título y dos párrafos. Hoy tu página va a crecer. Vas a aprender a hacer listas, a poner imágenes y a crear enlaces.

---

## Escena 2 · 0:16–1:29 · Listas

**Pantalla:** Escribir `<h2>Mis hobbies</h2>` y debajo una lista `ul` con tres `li`: «Dibujar», «Jugar fútbol», «Escuchar música». Mostrar los puntos en el resultado. Después escribir `<h2>Pasos para hacer un sándwich</h2>` y una lista `ol` con tres `li`: «Toma dos panes.», «Agrega queso.», «Junta los panes.». Mostrar los números en el resultado. Texto en pantalla: «ul = con puntos», «ol = con números», «li = cada elemento».

**Voz:**
> Empecemos con las listas. Hay dos tipos. La lista con puntos se hace con la etiqueta u ele. La lista con números se hace con la etiqueta o ele. En las dos, cada cosa de la lista va dentro de una etiqueta ele i. Hagamos una lista de hobbies. Primero pongo un título con hache dos: Mis hobbies. Abro u ele. Dentro escribo tres ele i: Dibujar, Jugar fútbol y Escuchar música. Cierro la u ele. Mira: aparecen tres puntos. Ahora hagamos una lista de pasos. Escribo otro título, y esta vez uso o ele. Los puntos cambian por números. Usa la lista con puntos cuando el orden no importa. Y usa la lista con números cuando el orden sí importa, como en una receta.

---

## Escena 3 · 1:29–2:53 · Imágenes

**Pantalla:** Escribir `<h2>Mi mascota favorita</h2>` y la etiqueta `<img src="https://picsum.photos/id/237/300/200" alt="Un perrito de pelo negro mirando a la cámara">`. Con recuadros, marcar `src` («dónde está la imagen») y `alt` («qué se ve en la imagen»). Mostrar la imagen en el resultado. Texto en pantalla: «img no lleva etiqueta de cierre».

**Voz:**
> Sigamos con las imágenes. Para poner una imagen usamos la etiqueta i eme ge. Esta etiqueta es especial: no se cierra, porque no lleva nada adentro. Pero sí necesita dos datos extra, que se llaman atributos. El primero es ese erre ce. Le dice al navegador dónde está la foto. Aquí va la dirección de internet de la imagen. El segundo es alt. Es un texto corto que cuenta qué se ve en la foto. Ayuda a las personas que no pueden ver bien y usan un programa que les lee la pantalla. Y también aparece si la foto no carga. Escribo la etiqueta con su ese erre ce, y en el alt pongo: Un perrito de pelo negro mirando a la cámara. ¡Listo! Ya aparece la foto. Recuerda: usa fotos que tengas permiso de usar, y nunca olvides el alt.

---

## Escena 4 · 2:53–3:33 · Dónde conseguir imágenes

**Pantalla:** Mostrar un banco de imágenes gratuitas (sin marcas ni nombres de autores en el video) y la página de una foto con su licencia. Texto en pantalla: «Revisa la licencia antes de usar una imagen».

**Voz:**
> Seguro te preguntas: ¿de dónde saco las fotos? Puedes usar páginas de fotos gratis, o fotos que tomaste tú. Si la foto es de otra persona, primero revisa su licencia. La licencia te dice si puedes usarla. En una página real, las fotos se guardan junto a tus archivos. Pero en este curso usaremos la dirección de internet de la foto, para que todo funcione en el editor.

---

## Escena 5 · 3:33–4:42 · Enlaces

**Pantalla:** Escribir `<h2>Quiero aprender más</h2>` y `<p><a href="https://developer.mozilla.org/es/">Aprende más en MDN</a></p>`. Con recuadros, marcar «Etiqueta a», «Atributo href: a dónde lleva» y «Texto del enlace». Mostrar el enlace azul y subrayado en el resultado. Texto en pantalla: «Mal: haz clic aquí» y «Bien: Aprende más en MDN».

**Voz:**
> Ahora vamos con los enlaces. Los enlaces unen unas páginas con otras, y así se forma la web. Un enlace se hace con la etiqueta a. Lleva el atributo hache ref, que guarda la dirección a donde vas a ir. Y entre la apertura y el cierre va el texto donde se hace clic. Hagamos uno. Escribo a, y en hache ref pongo la dirección de eme de ene, una página para aprender a programar. El texto será: Aprende más en eme de ene. Cierro la etiqueta. Mira: el texto se ve azul y subrayado. Si hago clic, me lleva a esa página. Un consejo: el texto del enlace debe decir a dónde lleva. No escribas solo: haz clic aquí.

---

## Escena 6 · 4:42–5:48 · Juntando todo

**Pantalla:** Recorrer la página completa en el resultado y resaltar con un recuadro cada elemento cuando se nombra: `h1`, `p`, `ul`, `ol`, `img`, `a`.

**Voz:**
> Miremos la página completa. Arriba está el título con hache uno y dos párrafos con pe. Después, un título hache dos y una lista con puntos. Más abajo, otra lista, pero con números. Luego, una imagen con su alt. Y al final, un enlace dentro de un párrafo. Los títulos hache dos separan cada parte, como los capítulos de un libro. Así cualquiera entiende cómo está ordenada tu página, incluso quien la escucha con un lector de pantalla. Un último consejo: dentro de una lista solo van etiquetas ele i. Si pones texto suelto, el navegador se puede confundir.

---

## Escena 7 · 5:48–7:46 · Práctica

**Pantalla:** Aviso grande «⏸️ Pausa el video y practica». Texto en pantalla: «1. Una lista con tus hobbies», «2. Una imagen con su alt», «3. Un enlace a un sitio que te guste». Dejar 90 segundos con el fiddle abierto y sin voz.

**Voz:**
> ¡Ahora te toca a ti! Abre el link de la descripción. Verás la página de la lección anterior. Agrega tres cosas: una lista con tus hobbies, una imagen con su alt, y un enlace a una página que te guste. Pausa el video y practica.

*(Silencio de 90 segundos.)*

---

## Escena 8 · 7:46–8:18 · Cierre

**Pantalla:** Tarjeta «Lo que aprendiste hoy»: «ul y ol para listas», «img con src y alt», «a con href para enlaces». Después, «Siguiente: Lección 4, Introducción a CSS».

**Voz:**
> Hoy aprendiste tres cosas. Las listas se hacen con u ele o con o ele. Las imágenes, con i eme ge. Y los enlaces, con la etiqueta a. Tu página ya tiene más contenido, pero todavía se ve muy simple. En la próxima lección le daremos color y estilo con ce ese ese. ¡Nos vemos!
