# Schnellstart - einen Garten zum "Internet of Gardens" hinzufügen

Melde dich bei [GitHub](https://github.com/join) an. Dann geh zum Projekt [internet-of-gardens](https://github.com/c0c0bird/mitmachgarten-laatzen) und klicke auf "Use this template".
Gib deinem neuen Repository einen Namen und stelle es auf "Public". Nachdem fertig angelegt ist, kannst du unter "Einstellungen" -> "Github Pages" den URL sehen, unter dem es veröffentlicht wurde. Die Garten-Map ist nun unter "https://[deinName].github.io/[deinProjekt]/main.json" erreicht, sieht aber noch aus wie der Vorlagengarten. Jetzt geht es ans Anpassen, um deinen Garten daraus zu machen.

Klone dein Repository auf deine Festplatte. Das geht entweder mit [GitHub Desktop](https://desktop.github.com/) oder klassisch an der Kommandozeile mit  
  git clone git@github.com:[deinName]/[deinProjekt].git

Hol dir den Editor [Tiled](https://www.mapeditor.org/), öffne damit die Datei "main.json" aus dem Projektverzeichnis. Tiled hat eine [Dokumentation](https://doc.mapeditor.org/en/stable/manual/introduction/); falls du lieber Videos schaust, probier bei Bedarf die [Tutorials](https://gamefromscratch.com/tiled-map-editor-tutorial-series/) aus.

Eine Map besteht aus beliebig vielen Ebenen von Kacheln (Tiles) auf denen Bilder aus einer Sammlung (Tileset) liegen. Jede Kachel ist 32px x 32px groß. Ein Tileset ist einfach eine PNG-Datei, in der ganze viele 32x32-Grafiken nebeneinander liegen. Die Vorlage kommt mit einigen Freeware-Tilesets, mehr davon findest du in den im Readme genannten Quellen. Eigene Tilesets kannst du mit jedem Grafikprogramm (z.B. GIMP, Krita) malen.

Um dein Werk live zu sehen, schiebe deine Änderungen zurück zu github. An der Kommandozeile geht das mit:

  git add .
  git commit -m"erster Versuch"
  git push

In ein paar Minuten erscheinen deine Änderungen in den GitHub Pages. Jetzt kannst du deinen Garten in jeder WorkAdventure-Instanz starten, etwa
* https://play.wa.binary-kitchen.de/_/global/[deinName].github.io/[deinProjekt]/main.json
* https://play.meet.n2n.io/_/global/[deinName].github.io/[deinProjekt]/main.json
* https://play.workadventu.re/_/global/[deinName].github.io/[deinProjekt]/main.json

Die vollständige Anleitung findest du bei [WorkAdventure](https://workadventu.re/map-building).
Eine umfassende Anleitung, allerdings mit Erweiterungen die es nur auf einem Event gab, liegt beim [rC3](https://howto.rc3.world/maps.html#schnell-uberblick).


