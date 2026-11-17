# Verdingkinder – Zeugnisse

Statische Website über Verdingkinder in der Schweiz: eine Übersicht mit Porträts von Zeuginnen und Zeugen,
pro Person ein Link zu ihrer Geschichte.

## Dateien

| Datei | Inhalt |
|---|---|
| `index.html` | Übersicht mit Einführung und Personenkarten |
| `person.html` | Geschichte einer Person (`person.html?id=…`) |
| `zeugen.js` | **Alle Inhalte** – hier werden Personen eingetragen |
| `style.css` | Gestaltung |
| `bilder/` | Porträtfotos |

## Neue Person hinzufügen

1. Foto in `bilder/` ablegen (Hochformat 3:4).
2. In `zeugen.js` einen Eintrag kopieren und ausfüllen (`id` eindeutig, nur Kleinbuchstaben/Bindestriche).

Die aktuellen Einträge sind Platzhalter. Bitte nur Zeugnisse mit Einverständnis, geklärten Bildrechten und Quellenangabe veröffentlichen.

## Lokal ansehen

```bash
python3 -m http.server 8000
```

Dann http://localhost:8000 öffnen.

## Veröffentlichen

Jeder Push auf `main` veröffentlicht die Seite automatisch (Workflow `.github/workflows/pages.yml`).
Falls es nicht klappt: GitHub → Settings → Pages → Source: «GitHub Actions».

Adresse: https://schlaef.github.io/test_verding/
