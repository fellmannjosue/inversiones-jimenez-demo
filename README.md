# Inversiones Jiménez · Demo (tienda e-commerce)

Tienda demo autónoma (HTML + JS vanilla, sin backend) con **localStorage**.
Inspirada en la arquitectura de FitcoreHN. La capa `Store` está aislada para
migrar fácil a **Laravel** más adelante.

## Incluye
- 🛍️ **Tienda**: hero, filtro por categoría, buscador, tarjetas con oferta/stock, carrito lateral.
- 💬 **Checkout por WhatsApp**: arma el pedido y abre `wa.me` con el detalle.
- 🔧 **Admin** (⚙️ arriba a la derecha): categorías, productos (precio, oferta, imagen, **stock**), destacados y ajustes (nombre, WhatsApp, moneda, contraseña).

## Uso
Abre `index.html` en el navegador.
- Admin: botón ⚙️ · contraseña demo **admin1234**.
- WhatsApp temporal: **+504 9507 6519** (cámbialo en Admin → Ajustes por el número real).
- Moneda: Lempira (**L.**).

> Los datos se guardan en el navegador (localStorage). Editar en el Admin actualiza la tienda al instante.
