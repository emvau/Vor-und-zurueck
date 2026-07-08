# Maqueen Plus V2 – Vorwärts und Rückwärts @tutorial
##  @fullscreen

In diesem Programm fährt der Maqueen Plus V2 Roboter
4 Mal vorwärts und rückwärts!
Zuerst musst du die Erweiterung **maqueenPlusV2** installieren.
Klicke links unten auf **Erweiterungen**.
Suche nach **maqueenPlusV2** und klicke darauf, um sie zu installieren.
##  
Füge einen ``||maqueenPlusV2:I2C initialisieren||`` Block
in den ``||basic:beim Start||`` Block ein.
Dieser Block muss immer am Anfang stehen,
damit der Roboter richtig funktioniert.
##  
Füge einen ``||loops:4 mal wiederholen||`` Block
unter den ``||maqueenPlusV2:I2C initialisieren||`` Block ein.
##  
Füge in den ``||loops:4 mal wiederholen||`` Block
einen ``||maqueenPlusV2:Motor steuern||`` Block ein.
Stelle folgendes ein:
- Motor: **Alle Motoren**
- Richtung: **Vorwärts**
- Geschwindigkeit: **255**
##  
Füge danach einen ``||basic:pausiere (ms)||`` Block ein.
Stelle die Zeit auf **1000** ms (= 1 Sekunde).
##  
Füge einen weiteren ``||maqueenPlusV2:Motor steuern||`` Block ein.
Stelle folgendes ein:
- Motor: **Alle Motoren**
- Richtung: **Vorwärts**
- Geschwindigkeit: **-255**
Die negative Geschwindigkeit lässt den Roboter **rückwärts** fahren!
##  
Füge nochmal einen ``||basic:pausiere (ms)||`` Block ein.
Stelle die Zeit wieder auf **1000** ms.
##   @fullscreen
Fertig! 🎉
Lade das Programm auf deinen micro:bit herunter
und lege ihn in den Maqueen Plus V2 ein.
Der Roboter fährt jetzt 4 Mal vorwärts und rückwärts! 🤖


        
Und hier die passende pxt.json:

JSON

Kopieren
{
    "name": "Maqueen Plus V2",
    "description": "Ein MakeCode Tutorial für den Maqueen Plus V2 Roboter",
    "dependencies": {
        "microbit": "*",
        "maqueenPlusV2": "github:DFRobot/pxt-maqueen-plus-v2"
    },
    "files": [
        "maqueen.md"
    ],
    "targetVersions": {
        "target": "7.0.0"
    }
}
⚠️ Wichtig: Bei Erweiterungen muss der genaue GitHub-Pfad in der pxt.json stehen. Falls github:DFRobot/pxt-maqueen-plus-v2 nicht stimmt, schau im MakeCode-Editor nach dem genauen Namen der Erweiterung! 😊





MV
Monika Veismann
Der Link heißt https://github.com/DFRobot/pxt-DFRobot_MaqueenPlus_v20
avatar
claude-4-6-sonnet
Danke! Dann muss die pxt.json so aussehen:

JSON

Kopieren
{
    "name": "Maqueen Plus V2",
    "description": "Ein MakeCode Tutorial für den Maqueen Plus V2 Roboter",
    "dependencies": {
        "microbit": "*",
        "maqueenPlusV2": "github:DFRobot/pxt-DFRobot_MaqueenPlus_v20"
    },
    "files": [
        "maqueen.md"
    ],
    "targetVersions": {
        "target": "7.0.0"
    }
}
Der Roboter fährt jetzt 4 Mal vorwärts und rückwärts! 🤖






