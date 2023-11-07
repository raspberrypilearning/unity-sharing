## Unity projecten delen

Wanneer je project af is, kun je het delen met je vrienden of familie.

Als dit de eerste keer is dat je een project deelt, moet je je build-instellingen wijzigen.

Klik op het **File** menu en selecteer **Build Settings...**.

![File menu geselecteerd en Build settings gemarkeerd.](images/1_file_build_settings.png)

Selecteer in het volgende scherm **WebGL** en klik op de optie **Install with Unity Hub**.

![WebGL optie geselecteerd en de Install with Unity Hub knop gemarkeerd.](images/2_install_webgl.png)

Klik in het volgende scherm op de knop **Install** en wacht tot de WebGL-module is geïnstalleerd.

![Add modules scherm met Install button gemarkeerd.](images/3_add_modules.png)

Zodra de module geïnstalleerd is, kun je Unity Hub sluiten en daarna Unity sluiten en opnieuw starten.

Nadat Unity opnieuw is geopend, controleer je of de **Build Settings...** in het **File** menu zijn bijgewerkt en dat WebGL is geïnstalleerd. Klik vervolgens op de knop **Player Settings...**.

![Build settings venster wordt weergegeven met de WebGL opties gemarkeerd en de Player Settings knop gemarkeerd.](images/5_webgl_installed.png)

Selecteer in het menu Player aan de linkerkant in het inklapbare menu voor Publishing Settings, **Disabled** bij de Compression Format opties.

![Project setting window met het Player menu gemarkeerd en de Compression format ingesteld op Disabled en gemarkeerd.](images/6_disable_compression.png)

Sluit het settings venster en klik vervolgens op de **Build and Run** -knop, en kies vervolgens waar je je project wil opslaan. Dit duurt een paar minuten tijdens je eerste run, maar zal sneller zijn bij volgende builds.

![Build And Run knop gemarkeerd in het Build Settings menu.](images/7_build_run.png)

Je game zou automatisch moeten openen in je standaard webbrowser en speelbaar moeten zijn.

![De WebGL-speler wordt weergegeven met een spel dat draait.](images/8_webgl_player.png)

Om jouw project te delen, moet je het uploaden naar een webserver. Er zijn veel manieren om dit te doen, maar een van de eenvoudigste is om [repl.it](https://replit.com) te gebruiken.

Open repl.it in je webbrowser en meld je aan of maak een account aan als je er nog geen hebt.

![Create repl knop.](images/9_create_repl.png)

Kies om een **HTML, CSS, JS** project te maken, geef je project dan een naam en klik op de **Create Repl** knop.

![Het html-, css-, js-menu voor het maken van een nieuwe repl.](images/10_html_repl.png)

Gebruik het menu met drie stippen om alle bestanden in het project te verwijderen.

![Menu geselecteerd voor het index bestand en de Delete knop in rood weergegeven.](images/11_delete_files.png)

Je kunt nu al je build-bestanden naar je repl.it-project slepen en neerzetten.

![De Build, TemplateData en index.html bestanden en mappen die worden weergegeven in repl.it.](images/12_drag_drop_files.png)

Klik op de knop **Run** en je zou je spel in het output window moeten zien draaien.

![Spel url weergegeven in het uitvoervenster.](images/13_game_url.png)

Aan de bovenkant van het output window zie je een URL. Dit is de URL van je spel; je kunt deze delen met andere mensen.

<div>
  <iframe allowtransparency="true" width="500" height="400" src="https://sharegame.marcscott.repl.co/" frameborder="0"></iframe>
</div>






