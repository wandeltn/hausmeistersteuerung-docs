---
title: 2FA hinzufgen
description: 
published: true
date: 2026-01-05T15:54:07.757Z
tags: 
editor: markdown
dateCreated: 2026-01-05T15:54:07.757Z
---

# 2-Faktor Authentifizierung hinzufügen

Für diejenigen, denen die Sicherheit ihres Account sehr am Herzen liegt wäre es empfehlenswert 2FA einzurichten. Damit wird sichergestellt, dass wenn jemand dein Passwort bekommt, er sich weiterhin nicht in dein Account einloggen kann. 

## Welche Methoden werden unterstützt?

Es werden diverse Methoden zur Zweifaktorauthentifizierung von Authentik angeboten. Dazu gehören zum Beispiel die folgenden:

- E-Mail
- TOTP
- Yubikey
- WebAuthn

Für mehr Information zu den unterstützten Methoden, schaue doch einfach mal auf der Website von Authentik vorbei: 

<https://goauthentik.io/blog/2025-03-05-mfa-in-authentik/>

## Wie kann ich eine Methode hinzufügen?

Die Einrichtung der Methoden ist sehr einfach. Besuche einfach einen der folgenden Links um deine passende Methode einzurichten.

- [Statische Tokens](https://auth.wandelt.party/if/flow/default-authenticator-static-setup/?next=%2Fif%2Fuser%2F%23%2Fsettings%3B%7B%22page%22%3A%22page-mfa%22%7D&inspector=available)
- [Time Based One-time Password (TOTP)](https://auth.wandelt.party/if/flow/default-authenticator-totp-setup/?next=%2Fif%2Fuser%2F%23%2Fsettings%3B%7B%22page%22%3A%22page-mfa%22%7D&inspector=available)
- [WebAuthn](https://auth.wandelt.party/if/flow/default-authenticator-webauthn-setup/?next=%2Fif%2Fuser%2F%23%2Fsettings%3B%7B%22page%22%3A%22page-mfa%22%7D&inspector=available)
{.links-list}

Wenn diese Links nicht funktionieren sollten, versuche bitte manuell zu der entsprechenden Stelle zu navigieren:

![authentik-user-settings.png](/authentik-user-settings.png)

![authentik-user-settings-mfa.png](/authentik-user-settings-mfa.png)

![authentik-mfa-enroll.png](/authentik-mfa-enroll.png)

Nach diesen drei Schritten kannst du nun eines der Möglichkeiten auswählen. Die nächsten Schritte werden dir auf der jeweiligen Seite erklärt.