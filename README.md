# Offline Update Manager – Programm-Testversionen

Dieser **öffentliche** GitHub-Kanal enthält ausschließlich vorab geprüfte,
portable **Programm-Testpakete** für den Offline Update Manager.

**Kein Entwicklungsquellcode-Repository, keine Kundendaten, keine Inventuren,
keine Microsoft-Paketbestände und keine gespeicherten Zugangsdaten.**

## Versionen

Freigegebene Testversionen werden als **GitHub Pre-Releases** bereitgestellt.
Jedes Release enthält unter **Assets**:

- `Offline-Update-Manager-v<version>.zip` – portabler Programmordner
- `Offline-Update-Manager-v<version>.zip.sha256` – separater SHA-256-Beleg

Die von GitHub erzeugten `Source code (zip)`-/`tar.gz`-Archive
sind **keine** Offline-Update-Manager-Programmversionen.

Bei Internetverbindung prüft die GUI im Hintergrund auf neue
Testversionen. Nur Programmdateien werden aktualisiert; die alte
Programmversion wird als Backup gesichert, und
`Offline-Update-Manager-Daten` bleibt unverändert.

**Veröffentlichungsprüfung:** PowerShell-Programm-ZIPs enthalten
lesbare Skripte. Vor dem öffentlichen Upload müssen die enthaltenen
Dateien auf Vertraulichkeit, Veröffentlichungserlaubnis und Lizenzen
geprüft werden.

Es handelt sich um einen **Alpha-/Teststand**, nicht um eine Freigabe
für unbeaufsichtigte Kundeninstallationen.
