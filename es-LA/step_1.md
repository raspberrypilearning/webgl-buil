Para construir un proyecto usando WebGL, asegúrese de que WebGL ha sido seleccionado en la configuración de construcción.

Haz clic en **Archivo** y luego en **Configuración de construcción**.

![menú de archivo mostrado con configuración de construcción resaltada](images/1_file_build_settings.png)

Asegúrate de que **WebGL** esté seleccionado, luego haga clic en el botón **Construir y ejecutar**, y luego elija dónde desea guardar su proyecto construido. Esto tomará unos minutos en tu primera ejecución, pero será más rápido en las siguientes compilaciones.

**Consejo:** Si acaba de configurar la configuración de compilación de WebGL, deberá hacer clic en el botón **Cambiar** antes de ver el botón **Construir y Ejecutar**.

![Botón Construir y Ejecutar resaltado en el menú Configuración de Construcción](images/7_build_run.png)

Tu juego debería abrirse automáticamente en tu navegador web predeterminado y ser jugable.

![el jugador WeGL mostrado con un juego en ejecución](images/8_webgl_player.png)

En la ubicación donde elegiste guardar tu proyecto, deberías ver un archivo `index.html`, un directorio `Build` y un directorio `Template`.

![dos directorios y un archivo de índice mostrado](images/8a_webgl_files.png)

Aunque tu archivo `index.html` contiene al jugador para tu juego, no se ejecutará sin usar un servidor web. El servidor web fue proporcionado por Unity cuando haces clic en **Construir y Ejecutar**.
