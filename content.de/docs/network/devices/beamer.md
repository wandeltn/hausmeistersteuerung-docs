# Beamer

Der Beamer ist auch im Netzwerk und wird durch dieses auch gesteuert.

## Steuerung

Für diesen Beamer spezifisch gibt es keine direkte Anleitung, wie man ihn programmatisch steuert. Er hat eine Weboberfläche durch die der Beamer graphisch einstellbar ist, wie auf der Fernbedienung. Dies ist für die meisten Nutzer ausreichend. Bitte nutzt, wenn ihr nicht gerade etwas automatisieren wollt, diese Möglichkeit.

### Steuerung per Weboberfläche

Hierzu wird nur die IP-Adresse des Beamers in den Browser eingegeben und aufgerufen. Dann sollte schon die Oberfläche zur Steuerung des Beamers auftauchen. Diese erscheint auch, wenn der Beamer ausgeschaltet sein sollte. Vorsicht mit den Einstellungen, nicht alles sollte verändert werden, besonders nicht die Netzwerkeinstellungen oder die Keystone Einstellungen. Die passen eigentlich so wie sie sind.

### Steuerung per Telnet

Der Beamer hat auf Port 23 eine Schnittstelle für Telnet. Über diese Schnittstelle können simple Anweisungen gesendet werden. Diese werden dann wie mit dem Drücken der Fernbedienung ausgeführt. Leider gibt es für die sämtlichen Befehle keine Bestätigung der Ausführung. Das heißt, das muss man sich ein bisschen aus den verschiedenen Befehlen zusammenbauen. Für das Ein- und Ausschalten ist folgender Ablauf geplant gewesen:

1. Kommando für Ein/Aus senden
2. Kommando für Ein/Aus Status senden und Rückgabe prüfen
3. 2 Wiederholen, bis zum gewünschten Status
4. Bestätigung erfolgt

Optimal ist der Ablauf nicht. Wenn dieser Ablauf von jemandem verbessert werden kann, würde ich mich sehr freuen. Bitte dann jedoch auch diese Anleitung editieren, damit diese auf dem neusten Stand bleibt.