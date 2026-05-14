# Poster_LGBIO1113

## Description

This repository contains the academic poster created for the course **LGBIO1113 — Anatomie et physiologie des systèmes** at UCLouvain. The poster covers the topic of **acute bronchiolitis in infants** (*bronchiolite aiguë du nourrisson*), including its anatomy, pathophysiology, symptoms, treatments, respiratory physiotherapy, and medical imaging (CT scan).

Authors: Julian Belotti, Guillaume Deside, Anaïs Volondat (Groupe 3)

## Building the Poster

The poster is written in LaTeX using the `baposter` class. To compile it you need a LaTeX distribution (e.g. TeX Live or MiKTeX) with the following packages: `wrapfig`, `lmodern`, `babel` (French), `graphicx`, `geometry`, `ragged2e`, `setspace`, `caption`.

```bash
pdflatex main.tex
```

The output is `main.pdf`.

## Repository Structure

```
Poster_LGBIO1113/
├── main.tex              # Main LaTeX source file
├── baposter.cls          # Baposter document class
├── poster_LGBIO1113.pdf  # Compiled poster (PDF)
├── images/               # Figures and logos used in the poster
└── README.md
```