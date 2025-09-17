# Raspberry Pi 4b Webconfiguration

Der Raspberry Pi 4b mit der Open-WRT installation lässt sich einfach auch über eine Weboberfläche konfigurieren. Das ist nicht besonders schwer, sollte aber in jedem Fall eigentlich nicht nötig sein.

> **Für alle die sich nicht damit auskennen**: Lasst es bitte ab diesem Punkt, es ist kein Spielzeug!

## Anwendungsfälle der Weboberfläche

Es gibt nicht viele Fälle, wo diese Oberfläche zum Einsatz kommt. Sie sollte eigentlich für die nächsten Jahre so bleiben können, wie sie ist, ohne angefasst werden zu müssen. Einige Ausnahmen gibt es jedoch trotzdem:

- IP-Addressen finden oder ändern

Mehr als diese Anwendungfälle sind auch in dieser Anleitung nicht aufgeführt, bitte nutzt für die erweiterte Nutzung die Anleitung direkt von Open-WRT zur Hilfe: <https://openwrt.org/docs/start>

## Login in die Weboberfläche

Der Raspi hat die IP-Addresse <http://192.168.1.1>. Beim Aufruf dieser Addresse sollte dann dieses Fenster auftauchen.

![OpenWRT Login Bildschirm. Das Hauptfenster zeigt ein Login-Formular mit dem Titel OpenWRT und zwei Eingabefeldern für Benutzername und Passwort. Der Benutzername ist root und das Passwortfeld ist leer. Rechts unten befindet sich ein grüner Login-Knopf. Die Umgebung ist schlicht und funktional, ohne ablenkende Elemente. Die Stimmung ist neutral und sachlich. Text im Bild: OpenWRT, Benutzername, Passwort, root, Login.](/static/openwrt/openwrt-login.png)

Die login-Daten sind sehr einfach. Der Nutzername bleibt so wie er da schon ist: `root`. Das Passwortfeld wird leer gelassen. Durch das Bestätigen mit der Enter-Taste oder dem grünen Knopf kann sich eingeloggt werden.

Nun sollte diese Startseite erscheinen:

![OpenWRT dashboard interface showing navigation menu on the left with options like Status, System, Network, and Logout. Main area displays system information including hostname, model, firmware version, and uptime. Layout is clean and functional with a neutral, professional tone. Text in the image includes OpenWRT, Status, System, Network, Logout, Hostname, Model, Firmware Version, and Uptime.](/openwrt/openwrt-dashboard.png)

Von hieraus sollten alle Konfigurationsoptionen erreichbar sein.
