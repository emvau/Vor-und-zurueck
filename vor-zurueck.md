# Maqueen Plus V2 – Vorwärts und Rückwärts @tutorial
##  @fullscreen

In diesem Programm fährt der Maqueen Plus V2 Roboter
4 Mal vorwärts und rückwärts!
##  
Füge einen ``||maqueenPlusV2:initialisiere Maqueen Plus V2||`` Block
in den ``||basic:beim Start||`` Block ein.
Dieser Block muss immer am Anfang stehen,
damit der Roboter richtig funktioniert.
##  
Füge einen ``||loops:4 mal wiederholen||`` Block
unter den ``||maqueenPlusV2:initialisiere Maqueen Plus V2||`` Block ein.
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

