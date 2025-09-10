# Raspberry Pi 4b

Auf diesem Gerät ist OpenWRT installiert. Dies ist der Router für die Hausmeistersteuerung ist zuständig für die Vergabe der IP-Adressen. Hier kommt auch das Internet aus NSW-Stage her.

## Aufgaben

Wie oben schon erwähnt ist diese Raspberry dafür da, die IP-Adressen im NSW-Stage WLAN zu vergeben. Außerdem ist hier ein USB-LAN (RJ-45) Adapter angeschlossen. Über diesen Adapter kommt das Internet was Herr Hortmeyer sehr großzügig von Daniel organisiert hat rein. Wen dieser Adapter nicht richtig stecken sollte oder ausgefallen ist, fällt das Gerät auf eine Verbindung mit dem WLAN NSW-Technik zurück. Dadurch ist ein totaler Ausfall unwahrscheinlich.

## Erscheinungen bei Ausfall

Die Auswirkungen des Ausfalls dieses Geräts sind vielfältig und manchmal schwer zu diagnostizieren. Fehler die auftreten könnten sein:

- Keine Verbindung mit dem WLAN mehr möglich
- Home Assistant nicht erreichbar
- Kein Internet im NSW-Stage WLAN

Das am häufigsten Auftretende Symptom ist das Fehlschlagen der Verbindung mit dem WLAN. Häufig gibt das Tablet dann die Meldung, dass die Konfiguration der IP-Adresse fehlgeschlagen sei.
