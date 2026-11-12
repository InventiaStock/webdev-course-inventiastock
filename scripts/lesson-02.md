# Lección 2: Introducción a HTML

**Duración prevista:** ~8 minutos · **Herramienta:** JSFiddle · **Práctica:** `starter-files/lesson-02`

**Objetivo:** que el estudiante comprenda las etiquetas, los elementos, los atributos y la estructura básica de HTML, y escriba un título y dos párrafos.

> Este guion corresponde a las 14 diapositivas de la lección. **Pantalla** indica la demostración o tarjeta; **Voz** es el texto para la narración. Las siglas están escritas como suenan para la síntesis de voz.

## Diapositiva 01 — Portada

**Pantalla:** Mostrar portada durante 3 segundos, sin audio.

**Voz:**
> (Silencio.)

---

## Diapositiva 02 — Recordemos

**Pantalla:** Subrayar HTML al nombrarlo; después CSS. Al mencionar que trabajan juntos, resaltar ambos.

**Voz:**
> ¡Hola! Bienvenido a la segunda lección de nuestro curso de desarrollo web. ¿Recuerdas lo que aprendimos anteriormente? Descubrimos que el hache te eme ele se encarga de organizar el contenido de una página web, mientras que el ce ese ese permite darle colores, tamaños y estilos. También vimos que ambos trabajan juntos para crear las páginas que visitamos todos los días. Hoy daremos el siguiente paso. Aprenderás a escribir código hache te eme ele, conocerás sus etiquetas principales y descubrirás cómo crear tu primera página web. ¡No te preocupes si nunca has programado! Vamos a comenzar desde lo más sencillo y avanzaremos paso a paso.

---

## Diapositiva 03 — ¿Qué es un elemento?

**Pantalla:** Primero resaltar apertura <p>, contenido Hola y cierre </p>. Después escribir <p>Hola</p> en JSFiddle, pulsar Ejecutar y enseñar el resultado Hola.

**Voz:**
> El hache te eme ele se escribe con etiquetas. Una etiqueta es una palabra entre los signos menor que y mayor que. Por ejemplo, pe. Casi todas vienen en pareja: una etiqueta de apertura y una etiqueta de cierre, que lleva una barra antes del nombre. Lo que queda entre las dos es el contenido. Las tres cosas juntas forman un elemento. Escribamos uno. Abro la etiqueta pe, escribo Hola, y cierro la etiqueta. Mira el resultado: aparece la palabra Hola. La pe viene de párrafo, y sirve para escribir texto normal. Pero ojo: si olvidas cerrar una etiqueta, el navegador se puede confundir. Por eso, cada vez que abras una, acuérdate de cerrarla.

---

## Diapositiva 04 — ¿Qué es un atributo?

**Pantalla:** Resaltar en <html lang="es"> el nombre lang, el signo = y el valor "es". No necesitas pegar la etiqueta html en JSFiddle.

**Voz:**
> A veces una etiqueta necesita información extra. Para eso existen los atributos. Un atributo se escribe dentro de la etiqueta de apertura, con un nombre, un signo igual y un valor entre comillas. Por ejemplo, en la etiqueta hache te eme ele podemos escribir el atributo lang igual a es. Con eso le decimos al navegador que la página está en español. Más adelante usaremos otros atributos para las imágenes y los enlaces. Por ahora recuerda esto: el atributo va dentro de la etiqueta de apertura, y su valor va entre comillas.

---

## Diapositiva 05 — Estructura básica de HTML

**Pantalla:** Resaltar <!DOCTYPE html>, <html>, <head>, <meta>, <title> y <body>, en el orden en que se explican. La estructura completa está guardada en el archivo del repositorio.

**Voz:**
> Toda página hache te eme ele tiene la misma estructura básica. Vamos por partes. Primero, una línea especial que dice doctype html. Le avisa al navegador que usaremos la versión moderna del hache te eme ele. Después viene la etiqueta html, que envuelve todo. Dentro hay dos grandes partes. 

---

## Diapositiva 06 — ¿Head o body?

**Pantalla:** Marcar HEAD y luego BODY. Mostrar 5 segundos el editor HTML de JSFiddle para explicar que se escribe solo el contenido de body.

**Voz:**
> La primera es head, que significa cabeza. Ahí va información sobre la página que no se muestra en pantalla, como el título que aparece en la pestaña del navegador. Ese título se escribe con la etiqueta title. También va una etiqueta llamada meta, que sirve para que se vean bien las tildes y la eñe. La segunda parte es body, que significa cuerpo. Todo lo que pongas dentro del body es lo que verás en la página: textos, imágenes, listas. Un truco para recordarlo: el head es la cabeza que piensa, y el body es el cuerpo que se ve. En este editor en línea, la estructura ya viene armada por detrás, así que nosotros escribiremos solo lo que va dentro del body. Pero cuando guardes tus páginas en un archivo, la estructura completa tiene que estar.

---

## Diapositiva 07 — Elementos dentro de otros

**Pantalla:** Mostrar <em> dentro de <p>. Escribir el ejemplo con <em> y pulsar Ejecutar; la palabra mucho debe aparecer inclinada. Evitar grabar el menú de autocompletado.

**Voz:**
> Los elementos se pueden poner uno dentro de otro, como cajas dentro de cajas. Por ejemplo, dentro de un párrafo puedo resaltar una palabra con la etiqueta e eme. Escribo: Me gusta, abro e eme, escribo mucho, cierro e eme, y sigo con: programar. Mira: la palabra mucho aparece inclinada. Fíjate en el orden: la etiqueta que abrí al último es la primera que cierro. Es como cerrar cajas: primero cierras la de adentro y después la de afuera. 

---

## Diapositiva 08 — La sangría ordena tu código

**Pantalla:** Mostrar comparación sin sangría y con sangría. Si lo grabas, mostrar primero el código sin sangría y después el código con sangría.

**Voz:**
> Cuando uses muchas etiquetas, ayuda dejar espacios al inicio de cada línea, para ver qué está dentro de qué. Eso se llama sangría, y hace que tu código sea mucho más fácil de leer.

---

## Diapositiva 09 — Títulos y párrafos

**Pantalla:** Mostrar un ejemplo con un h1 y dos párrafos. Pulsar Ejecutar para ver el resultado.

**Voz:**
> Ahora escribamos contenido. Escribo hache uno: Mi primera página. Y para los textos usamos la etiqueta pe. Escribo un párrafo: Hola, me llamo Alex y estoy aprendiendo a crear páginas web. Cada párrafo va en su propia etiqueta pe. Si escribo otro párrafo, aparece debajo, separado del anterior.

---

## Diapositiva 10 — Comparar h1, h2 y h3

**Pantalla:** Escribir un ejemplo temporal con h1, h2 y h3, pulsar Ejecutar y comparar tamaños. Después volver al ejemplo anterior para no guardar h2/h3 como resultado final.

**Voz:**
> Para los títulos existen las etiquetas hache uno, hache dos, hache tres, y así hasta hache seis. El hache uno es el más grande y el más importante, y el hache seis es el más pequeño. Normalmente usamos un solo hache uno por página, como título principal. Mira cómo cambia la jerarquía entre hache uno, hache dos y hache tres. Después dejamos nuestro ejemplo con un solo título principal y dos párrafos.

---

## Diapositiva 11 — Comentarios en el código

**Pantalla:** Escribir un ejemplo con <!-- comentario --> al inicio. Pulsar Ejecutar: el comentario no debe mostrarse en el resultado.

**Voz:**
> Un truco más: a veces quieres dejar una nota para ti sin que se vea en la página. Para eso existen los comentarios. Se escriben con un signo menor que, una exclamación y dos guiones, y se cierran con dos guiones y un signo mayor que. Mira: escribo un comentario que dice: aquí va mi título. En el resultado no aparece, pero en el código sí queda. Y una cosa muy importante: equivocarse es normal. Si algo no se ve como esperabas, pasa por tu código con calma y revisa si cada etiqueta que abriste tiene su cierre, y si los atributos tienen sus comillas. Con la práctica encontrarás los errores cada vez más rápido. En la última lección veremos cómo.

---

## Diapositiva 12 — Practica HTML

**Pantalla:** Mostrar las 3 instrucciones y luego abrir el proyecto "Lección 2 - Starter" con la caja HTML vacía o con comentario de ayuda.

**Voz:**
> Es tu turno. Abre el link de la descripción. Verás un editor vacío. Escribe un título con la etiqueta hache uno que diga Mi primera página, y dos párrafos con la etiqueta pe: uno que diga quién eres, y otro que cuente qué quieres aprender. Pausa el video y practica.

---

## Diapositiva 13 — Pausa el video y practica

**Pantalla:** Mostrar aviso de pausa y mantener visible JSFiddle Starter durante 60 segundos completos SIN VOZ ni música.

**Voz:**
> (Silencio.)

---

## Diapositiva 14 — Lo que aprendiste hoy

**Pantalla:** Mostrar los tres aprendizajes y el anuncio de la Lección 3. El guion original indica cierre de 8–10 s como mínimo; prolongar la imagen si la narración dura más.

**Voz:**
> Lo que aprendiste hoy: una etiqueta se abre y se cierra; los atributos dan información extra; y toda página tiene head y body. Ya tienes tu primera página. En la próxima lección agregaremos listas, imágenes y enlaces. ¡Hasta pronto!

---

## Prácticas

- **Starter:** editor HTML vacío o comentario de ayuda. El estudiante escribe un encabezado `h1` y dos párrafos `p`.
- **Completed:** código terminado en `completed-examples/lesson-02/index.html`.
- Se debe mostrar 60 segundos de práctica sin voz ni música y presentar los enlaces oficiales de JSFiddle en la descripción del video.
