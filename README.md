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
