# Raspberry Pi 5

Dieser Raspberry Pi ist das Herz der Hausmeistersteuerung. Hier ist die eigentliche Instanz von Home Assistant installiert, mithilfe die Hausmeistersteuerung umgesetzt wurde.

> In den folgenden Texten wird die Bezeichnung "Home Asssistant" auch durch das Akronym "Hass" abgekürzt.

## Erscheinungen bei Ausfall

Die Erscheinungen bei einem Ausfall dieses Teilsystems sind nicht so schwer zu unterscheiden von anderen. Einige der Symptome sind hier aufgelistet

- Tablet kann Hass nicht mehr erreichen ([Was tun?](/content.de/docs/troubleshooting/tablet.md))
- Hass ist auch durch <https://hausmeister.wandelt.party> nicht mehr erreichbar
- Andere Geräte wie der Beamer sind weiterhin erreichbar

### Hass durch externe URL nicht erreichbar

Dies ist kein eindeutiger Hinweis auf einen Ausfall von Hass, es ist nur ein Hinweis. Dieser Dienst läuft über den privaten Server von Niklas Wandelt und kann jederzeit mal nicht funktionieren. Wenn dies der Fall sein sollte, einfach mal anrufen, dann besprechen wir das weitere Vorgehen. Im Fall eines wirklichen Fehlers im System liegt es natürlich nicht an mir, sondern am Raspberry Pi oder am Netzwerk.

### Andere Geräte sind weiterhin erreichbar, nur Hass nicht

Meist liegt dies an einem lockeren Stecker. Prüfe dazu also folgende Dinge:

- Sind alle Kabel am Pi angeschlossen?
- Ist das LAN Kabel in einem POE fähigen Anschluss am Switch?
- Blinken die LEDs am Pi?
- Steckt eine SD Karte im Pi?
- Sind die PIN Header frei und nicht kurzgeschlossen?

## Was sollte am Pi angeschlossen sein?

Der Raspberry Pi ist per POE an Strom angeschlossen, das heißt, er bekommt seinen Strom über den Netzwerkanschluss. Wundere dich also nicht, wenn kein seperates Netzteil angeschlossen sein sollte. Außer diesem Netzwerkanschluss wird kein weiterer Anschluss des Pis verwendet. Bitte achte jedoch darauf, dass das LAN Kabel auch in einem **POE fähigen Anschluss** im Switch steckt.

## Systemupdates des Raspberry Pis

Etwa jeden Monat ein mal wird der Raspi sich melden, um Updates durchzuführen. Diese sind auf jeden Fall nichts schlimmes, trotzdem sollte hier in jedem Fall vorsicht geboten sein. Bei einem Update sollte die Option "Backup erstellen" vor dem Update auf jeden Fall aktiviert sein.

Um ein Update durchzuführen gilt folgender Ablauf.

1. Admin Account anmelden. Passwort und Nutzername [hier]()
2. In der linken Seitenleiste die Einstellungen öffnen
3. Wenn Updates verfügbar sein sollten, werden diese nun ganz oben aufgelistet
4. Um ein Update auszuführen, einfach auf ein Element aus der Liste klicken
5. Update Ausführen, indem man auf Bestätigen klickt. Unbedingt dazu den Hinweis aus dem obigen Text lesen.
