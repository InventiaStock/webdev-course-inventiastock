# Lección 5: Crear una página web sencilla

**Duración prevista:** aproximadamente 12 minutos.
**Herramienta:** JSFiddle.
**Objetivo:** unir HTML y CSS para crear una página de perfil
personal y aprender a encontrar un error.

**Práctica inicial:** starter-files/lesson-05
**Ejemplo terminado:** completed-examples/lesson-05

El personaje Alex Rivera es ficticio.
Los tiempos son orientativos: se ajustan al audio y la demostración.
En JSFiddle, pulsar Ejecutar después de cada cambio.
Pegar el código por bloques y explicar sus efectos.

## Escena 1 · El proyecto
Tiempo orientativo: 0:00–0:50

**Pantalla:**
Mostrar la portada de la Lección 5 durante 3 segundos.
Después, mostrar el resultado terminado en JSFiddle:
foto redonda, nombre, tres secciones y pie de página.
Texto en pantalla: «Proyecto: tu página de perfil».

**Voz:**
Llegó el momento de juntar todo lo que aprendiste.
En esta lección vas a crear una página de perfil personal.
Tendrá una foto, tu nombre, una sección sobre ti,
una lista de tus hobbies y un enlace a un sitio que te guste.
Esta es la página terminada.
Vamos a construirla juntos, paso a paso.
Y al final, vas a aprender a encontrar y corregir errores.
Usaremos a un personaje ficticio llamado Alex,
pero tú vas a poner tus propios datos.

## Escena 2 · El plan
Tiempo orientativo: 0:50–1:25

**Pantalla:**
Mostrar la diapositiva del plan.
Señalar el encabezado, las tres secciones y el pie de página
a medida que se mencionan.

**Voz:**
Antes de escribir código, siempre conviene hacer un plan.
Dibujemos un boceto.
Arriba, un encabezado con la foto, el nombre y una frase corta.
En el medio, tres secciones:
sobre mí, mis hobbies y mi sitio favorito.
Abajo, un pie de página.
Cada parte de este boceto será una etiqueta
de hache te eme ele.

## Escena 3 · El HTML paso a paso
Tiempo orientativo: 1:25–3:37

**Pantalla:**
Mostrar JSFiddle con el panel CSS vacío.
En el panel HTML se pega solamente el contenido del body.
Agregar el encabezado, el contenido principal con sus tres
secciones y el pie de página, por bloques.
Pulsar Ejecutar después de cada bloque.

Resaltar una etiqueta a la vez.
Mostrar los siguientes textos cuando corresponda:
- «header = encabezado»
- «main = contenido principal»
- «section = sección»
- «footer = pie de página»

**Voz:**
Empecemos con el hache te eme ele.
Para organizar la página usaremos etiquetas con significado.
Header, para el encabezado.
Main, para el contenido principal.
Section, para cada sección.
Y footer, para el pie de página.

Funcionan como una caja, pero además le dicen al navegador
qué función cumple cada parte.
Si usáramos solo cajas genéricas, la página se vería igual,
pero sería más difícil de entender para quienes
la escuchan con un lector de pantalla.

Fíjate que cada bloque de código que pego corresponde
a una parte de nuestro boceto.
En el header ponemos la imagen, con su ese erre ce y su alt.
El ese erre ce indica la dirección de la imagen.
El alt describe su contenido.
Debajo colocamos un hache uno con el nombre
y un párrafo con una frase corta.
A la imagen le ponemos la clase foto,
que nos servirá después para darle estilo.

Ahora el main.
En la primera section, un hache dos que diga Sobre mí,
y un párrafo con una pequeña presentación.
En la segunda, un hache dos que diga Mis hobbies,
y una lista con puntos.
En la tercera, un hache dos que diga Mi sitio favorito,
y un párrafo con un enlace.

Fíjate que dentro del main hay tres section,
una por cada rectángulo del boceto.
Por último, el footer, con un párrafo corto.
Así queda la página sin estilo:
todo el contenido está, pero se ve muy sencillo.

## Escena 4 · El CSS paso a paso
Tiempo orientativo: 3:37–6:07

**Pantalla:**
Mostrar la diapositiva de CSS como introducción breve.
Volver a JSFiddle.
Agregar las reglas CSS en este orden:
body, header, .foto, main, section, h2, a y footer.
Pulsar Ejecutar después de cada regla
y mostrar el cambio en el resultado.

Resaltar las propiedades que se explican.
Texto en pantalla, cuando corresponda:
- «border-radius: 50% = círculo»
- «margin: 0 auto = centrado»

**Voz:**
Ahora la ropa de nuestra página: el ce ese ese.
Pegaré las reglas una por una,
y después de cada una mira cuánto cambia la página.
Aprender ce ese ese es probar y mirar.

Empezamos por el body.
Le ponemos la letra Arial, un fondo gris muy claro
y un texto gris oscuro.
También quitamos el margen que el navegador pone
por defecto, con margin cero.

Luego el header:
fondo azul oscuro, texto blanco, texto centrado
y un padding para darle aire.
El padding es el espacio interior.

La foto tiene la clase foto.
Le damos un ancho y un alto de ciento cuarenta píxeles.
Con border radius de cincuenta por ciento,
el cuadrado se convierte en un círculo.
También le ponemos un borde blanco,
y la propiedad object fit con el valor cover,
para que la foto conserve sus proporciones
y llene el espacio, aunque se recorte una parte.

Ahora el main.
Para que el contenido no se estire en pantallas grandes,
le damos un ancho máximo de seiscientos píxeles.
Y para centrarlo usamos margin cero y auto.
El auto reparte el espacio sobrante a los lados.

Después, cada section:
fondo blanco, un borde fino gris,
esquinas redondeadas con border radius,
padding y un margin abajo para separar una de otra.

Los títulos hache dos tendrán el mismo azul
del encabezado, para que toda la página se vea coherente.
Los enlaces, un color marrón rojizo
que se lee bien sobre el blanco.
Y el footer, con el texto centrado,
en gris y con padding.

¡Mira cómo quedó!
Pasamos de una página simple a una página de perfil
con muy buen aspecto.

## Escena 5 · Probar en otros tamaños
Tiempo orientativo: 6:07–6:47

**Pantalla:**
Cambiar el ancho del panel del resultado en JSFiddle.
Mostrar el contenido en una vista ancha y en una angosta.
Comprobar que las tarjetas se adaptan al espacio disponible.
Texto en pantalla: «max-width: 600px».

**Voz:**
Un detalle que vale la pena probar:
cambia el tamaño de la ventana y mira lo que pasa.
Gracias al ancho máximo y al centrado,
el contenido se mantiene ordenado,
no se estira de lado a lado.
Así tu página se ve bien en una pantalla grande
y también en una más pequeña.
Más adelante aprenderás a ajustar la página
aún mejor para celulares.

## Escena 6 · Encontrar un error
Tiempo orientativo: 6:47–8:02

**Pantalla:**
En la regla section, borrar únicamente el punto y coma
que sigue a padding: 15px.
Mantener margin-bottom: 15px; en la línea siguiente.
Pulsar Ejecutar y mostrar la pérdida de los espacios.

Señalar el error con un recuadro.
Restaurar el punto y coma, pulsar Ejecutar
y mostrar el resultado corregido.

Texto en pantalla: «Cambia una sola cosa a la vez».

**Voz:**
Ahora una habilidad clave: encontrar errores.
A todos nos pasa, incluso a quienes programan hace años.
Vamos a cometer uno a propósito.
Borro un punto y coma en la regla de section,
justo después del padding.
Pulso Ejecutar.

Mira: las secciones perdieron el espacio de adentro
y el espacio entre ellas.
¿Por qué?
Porque el navegador lee el padding y el margin
como si fueran una sola instrucción.
No la entiende, y la ignora completa.

Para encontrarlo, leemos la regla con calma,
línea por línea, y buscamos qué falta.
Ahí está: el punto y coma.
Lo agrego y vuelvo a ejecutar.
Todo vuelve a la normalidad.

Un consejo:
cuando algo no se ve como esperas,
cambia una sola cosa a la vez
y revisa el resultado después de cada cambio.

## Escena 7 · Ideas para mejorar tu perfil
Tiempo orientativo: 8:02–8:31

**Pantalla:**
Mostrar variaciones de la página:
otros colores, una sección de Mis metas y otra imagen.
Usar una copia de demostración para conservar
el ejemplo terminado original.
Texto en pantalla: «Hazla tuya».

**Voz:**
Cuando termines, haz que la página sea tuya.
Puedes cambiar los colores,
agregar una sección nueva, como Mis metas
o Mis libros favoritos,
usar otra foto o poner más enlaces.
Lo importante es que pruebes,
te equivoques y vuelvas a intentar.
Cada cambio es práctica.

## Escena 8 · Reto final
Tiempo orientativo: 8:31–11:05

**Pantalla:**
Mostrar la tarjeta del reto:
1. Cambia el nombre, la frase y los datos.
2. Pon tus hobbies.
3. Elige tus colores.
4. Agrega un enlace a tu sitio favorito.

Mostrar el aviso de práctica con el enlace real
de Lección 5 - Starter escrito encima.
Después, mostrar ese fiddle abierto.
Dejar 120 segundos de práctica sin narración.

**Voz:**
Es tu turno.
Abre el link de la descripción.
Verás la estructura de la página
con comentarios que te guían.
Cambia el nombre, la frase y los datos por los tuyos.
Escribe tus hobbies, elige tus propios colores
y agrega un enlace a tu sitio favorito.
Pausa el video y crea tu perfil.

**Silencio de práctica:** 120 segundos.

## Escena 9 · Cierre
Tiempo orientativo: 11:05–11:40

**Pantalla:**
Mostrar la tarjeta «Lo que aprendiste hoy»:
- Planear antes de escribir.
- Etiquetas con significado.
- HTML + CSS = una página completa.

Después mostrar:
«Siguiente: Lección 6, Errores comunes y próximos pasos».

**Voz:**
Lo que aprendiste hoy:
conviene planear antes de escribir,
existen etiquetas con significado como
header, main, section y footer,
y el hache te eme ele junto con el ce ese ese
forman una página completa.

Ya creaste una página de perfil.
En la última lección verás los errores más comunes
y cómo evitarlos.
¡Hasta pronto!