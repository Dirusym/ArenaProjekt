# Game Maker "ArenaProjekt"
#####Ordner-Strukturen und Bedeutungen
1. GameSprite Ordner -> Alle nutzbaren Sprites für das Game !
2. Projekt Ordner -> Alle Dateien für Game Maker ! **(Pfad: C:\Users\Lenovo Z50-70\Documents\GameMaker\Projects\ )**
3. README.md -> Aktueller Stand der Dinge immer aufschreiben !
4. PS. Falls man den GameSprite Ordner erweitern will bitte auch in dem Changelog erwähnen :)
5. Changelogs immer __über__ dem letzten schreiben !

#####Changelog *09.03.17 21.23*
-Github Projekt eröffnet und Dateien eingefügt !

#####*10.03.17 13.15*
-Kollisionsabfrage und Bewegungsscript Änderungen unter Party Game.gmx.7z

#####*10.03.17 15.34*
1. -Alle Prozesse in Scripts umgewandelt, entsprechende Beschreibung in den jeweiligen Objekten und Scripts
2. -Zoomfix -> Jetzt kann jeder Player mit dem "x"-Button rauszoomen und bewegt sich dabei nicht.
3. -ZoomProblem -> Beim 2ten Player zoomt er etwas zu weit raus !

#####*10.03.17 21.46*
1. -Neuer Ordner in Sprites -> Player (Dort ist die Kanone und der Körper !)
2. -Die Kanone wird in obj_Player im DrawEvent gezeichnet !

#####*14.03.17 01.11*
1. -Den ersten Room in Level01 benannt und nen Background Ordner für die Level erstellt 
2. -Level Größe immer auf 2048x2048 ! (Da sonst Bugs auftreten wegen Zoom !)
3. -Feste Spawntpunkte in den Ecken der Map platziert !
4. -WaffenSpawn Prototype platziert !

#####*15.03.17 01.58*
1. -Neue Sprites ! Player 1 = Rot || Player 2 = Blau !
2. -Farbkleckse hinzugefügt ! Player hinterlässt nun Kleckse auf dem Boden (Derzeit nur Rot) !

#####*03.05.17 18.18*
1. -Hook hinzugefügt !
   ->Folgende Probleme gibt es:
   ->>Wenn man die Hook startet, spawnt ein Teil der Kette rechts neben dem Spieler !
   ->>Wenn man nach oben und unten schaut und die Hook startet, kommt sie nicht aus der Waffe, sonder etwas versetzt !
   ->>Wenn man an der Wand steht und auf die Wand die Hook startet, buggt sich der Spieler in die Wand !
2. WaffenSpawn (Primitiv)
   ->Man kann nun auf das Waffenterminal und die Waffe wird derzeit nur verändert ! (Aussehen)
   
#####*09.05.17 23.39*
1. ->Neue Hook mit einem neuen Script, alte Sachen wurden gelöscht !
2. ->Kette funktioniert nicht ganz, werde mich drum kümmern ;)
   
   
   
