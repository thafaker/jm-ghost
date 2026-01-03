# Ghost Theme JM Ghost

First push 03.01.2026

![](screenshot.png)

### Anpassungen am Dawn-Theme

## CSS-Modifikationen

| Datei | Änderung | Zweck | Code |
| :--- | :--- | :--- | :--- |
| `assets/css/general/grid.css` | `.gh-canvas` Regel überschrieben | Begrenzt Inhaltsbreite auf 800px | `.gh-canvas { grid-template-columns: ... }` |
| `assets/css/screen.css` | Neue Klassen hinzugefügt | Styling für Startseiten-Layout | `.gh-article-full { margin-bottom: 4rem; }` |
| `templates/index.hbs` | Template komplett ersetzt | Zeigt neuesten Artikel vollständig, dann Liste | [Siehe separate Datei] |
