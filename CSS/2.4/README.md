## Parte A - Cajas visibles y centradas

He creado una página con un contenedor principal, una cabecera, una zona de contenido y un pie de página.

He utilizado diferentes colores y bordes para distinguir las cajas. También he centrado la página con `margin: 0 auto` y he añadido padding para separar el contenido de los bordes.

## Parte B - Display

Al principio, las tarjetas se mostraban una debajo de otra porque tienen `display: block` por defecto.

Al utilizar `inline-block`, la tercera tarjeta saltaba de línea porque el ancho total superaba los 800px disponibles.

La cuenta es:

210 + 30 + 2 + 20 = 262px por tarjeta.

262 × 3 = 786px.

He elegido `display: flex` porque permite colocar las tres tarjetas en la misma fila de una forma sencilla.

## Parte C - Block, inline y none

1. **Diferencia entre margin y padding:** El margin es el espacio exterior de una caja y el padding es el espacio interior, entre el contenido y el borde.

2. **Por qué saltaba la tercera tarjeta:** Porque el ancho total de las tres tarjetas, contando el padding, los bordes y los márgenes, superaba los 800px.

3. **Propiedades que ignoraba el span:** Al ser un elemento en línea, no se aplicaban el width, el height ni los márgenes verticales. Al poner `display: inline-block`, sí se aplican.

4. **Qué hace display: none:** Oculta el elemento y elimina el espacio que ocupaba, por lo que las demás tarjetas ocupan su lugar.