## Sharing Unity projects

When your project is complete, you can share it with your friends or family.

If this is your first time sharing a project, you need to change your build settings.

Click on the **File** menu and select **Build Settings...**.

![File menu selected and Build Settings highlighted.](images/1_file_build_settings.png)

On the next screen, select **WebGL** and click on the **Install with Unity Hub** option.

![WebGL option selected and the Install with Unity Hub button highlighted.](images/2_install_webgl.png)

On the next screen, click the **Install** button, then wait for the WebGL module to be installed.

![Add modules screen with Install button highlighted.](images/3_add_modules.png)

Once the module has installed, you can close Unity Hub, and then close Unity and restart it.

Once Unity has re-opened, check that the **Build Settings...** from the **File** menu have been updated, and show that WebGL has been installed. Then click on the **Player Settings...** button.

![Build Settings window shown with the WebGL options highlighted and the Player Settings button highlighted.](images/5_webgl_installed.png)

From the Player menu on the left, in the collapsible menu for Publishing Settings, select **Disabled** from the Compression Format options.

![Project setting window with the Player menu highlighted and the Compression format set to Disabled and highlighted.](images/6_disable_compression.png)

Close the settings window and then click on the **Build And Run** button, then choose where you want to save your built project. This will take a few minutes on your first run, but will be quicker on following builds.

![Build And Run button highlighted on the Build Settings menu.](images/7_build_run.png)

You game should automatically open in your default web browser, and be playable.

![The WebGL player shown with a game running.](images/8_webgl_player.png)

To share your project, you need to upload it to a web server. There are many ways of doing this, but one of the simplest is to use [repl.it](https://replit.com).

Open repl.it in your web browser, and either sign in, or sign up for an account if you don't have one.

![Create repl button.](images/9_create_repl.png)

Choose to make an **HTML, CSS, JS** project, then give your project a name and click the **Create Repl** button.

![The html, css, js menu for creating a new repl.](images/10_html_repl.png)

Use the three dot menus to Delete all the files in the project.

![Menu selected for the index file and the Delete button shown in red.](images/11_delete_files.png)

You can now drag and drop all your build files into your repl.it project.

![The Build, TemplateData, and index.html files and folders shown in repl.it.](images/12_drag_drop_files.png)

Click on the **Run** button and you should see your game running in the output window.

![Game url shown in the output window.](images/13_game_url.png)

At the top of the output window, you will see a URL. This is the URL of your game; you can share this with people.

<div>
  <iframe allowtransparency="true" width="500" height="400" src="https://sharegame.marcscott.repl.co/" frameborder="0"></iframe>
</div>






