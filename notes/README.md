# StudyOS — Notizen-Abgleich

Die Dateien in diesem Ordner werden beim Laden von `studyos.html` automatisch mit der App abgeglichen (Repo → Browser):

- Fehlt eine Notiz lokal (z. B. weil sie in der App gelöscht wurde), wird sie aus dem Repo **wiederhergestellt**.
- Ist die Repo-Version **neuer** (`updated`-Datum im Frontmatter), überschreibt sie die lokale Version.
- Lokale Bearbeitungen mit neuerem Datum bleiben erhalten.

## Neue Notiz hinzufügen

1. `.md`-Datei in den passenden Fach-Ordner legen (`Chemie/`, `Physik/`, `Mathe/` — neue Fächer einfach als Ordner anlegen).
2. Den Pfad in `manifest.json` eintragen, z. B. `"Chemie/Neues Thema.md"`.

Frontmatter ist optional — ohne Frontmatter wird der Dateiname als Titel und der Ordnername als Fach verwendet:

```markdown
---
title: "Neues Thema"
subject: "Chemie"
tags: ["tag1", "tag2"]
difficulty: "mittel"
updated: "2026-07-04"
---

# Inhalt hier…
```

Hinweis: Der Abgleich funktioniert nur, wenn die Seite über einen Server läuft (GitHub Pages, `python -m http.server`, …) — beim direkten Öffnen der Datei (`file://`) wird er still übersprungen.
