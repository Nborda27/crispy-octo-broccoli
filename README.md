# Adiós Nonino

Partitura en ASCII de la melodía de *Adiós Nonino* (Astor Piazzolla, 1959), en la versión de Artem Amaro grabada el 16 de junio de 2013 en el Royal Conservatoire of Scotland, Glasgow.

Unos 150 segundos —de 04:00 a 06:30 del [video](https://www.youtube.com/watch?v=pavplLzT7Mk)— se dibujan como un paisaje monoespaciado: cada fila es un semitono, el grano sigue la dinámica y el panel inferior resume las siete frases. El audio no viaja con la página; el modo de audio original abre el reproductor de YouTube.

La pieza publicada es [`index.html`](index.html), autocontenida. La fuente editable y el análisis están en [`src/`](src/). Un adelanto mudo está en [`assets/preview.mp4`](assets/preview.mp4).

## Controles

- Arrastrar el campo, o usar la rueda, para recorrer el tiempo. En el teléfono el gesto sigue el dedo y la página no se desplaza.
- En una pantalla estrecha la partitura ocupa el alto: los datos van en dos columnas, la leyenda queda sobre el campo, los controles en su propia fila y el video, si se abre, debajo de la melodía.
- Clic en el panel inferior para saltar a ese instante.
- `Espacio`: reproducir o pausar.
- `←` / `→`: frase anterior o siguiente.
- `D`: tema oscuro o claro.
- `Y`: audio original por YouTube, o volver al silencio.
- `R`: volver al inicio.

Los botones de abajo a la derecha hacen lo mismo: pausa, tema y audio original.

## Parámetros

- `?theme=dark` abre en tema oscuro.
- `?t=72` empieza en ese segundo de la melodía.
- `?rec=1` oculta la interfaz y deja el tiempo quieto, para capturar un fotograma.

Sitio: <https://nborda27.github.io/crispy-octo-broccoli/>
