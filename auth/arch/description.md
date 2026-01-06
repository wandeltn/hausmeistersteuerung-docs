---
title: Authentik Funktionsweise
description: 
published: true
date: 2026-01-06T08:33:54.533Z
tags: auth
editor: markdown
dateCreated: 2026-01-06T08:13:30.624Z
---

# Funktionsweise von Authentik

Authentik an sich ist nur als externe Platform zur Authenfikation zu sehen. Die Platform vereint die verschiedenen Passwortmechanismen der verschiedenen Platformen in der Hausmeistersteuerung zu einem zentralen System mit noch ein paar Extras.

Auf die genaue Funktionsweise von Authentik werde ich nicht eingehen, da es zu komplex ist um hier zu erklären. Was hier erklärt wird, ist wie dieser Idenditätsanbieter (IdP) angewendet werden kann, auch in eventuell neuen Anwendungen.

## Grundsätzliche Limitierungen

Für Authentik bestehen ein paar Limitierungen, die den Anwensungsbereich minimal einschränken. Diese finden aber in der Regel im WLAN der Hausmeistersteuerung keine Anwendung. Trotzdem werde ich sie hier nenne, damit sie zumindest bekannt.

Wenn du dich mit Authentik anmelden möchtest, musst in in dem aktuellen Netzwerk deines Geräts eine Verbindung zum Internet aufbauen können. Mit diesem Zugriff wird auf den Domain <https://auth.wandelt.party> weitergeleitet. Ohne Zugriff auf diesen Domain ist die Nutzung von Authentik nicht möglich.

Außerdem muss eine grundsätzliche Unterstützung eines externen IdPs haben. Ist dies nicht der Fall, kann es sein, dass die bestimmte App auch ein Plugin oder Add-on hat, was diese Unterstützung hinzufügen kann. Wenn dies auch nicht der Fall sein sollte, ist es wahrscheinlich, dass die Authentifizierung mit Authentik nicht möglich sein wird. 
