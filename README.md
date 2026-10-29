# ZeroStress Shoping

Primera base funcional de la app de lista de la compra compartida.

## Incluye
- Cuatro listas separadas: MERCADONA, HIPERBER, CARREFOUR y FRUTERÍA.
- Añadir productos, notas, fotos, marcar como comprado y eliminar.
- Registrar gasto total por compra (sin desglose por producto).
- Resumen y filtrado mensual de gastos.
- Guardado local en el dispositivo y exportación de copia JSON.
- PWA instalable y caché básica para uso offline.

## Abrir
Para probarla en el ordenador, abre `index.html` en el navegador.
Para instalar como PWA y probar correctamente el service worker, sirve la carpeta desde un servidor HTTPS o localhost (por ejemplo, GitHub Pages o Firebase Hosting).

## Importante: sincronización con Frank
Esta versión guarda la información en el navegador/dispositivo actual. **Todavía no comparte los datos entre Laura y Frank.**
El siguiente paso es configurar Firebase Authentication y Firestore, definir usuarios autorizados y sincronizar listas y gastos. Las fotos compartidas necesitarán almacenamiento remoto (Firebase Storage u otra solución segura); en esta base se guardan localmente como datos de imagen.

No publiques credenciales privadas ni reglas abiertas de Firebase. Las claves de configuración web de Firebase no son contraseñas, pero deben ir acompañadas de reglas de seguridad correctas.
