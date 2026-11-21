# National League – Resultate 🏒

Windows-Desktopanwendung für Resultate, Spielverlauf und die Tabelle der Schweizer National League.

Dieses Repository stellt **öffentliche Downloads und Lizenzhinweise** bereit. Das vollständige Entwicklungsrepository bleibt privat. Die veröffentlichten Update-Pakete und Installationen enthalten allerdings lesbare Python-Laufzeitdateien (`.py`).

## NL Resultate herunterladen

**[Aktuelle Version herunterladen](https://github.com/ChuchiiChaestlii/NL_Resultate_public/releases/latest)** – dort die Datei **`NL_Resultate_vX.Y.Z_Setup.exe`** auswählen.

Die erste öffentliche Version ist **v2.3.0**: [Setup.exe direkt herunterladen](https://github.com/ChuchiiChaestlii/NL_Resultate_public/releases/download/v2.3.0/NL_Resultate_v2.3.0_Setup.exe).

Der Installer ermöglicht eine frei wählbare Installation und die reguläre Deinstallation über Windows-Einstellungen.

**Voraussetzung:** Windows 10/11 und Python 3.10 oder neuer mit `pythonw.exe`. Die kleine Setup.exe installiert Python nicht selbst.

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
