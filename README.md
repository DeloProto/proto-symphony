# Toma de pedido · Prototipo POS Simphony

Prototipo web navegable de la toma de pedido en el POS Oracle Simphony (1920×1080, escalado a la ventana).

## Flujos incluidos
- **Toma de pedido:** happy path, alimento, frappuccino, merch (por categoría, SKU y escáner), segunda venta, nombre del cliente, personalizar, edición, borrar productos, cancelar pedido (clave y huella) y errores de SKU, clave y huella.
- **Rewards:** identificar al cliente, canje de estrellas (café del día, Frappuccino, bebida + alimento, tumblers, varios productos) y beneficios (shot gratis, cumpleaños, café en grano, refill).
- **Checkout:** comprobante, pago en soles (billetes y otro monto), POS, dólares, Rewards y descuentos.

Usa el botón **Flujos** de la barra superior para saltar a cualquier escenario.

## Datos de demo
- Clave gerencial: `1234`
- SKU inexistente para probar el error: `99999`
- Lecturas de tarjeta, huella y escáner se simulan con botones marcados como *Demo*.

## Cómo usarlo
Es un solo archivo estático (`index.html`), sin dependencias ni build.
- **Local:** abre `index.html` en el navegador.
- **GitHub Pages:** sube `index.html` a la raíz del repositorio y activa Pages en *Settings → Pages* (rama `main`, carpeta `/root`).

La tipografía Inter se carga desde Google Fonts; sin conexión usa la fuente del sistema.
