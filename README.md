# Geschmackstagebuch

Private Bewertungs-App als PWA. Alle Daten bleiben lokal auf dem Gerät (IndexedDB).

## Installieren (GitHub Pages)
1. Auf github.com ein neues **öffentliches** Repository anlegen, z. B. `geschmackstagebuch`.
2. „uploading an existing file" → alle Dateien aus diesem Ordner hochladen → Commit.
3. Settings → Pages → Source: „Deploy from a branch", Branch `main`, Ordner `/ (root)` → Save.
4. Nach 1–2 Minuten ist die App unter `https://<dein-name>.github.io/geschmackstagebuch/` erreichbar.
5. Am Android-Handy in **Chrome** öffnen → Menü ⋮ → **„App installieren"** (bzw. „Zum Startbildschirm hinzufügen").

## Updates
Geänderte Dateien hochladen und in `sw.js` die Versionsnummer (z. B. `geschmackstagebuch-v2` → `v3`) erhöhen.
Die App holt sich die neue Version beim nächsten Öffnen mit Internet. Deine Daten bleiben erhalten.

## Backup
In der App oben rechts ⇅ → „Backup-Datei (JSON)". Am besten in Google Drive speichern.
Wichtig: Chrome-Websitedaten löschen oder die App deinstallieren löscht auch die Daten.
