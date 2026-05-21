# Kneipenquiz

Repo-lokale Beamer-Präsentation inklusive aller verwendeten Bild-Assets.

## Struktur

- `quiz.tex` – komplette Präsentation
- `antwortboegen.tex` – druckbare Antwortzettel, eine Seite pro Runde
- `assets/brauereien/` – Bildfragen Runde 1
- `assets/bilderraetsel/` – Bildfragen Runde 2
- `assets/gametrivia/` – Bildfragen Runde 2
- `assets/memes/` – Bildfragen Runde 3
- `assets/sources/tierquiz.pdf` – Quell-PDF für Tierfragen

## Kompilieren

Empfohlen mit einer üblichen LaTeX-Installation:

```bash
pdflatex quiz.tex
pdflatex quiz.tex
```

Falls du lieber `latexmk` nutzt:

```bash
latexmk -pdf quiz.tex
```

## Hinweise

- Die Bilddateien liegen absichtlich im Repo und werden über relative Pfade eingebunden.
- Falls du Design oder Font später näher an deine erste Skizze bringen willst, ist das nur ein Styling-Thema; die Inhalte und Pfade sind jetzt sauber gekapselt.
