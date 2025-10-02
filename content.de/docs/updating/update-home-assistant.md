# Aktualisierung der Hausmeistersteuerung

Etwa jeden Monat wird ein Update für die Hausmeistersteuerung verfügbar sein. Generell benötigt die Hausmeistersteuerung keine Updates. Jedoch ist es wichtig einen aktuellen Stand der Software zu bewahren, um Sicherheitslücken im Netzwerk zu vermeiden. 

## Wann ist ein Update verfügbar

Auf den IPads der Schüler und auf dem Tablet der Hausmeistersteuerung wird kein Update angezeigt. Dies ist gewollt, um ungewollte Eingriffe in das System zu verhindern. Nur die Lehrer, Niklas und Johan Kolms haben zur Zeit Zugriff auf diese Einstellung.

Wenn ein Update verfügbar sein sollte, ist dies unter dem Reiter "Einstellungen" einzusehen:

![Bild von der Einstellungen von Home Assistant. Ein Update ist verfügbar, welches oben angezeigt wird.](/images/hass/update/update_settings_overview.png)

In dem Bild sieht man als oberste Kachel, dass ein Update für die Komponente "Core" Verfügbar ist.

Dieses Update wollen wir nun durchführen. Dazu klicken wir vorerst auf das Update. Damit öffnet sich ein Fenster mit den Details zu dem Update. Diese immer sorgfältig durchlesen.

![Bild von der Detailübersicht eines Home Assistant Core Updates](/images/hass/update/update_details.png)

Bevor jedoch dieses Update durchgeführt werden kann, ist es wichtig aus Sicherheitsgründen das Backup mit dem Schalter zu aktivieren. Dadurch kann gewährleistet werden, dass wenn das Update fehlschlägt, eine funktionstüchtige Version gesichert wurde.

Wenn dieser Schalter aktiviert wurde, kann das Update nun durch das Klicken auf den Knopf "Update" duchgeführt werden. Es erscheint ein durchlaufender Fortschrittsbalken. Die Hausmeistersteuerung wird automatisch neustarten. Dies ist ein normaler Prozess. Hierdurch werden alle Lampen ausgeschaltet, die vorher auf der Bühne aktiviert waren und alle Schüler ausgeloggt. Nach dem Neustarten der Hausmeistersteuerung, kann diese normal weiter benutzt werden.
