# Reved Bot
Fork von PlaceDE von PlaceNL Bot. Thanks guys!  
Der Bot für Reved und Niekbeats! Dieser Bot holt automatisch alle paar Minuten [Pläne](https://github.com/NoNamePro0/pixel), um zu verhindern, dass Bots miteinander kollidieren.

> AKTUELL KAPPUTT. WIRD GEFIXT. (hoffentlich)

## Installationsanweisungen

Überprüfe, dass gerade neue Pixel plaziert werden können und dies nicht auf Cooldown ist

1. Installiere die Browsererweiterung [Tampermonkey](https://www.tampermonkey.net/) oder [Violentmonkey (Firefox)](https://addons.mozilla.org/en-US/firefox/addon/violentmonkey/).
2. Klicke auf diesen Link: [https://github.com/NoNamePro0/Bot/raw/main/placedebot.user.js](https://github.com/NoNamePro0/Bot/raw/main/placedebot.user.js). Wenn alles gut geht, bietet Tampermonkey an, ein Benutzerskript zu installieren. Klicke auf **Installieren**.
3. Lade den **r/place** Tab neu. Wenn alles gut gegangen ist, sollte "Abfrage des Zugriffstokens..." oben rechts auf dem Bildschirm zu sehen sein. Der Bot ist nun aktiv und wird diese Benachrichtigungen oben rechts für laufende Informationen nutzen.

WICHTIG: Sollten anbleibende Verbindungsprobleme zum Server bestehen kann dies an eurem Adblocker etc. liegen!

## Schwachstellen des Bots

- Der Bot aktualisiert die Cooldown Nachricht nicht, so dass es aussieht als ob noch ein Pixel platziert werden kann. Der Bot hat das Pixel jedoch schon platziert und wartet nun auf den Cooldown.
- Der Bot berücksichtigt eine bestehende Abklingzeit nicht und geht daher davon aus, dass man sofort einen Pixel platzieren kann, wenn man **r/place** öffnet. Im schlimmsten fall gehen so 5 Minuten verloren
