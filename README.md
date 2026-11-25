# National League – Resultate 🏒

Windows-Desktopanwendung für Resultate, Spielverlauf und die Tabelle der Schweizer National League.

## Aktueller Hinweis zur Datenverfügbarkeit (25. November 2026)

**Die SIHF hat den öffentlichen Zugriff auf die bisherige Statistik-API eingestellt.**
Der Server liefert für Resultate und Tabellen HTTP 403 mit dem Hinweis,
dass der öffentliche Zugriff nicht mehr verfügbar ist. **Dadurch kann
NL Resultate derzeit keine aktuellen Resultate, Tabellen oder
Spielverläufe aus dieser Quelle anzeigen.** Eine freigegebene Ersatzdatenquelle
ist noch nicht eingebunden.

Seit **v2.3.3** zeigt die App den Grund verständlich an und stoppt
automatische Wiederholungsabfragen, wenn die Sperre festgestellt wird.
Diese Version behebt **nicht** die Daten-Sperre.

Für die Bereitstellung eines berechtigten SIHF-Zugangs verweist die
SIHF ausdrücklich an **support@sihf.ch**.

Dieses Repository stellt **öffentliche Downloads und Lizenzhinweise** bereit. Das vollständige Entwicklungsrepository bleibt privat. Die veröffentlichten Update-Pakete und Installationen enthalten allerdings lesbare Python-Laufzeitdateien (`.py`).

## NL Resultate herunterladen

**[Aktuelle Version herunterladen](https://github.com/ChuchiiChaestlii/NL_Resultate_public/releases/latest)** – dort die Datei **`NL_Resultate_vX.Y.Z_Setup.exe`** auswählen.

**Aktuelle Version v2.3.3:** [Setup.exe direkt herunterladen](https://github.com/ChuchiiChaestlii/NL_Resultate_public/releases/download/v2.3.3/NL_Resultate_v2.3.3_Setup.exe). Für spätere Versionen immer den Link **Aktuelle Version herunterladen** verwenden.

Der Installer ermöglicht eine frei wählbare Installation und die reguläre Deinstallation über Windows-Einstellungen.

**Voraussetzung:** Windows 10/11. Falls **Python 3.10 oder neuer** bereits vorhanden ist, wird es automatisch weiterverwendet.

**Neu ab v2.3.2:** Wenn Python auf einem 64-Bit-Windows-PC fehlt, fragt das Setup nach, ob es den **offiziellen Python-3.13.12-Installer** von `python.org` herunterladen (ca. 28 MB) und für den aktuellen Benutzer installieren soll. Die Python-Datei wird anhand einer SHA-256-Prüfsumme geprüft. Der Download ist **freiwillig**, benötigt Internet und erfolgt nicht ohne ausdrückliche Zustimmung. Die Setup.exe bleibt selbst etwa 2,15 MB gross.

Python ist eine eigenständige Installation und bleibt bestehen, wenn du NL Resultate deinstallierst. Unter 32-Bit-Windows muss ein passendes Python gegebenenfalls vorher separat installiert werden.

## Automatische Updates

Nach der Installation prüft die Anwendung auf neue **öffentliche Releases**. Zum Herunterladen ist **kein GitHub-Konto, Git, GitHub CLI oder eigener Token** notwendig.

- `NL_Resultate_vX.Y.Z_Setup.exe`: Windows-Installer für die Erstinstallation
- `NL_Resultate_vX.Y.Z.zip`: Update-Paket, das die App automatisch überprüft und installiert
- Jede Veröffentlichung enthält ein deutschsprachiges Changelog mit den Änderungen.

Der Update-Mechanismus überprüft die Version, die erwartete Dateigrösse, die von GitHub angegebenen SHA-256-Prüfsummen und die erlaubten Paketdateien, bevor er ein Update installiert.

> Seit **v2.3.0** ist der öffentliche Download- und Update-Kanal aktiviert. Neue Versionen erscheinen hier nach erfolgreicher Prüfung und Veröffentlichung über GitHub Actions.

## Lizenz

**MIT License – Copyright (c) 2026 ChuchiiChaestlii**

Du darfst NL Resultate und den eigenen Programmcode **kostenlos
verwenden, kopieren, verändern und weitergeben**, ohne um Erlaubnis zu
fragen. Auch eine kommerzielle Nutzung ist erlaubt. Bei einer
Weitergabe musst du den Copyright- und Lizenzhinweis beibehalten.

- [MIT-Lizenztext](LICENSE)
- [Hinweis zu Vereinslogos und Grafiken](ASSET_RIGHTS.md)

**Wichtig:** Die MIT-Lizenz umfasst keine Rechte Dritter an
SIHF-/Vereinslogos, Namen oder Marken. Bei veränderten Versionen
müssen solche Rechte separat beachtet werden. Der Quellcode im privaten
Entwicklungsrepository wird durch die Lizenz nicht automatisch als
GitHub-Repository öffentlich veröffentlicht.

## Datenquelle

Resultate und Tabelleninformationen stammen aus der SIHF-Statistik. Vereinslogos und weitere Bezeichnungen gehören den jeweiligen Rechteinhabern.
