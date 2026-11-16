# Alma Lino · tienda Shopify de demostración

Tienda de ropa de lino y complementos de estilo mediterráneo: vestidos, monos, camisas y pantalones con tallas y colores, capazos, sombreros y joyas, y una portada a pantalla completa con el producto destacado flotando sobre la foto.

**Verla publicada:** https://alma-lino.myshopify.com/ (contraseña de la tienda de prueba: `iagiaz`)

## Qué hay en este repositorio
Solo lo hecho a medida sobre el tema gratuito Horizon de Shopify: las secciones y fragmentos propios (prefijo `al-`), las plantillas que los colocan y los ajustes del tema. El resto de Horizon no se incluye.

```
sections/al-*.liquid     Secciones propias: portada, mosaico, categorías, pie...
snippets/al-*.liquid     Estilos y fragmentos propios
templates/*.json        Plantillas con las secciones colocadas
sections/*-group.json   Cabecera y pie
config/settings_data.json  Colores, tipografías y ajustes del tema
```

## Cómo está hecha
- Shopify, tienda de desarrollo con el plan Basic
- Tema Horizon, el tema oficial y gratuito de Shopify
- Ocho secciones programadas a medida en Liquid: portada, compromisos, novedades, look en tres piezas, mosaico editorial, categorías, forma de hacer y pie de página
- Portada con titular animado, tarjeta flotante de producto, tres datos de confianza y cinta de frases en movimiento, que se desactiva si el visitante pide menos animación
- Paleta, tipografías (Playfair Display y Work Sans) y esquinas rectas propias de la marca
- Tienda, menús, correos y páginas de sistema en español

## Catálogo y compra
- 16 productos con 57 variantes de color y talla, con su stock
- Botón "Elegir talla" en las tarjetas de productos con tallas, para que nadie compre la talla equivocada sin querer
- Ficha de producto con desplegables de envíos y cambios, guía de tallas y forma de hacer
- Colecciones automáticas por etiqueta: Ropa, Complementos, Novedades y Más vendidos
- Fotos de producto creadas para la marca
- Mercado España en euros, con el precio en formato español (69,90 €)
- Envío estándar a 3,95 €, gratis a partir de 50 €, y envío exprés a 6,95 €
- Código de bienvenida BIENVENIDA10 con un 10 % de descuento
- Pasarela de pago de prueba de Shopify activa
- Pedido de prueba completo: carrito, envío calculado, pedido pagado y correo de confirmación en español

## Detalles
- Sin apps de terceros: todo funciona con herramientas propias de Shopify (colecciones, mercados, envíos, pagos y correos)
- Tema subido con Shopify CLI y código revisado con Theme Check, sin errores en las secciones propias
- Lista para añadir apps cuando el cliente las necesite: reseñas, Klaviyo, pagos a plazos o traducción

## Cómo instalarlo
1. Instala el tema Horizon en tu tienda y descárgalo con Shopify CLI (`shopify theme pull`).
2. Copia encima las carpetas de este repositorio.
3. Súbelo con `shopify theme push` o pruébalo con `shopify theme dev`.

## Sobre esta tienda
Diseño y desarrollo de [Dania360](https://dania360.com). Es una tienda de ejemplo: la marca y los productos son inventados, las fotos se crearon para la marca y el pago es de prueba, no cobra nada. El código se publica para enseñar cómo está hecha; no tiene licencia de uso.

Más tiendas en el portafolio: https://tiendas.dania360.com
