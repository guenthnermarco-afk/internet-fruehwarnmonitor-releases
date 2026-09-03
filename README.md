# Internet-Frühwarnmonitor – Releases

Dieses Repository enthält ausschließlich veröffentlichte Installationspakete,
Versionshinweise und das kryptografisch signierte Update-Manifest des
Internet-Frühwarnmonitors.

Der Programmquellcode, lokale Messdaten und der private Signierschlüssel sind
nicht Bestandteil dieses Repositorys.

Installationspakete befinden sich unter **Releases**. Das Programm lädt das
`update-manifest.json`-Asset des jeweils neuesten Releases, wählt das zum
Betriebssystem passende Paket aus und akzeptiert das Manifest nur mit gültiger
Ed25519-Signatur.

Die Manifestkopie im Hauptzweig bleibt vorübergehend als Übergang für die
Testversionen 1.20.1 bis 1.20.4 erhalten. Aktuelle Versionen verwenden direkt
das Manifest-Asset des neuesten Releases.
