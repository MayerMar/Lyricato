# Datenschutzerklärung — Lyricato

*Stand: 6. Mai 2026*

## Über die App

Lyricato ist eine Begleit-App, die zu der gerade auf dem Gerät abgespielten
Musik die zugehörigen Liedtexte (Lyrics) anzeigt. Lyricato spielt selbst keine
Musik ab.

## Datenerhebung

Lyricato erhebt **keine personenbezogenen Daten**. Es gibt kein Nutzerkonto,
keine Anmeldung, keine Werbe-Tracker und keine Analytics-Frameworks.

## Was wird übertragen

Um Lyrics zu finden, sendet die App **Liedtitel, Künstlername, Albumname und
Songdauer** an folgende externe Dienste:

- **lrclib.net** (Community-Lyrics-API)
- **music.163.com** (NetEase Cloud Music, Fallback-Quelle)

Diese Übertragung erfolgt verschlüsselt über HTTPS. Es werden keinerlei
Personen-Identifikatoren mitgesendet (keine IP-Logs durch uns, kein Account-
Bezug, keine Geräte-IDs).

## Was wird lokal gespeichert

Geladene Lyrics werden in einem lokalen Cache (Room-Datenbank) auf dem Gerät
gespeichert, um Lyrics offline und schneller verfügbar zu machen. Diese Daten
verlassen das Gerät nicht und werden bei Deinstallation der App vollständig
entfernt.

## Berechtigungen

Lyricato benötigt die Berechtigung **„Mitteilungszugriff"
(BIND_NOTIFICATION_LISTENER_SERVICE)**, um die aktuell auf dem Gerät
abgespielte Musik zu erkennen (Künstler/Titel über die System-MediaSession).
Es werden keine Notification-Inhalte ausgelesen, gespeichert oder weiter-
geleitet — die Berechtigung ist technisch notwendig, um Drittanbieter-Player
wie Spotify auszulesen.

Zusätzlich benötigt die App **Internetzugriff**, um die externen Lyrics-
Dienste anzusprechen.

## Kontakt

Bei Fragen zum Datenschutz: **mailtomayer@gmail.com**

## Änderungen

Änderungen an dieser Datenschutzerklärung werden auf dieser Seite
veröffentlicht.
