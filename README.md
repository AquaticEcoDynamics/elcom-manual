# ELCOM Manual

A Quarto book containing the ELCOM (Estuary, Lake and Coastal Ocean Model) documentation, including science description, user guide, and publication list.

## Building

Requires [Quarto](https://quarto.org/) to be installed.

```bash
quarto render --to html
```

Output is written to the `docs/` folder for GitHub Pages deployment.

## Folder Structure

```
elcom-quarto/
├── _quarto.yml                 # Book configuration (output-dir: docs)
├── index.qmd                   # Title page
├── 01-intro.qmd                # Ch 1: Introduction
├── 02-notation.qmd             # Ch 2: Notation
├── 03-sci-intro.qmd            # Ch 3: Science overview
├── 04-sci-goveqns.qmd          # Ch 4: Governing equations
├── 05-sci-timestep.qmd         # Ch 5: Timestep limitations
├── 06-sci-method.qmd           # Ch 6: Numerical method
├── 07-sci-thermo.qmd           # Ch 7: Surface thermodynamics
├── 08-sci-mixing.qmd           # Ch 8: Vertical mixing
├── 09-sci-underflow.qmd        # Ch 9: Underflow model
├── 10-sci-destrat.qmd          # Ch 10: Artificial destratification
├── 11-getting-started.qmd      # Ch 11: Getting started
├── 12-pre.qmd                  # Ch 12: Domain pre-processing
├── 13-elcom.qmd                # Ch 13: Configuring a simulation
├── 14-running.qmd              # Ch 14: Running a simulation
├── 15-output.qmd               # Ch 15: Output file processing
├── 16-developer.qmd            # Ch 16: Developer information
├── 17-application.qmd          # Ch 17: Application examples
├── 18-publications.qmd         # Ch 18: Publications
├── references.qmd              # References
├── book.bib                    # Bibliography database
├── packages.bib                # Package citations
├── preamble.tex                # LaTeX preamble (PDF output)
├── images/                     # All figures
│   ├── coords.pdf
│   ├── coupling.pdf
│   ├── eview_cart_mesh.png
│   ├── fig4_1.pdf
│   ├── fig4_2.pdf
│   ├── insertion.pdf
│   ├── north.pdf
│   ├── pview_bath.pdf
│   ├── pview_cart_mesh.pdf
│   ├── unstableMixing.pdf
│   └── vgrid.pdf
├── docs/                       # Rendered HTML (served by GitHub Pages)
└── .gitignore
```
