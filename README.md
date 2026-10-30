# ZeroStress Shoping

App de lista de la compra de uso personal, sin inicio de sesión ni conexión a Firebase.

## Uso
- Añade productos por tienda, notas y fotos.
- Marca productos como comprados o elimínalos.
- Registra gastos y consulta el histórico mensual.
- **Compartir lista (imagen)** crea una imagen PNG de la lista pendiente, incluyendo las fotos de los productos. En móviles compatibles abre el menú nativo para enviarla por WhatsApp; si no, descarga el PNG para adjuntarlo manualmente.
- **Exportar copia** descarga un JSON de respaldo.

## Datos
Los datos se guardan en el almacenamiento local del navegador/dispositivo. No se sincronizan automáticamente entre dispositivos ni se suben a Firebase. Si borras los datos del navegador o cambias de dispositivo, importa/recupera el respaldo manualmente (la importación aún no está implementada).

## Publicación
Puede alojarse como sitio estático en GitHub Pages. La app conserva soporte PWA y caché offline.
