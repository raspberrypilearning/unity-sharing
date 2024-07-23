## Compartir proyectos de Unity

Cuando tu proyecto esté completo, podrás compartirlo con tus amigos o familiares.

Si es la primera vez que compartes un proyecto, debes cambiar la configuración de compilación.

Haz clic en el menú **Archivo** y selecciona **Configuración de compilación...**.

![Menú Archivo seleccionado y Configuración de compilación resaltada.](images/1_file_build_settings.png)

En la siguiente pantalla, selecciona **WebGL** y haz clic en la opción **Instalar con Unity Hub**.

![Opción WebGL seleccionada y el botón Instalar con Unity Hub resaltado.](images/2_install_webgl.png)

En la siguiente pantalla, haz clic en el botón **Instalar** y luego espera a que se instale el módulo WebGL.

![Añadir pantalla de módulos con el botón Instalar resaltado.](images/3_add_modules.png)

Una vez que el módulo se haya instalado, puedes cerrar Unity Hub, y luego cerrar Unity y reiniciarlo.

Una vez que Unity se haya vuelto a abrir, verifica que **Configuración de compilación...** del menú **Archivo** se haya actualizado y muestre que WebGL se ha instalado. Luego haga clic en el botón **Configuración del jugador...**.

![La ventana de Configuración se muestra con las opciones de WebGL resaltadas y el botón de Configuración del reproductor resaltado.](images/5_webgl_installed.png)

En el menú de Reproductor de la izquierda, en el menú plegable para la configuración de publicación, seleccione **Desactivado** de las opciones de formato de compresión.

![Ventana de configuración del proyecto con el menú Reproductor resaltado y el formato de compresión ajustado a Desactivado y resaltado.](images/6_disable_compression.png)

Cierra la ventana de configuración y haz clic en el botón **Construir y ejecutar**, luego elige dónde quieres guardar tu proyecto construido. Esto tomará unos minutos en tu primera ejecución, pero será más rápido en las siguientes compilaciones.

![Botón Construir y Ejecutar resaltado en el menú Configuración de compilación.](images/7_build_run.png)

Tu juego debería abrirse automáticamente en tu navegador web predeterminado, y poder jugarse.

![El jugador WebGL se muestra con un juego en ejecución.](images/8_webgl_player.png)

Para compartir tu proyecto, necesitas subirlo a un servidor web. Hay muchas maneras de hacer esto, pero una de las más simples es usar [repl.it](https://replit.com).

Abre repl.it en tu navegador web e inicia una sesión o regístra una cuenta si no tienes una.

![Crear botón repl.](images/9_create_repl.png)

Elije crear un proyecto **HTML, CSS, JS** dale un nombre a tu proyecto y haz clic en el botón **Crear Repl**.

![El menú html, css, js para crear un nuevo repl.](images/10_html_repl.png)

Utiliza los tres menús de puntos para eliminar todos los archivos del proyecto.

![Menú seleccionado para el archivo de índice y el botón Eliminar mostrado en rojo.](images/11_delete_files.png)

Ahora puedes arrastrar y soltar todos tus archivos de compilación en tu proyecto repl.it.

![Los archivos build, TemplateData, index.html y carpetas como se muestran en repl.it.](images/12_drag_drop_files.png)

Haz clic en el botón **Ejecutar** y deberías ver tu juego corriendo en la ventana de salida.

![URL del juego que se muestra en la ventana de salida.](images/13_game_url.png)

En la parte superior de la ventana de salida, verás una URL. Esta es la URL de tu juego; puedes compartirla con la gente.

<div>
  <iframe allowtransparency="true" width="500" height="400" src="https://sharegame.marcscott.repl.co/" frameborder="0"></iframe>
</div>






