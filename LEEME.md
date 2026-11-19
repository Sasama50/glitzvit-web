# Web de Glitzvit (glitzvit.com)

Página estática: no necesita servidor ni instalación. Para verla, abre `index.html` con doble clic.

- `index.html`: toda la página (texto, estilos y la demostración).
- `assets/img/`: capturas de los 3 trabajos (la de subastas tiene matrículas y la distancia a Vitoria desenfocadas).
- `assets/fonts/`: tipografías alojadas aquí (no se cargan de Google, por privacidad).

Cambiar texto: edita `index.html` (busca el texto y cámbialo). Cambiar colores: bloque `:root` al principio del CSS.

Antes de publicar con actividad económica registrada: añadir aviso legal y política de privacidad (identificación del titular).

## Idioma (19/11/2026)
La página es bilingüe español/inglés con el botón EN/ES de la cabecera. Por defecto se muestra en español si el navegador está en es/ca/eu/gl y en inglés en otro caso; `?lang=en` o `?lang=es` fuerzan un idioma. No guarda nada en el navegador. Los textos en inglés están en el objeto `EN` del primer `<script>`; los de español son el propio HTML. Al cambiar un texto en español, cambiar también su versión en `EN` (misma clave `data-t`).
