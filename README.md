# Thesis Template

LaTeX-Vorlage für Abschlussarbeiten. Angelehnt an die Vorgaben der Sektion MINT der Uni Lübeck.

Mit Inspiration von: [Kompiliertes PDF](https://malteschmitz.github.io/latex-thesis/thesis.pdf)

Es handelt sich _nicht_ um eine offizielle Vorlage. Ob diese Vorlage eventuell vorhandenen Gestaltungsvorgaben entspricht, ist im Zweifelsfall mit den jeweils zuständigen Institutionen abzusprechen.


Zur Nutzung in VS Code:
Erweiterungen: LaTeX Workshop

In die Preferences: Open Settings (JSON):

    "latex-workshop.latex.recipes": [
        {
            "name": "pdflatex ➞ bibtex ➞ pdflatex × 2",
            "tools": ["pdflatex", "bibtex", "pdflatex", "pdflatex"]
        }
    ]
