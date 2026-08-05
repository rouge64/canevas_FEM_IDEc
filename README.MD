# FEM IDEc Presentation Template

A LaTeX Beamer template for documenting and presenting Finite Element Method (FEM) studies.

This repository provides a structured presentation template covering the complete workflow of a FEM project, from the definition of the problem to the final conclusions. It is intended as a reusable starting point for engineers preparing technical presentations or analysis reports.

## Purpose

This template is **not intended to be used unchanged**.

Each project has different requirements. Users are expected to:

- keep only the slides relevant to the analysis;
- remove sections that are not applicable;
- duplicate slides when additional explanations are required;
- replace all placeholder text with project-specific content.

The objective is to provide a consistent methodology for documenting FEM studies rather than a fixed presentation.

## Contents

The template contains guidance and recommendations for documenting:

- Project overview
- Context and objectives
- Geometry
- Modelling assumptions
- Boundary conditions and loads
- Materials
- Mesh generation and quality
- Mesh convergence
- Solver settings
- Result validation
- Discussion of results
- Conclusions
- References
- Authenticity declaration

Many slides also include recommendations and best practices to improve the quality, reproducibility and readability of engineering reports.

## Repository structure

```text
.
├── data/
│   ├── preamble.tex      # Packages and global configuration
│   └── info.tex          # Author and presentation information
│
├── slides/
│   ├── information/      # Project definition and methodology
│   ├── modelling/        # FEM modelling
│   ├── results/          # Results and discussion
│   └── conclusion/       # Conclusions and references
│
├── img/
│   ├── information/
│   ├── modelling/
│   ├── results/
│   └── conclusion/
│
├── references.bib
└── main.tex
```

The `img/` directory is organised using the same chapter structure as the presentation to simplify image management.

## Requirements

- TeX Live
- Biber
- A LaTeX editor (Visual Studio Code + LaTeX Workshop recommended)

## Compilation

Compile the project using `latexmk` or any LaTeX editor supporting `biblatex` and `biber`.

## License

This project is distributed under the terms of the accompanying LICENSE file.
