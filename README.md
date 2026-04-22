## Plantilla de Tienda de Aplicaciones de la Comunidad para Umbrel

Este repositorio es una plantilla para crear una Tienda de Aplicaciones de la Comunidad para Umbrel. Estas tiendas de aplicaciones adicionales permiten a los desarrolladores distribuir sus aplicaciones sin necesidad de enviarlas a la [Tienda Oficial de Aplicaciones de Umbrel](https://github.com/getumbrel/umbrel-apps).

## Cómo usar:

1. Comienza haciendo clic en el botón "Use this template" (Usar esta plantilla) ubicado arriba.
2. Asigna un ID y un nombre a tu tienda de aplicaciones dentro del archivo `umbrel-app-store.yml`. Este archivo especifica dos atributos importantes:
    - `id` - Actúa como un prefijo único para cada aplicación dentro de tu Tienda de la Comunidad. Debes comenzar el ID de tu aplicación con el ID de tu tienda. Por ejemplo, en esta plantilla, el ID de la tienda es `cmoraes`, y hay una aplicación llamada `hello world`. En consecuencia, el ID de la aplicación debería ser: `cmoraes-hello-world`.
    - `name` - Este es el nombre de la Tienda de la Comunidad que se muestra en la interfaz de umbrelOS.
3. Cambia el nombre de la carpeta `cmoraes-hello-world` para que coincida con el ID de tu aplicación. Tú decides el ID de tu aplicación. Por ejemplo, si el ID de tu tienda es `whistles`, y tu aplicación se llama Mi Descargador de Videos, podrías establecer su ID como `whistles-my-video-downloader`, y renombrar la carpeta en consecuencia.
4. Luego, ingresa los detalles de tu aplicación en el archivo `whistles-my-video-downloader/umbrel-app.yml`. Estos se muestran en la interfaz de umbrelOS.
5. Incluye los servicios de Docker necesarios en `whistles-my-video-downloader/docker-compose.yml`.
6. ¡Eso es todo! Tu Tienda de la Comunidad, con tu aplicación única, está configurada y lista para usar. Para utilizar tu Tienda de la Comunidad, puedes agregar su URL de GitHub a la interfaz de usuario de umbrelOS como se muestra en la siguiente demostración:


https://user-images.githubusercontent.com/10330103/197889452-e5cd7e96-3233-4a09-b475-94b754adc7a3.mp4
