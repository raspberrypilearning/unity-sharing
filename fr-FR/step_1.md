## Partager des projets Unity

Lorsque ton projet est terminé, tu peux le partager avec tes amis ou ta famille.

Si c'est la première fois que tu partages un projet, tu dois modifier tes paramètres de build.

Clique sur le menu **File** et sélectionne **Build Settings...**.

![Menu File sélectionné et Build Settings en surbrillance.](images/1_file_build_settings.png)

Sur l'écran suivant, sélectionne **WebGL** et clique sur l'option **Install with Unity Hub**.

![Option WebGL sélectionnée et bouton Install with Unity Hub en surbrillance.](images/2_install_webgl.png)

Sur l'écran suivant, clique sur le bouton **Install**, puis attends que le module WebGL soit installé.

![Écran Add modules avec le bouton Install en surbrillance.](images/3_add_modules.png)

Une fois le module installé, tu peux fermer Unity Hub, puis fermer Unity et le redémarrer.

Une fois Unity rouvert, vérifie que **Build Settings...** du menu **File** a été mis à jour, et montre que WebGL a été installé. Clique ensuite sur le bouton **Player Settings...**.

![La fenêtre Build Settings s'affiche avec les options WebGL en surbrillance et le bouton Player Settings en surbrillance.](images/5_webgl_installed.png)

Dans le menu Player sur la gauche, dans le menu déroulant pour Publishing Settings, sélectionne **Disabled** dans les options Compression Format.

![Fenêtre Project setting avec le menu Player en surbrillance et Compression format défini sur Disabled et en surbrillance.](images/6_disable_compression.png)

Ferme la fenêtre des paramètres, puis clique sur le bouton **Build And Run**, puis choisis où tu souhaites enregistrer ton projet créé. Cela prendra quelques minutes lors de la première exécution, mais sera plus rapide pour les builds suivants.

![Bouton Build And Run mis en surbrillance dans le menu Build Settings.](images/7_build_run.png)

Ton jeu devrait s'ouvrir automatiquement dans ton navigateur Web par défaut et être jouable.

![Le lecteur WebGL affiché avec un jeu en cours d'exécution.](images/8_webgl_player.png)

Pour partager ton projet, tu dois le télécharger sur un serveur Web. Il existe plusieurs façons de procéder, mais l'une des plus simples consiste à utiliser [repl.it](https://replit.com).

Ouvre repl.it dans ton navigateur Web et connecte-toi ou crée un compte si tu n'en as pas.

![Bouton Create repl.](images/9_create_repl.png)

Choisis de faire un projet **HTML, CSS, JS**, puis donne un nom à ton projet et clique sur le bouton **Create Repl**.

![Le menu html, css, js pour créer un nouveau repl.](images/10_html_repl.png)

Utilise les menus à trois points pour supprimer tous les fichiers du projet.

![Menu sélectionné pour le fichier d'index et le bouton Delete affiché en rouge.](images/11_delete_files.png)

Tu peux maintenant faire glisser et déposer tous tes fichiers de build dans ton projet repl.it.

![Les fichiers et dossiers Build, TemplateData et index.html affichés dans repl.it.](images/12_drag_drop_files.png)

Clique sur le bouton **Run** et tu devrais voir ton jeu en cours d'exécution dans la fenêtre de sortie.

![URL du jeu affichée dans la fenêtre de sortie.](images/13_game_url.png)

En haut de la fenêtre de sortie, tu verras une URL. Il s'agit de l'URL de ton jeu ; tu peux partager cela avec les gens.

<div>
  <iframe allowtransparency="true" width="500" height="400" src="https://sharegame.marcscott.repl.co/" frameborder="0"></iframe>
</div>






