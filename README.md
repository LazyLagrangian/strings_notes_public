# Introduction to String Theory, Part II: String compactifications

Lecture notes for Module 1 of *Introduction to String Theory* (University of Bologna, academic year 2026/27).

**[Read the notes (PDF)](main.pdf)**

The module covers the low-energy effective action of string theory, D-branes and dualities, type II compactifications on Calabi–Yau manifolds, flux compactifications and moduli stabilisation, supersymmetry breaking in string models, and the basic principles of string cosmology. Chapters are added as the course goes on.

The notes use one set of conventions throughout (mostly-plus metric, $\ell_s = 2\pi\sqrt{\alpha'}$, reduced Planck mass), collected in the chapter *Notation and conventions*.

These are student notes, not an official text of the course: they have not been reviewed by the lecturer, and any errors are mine. Corrections are welcome as issues or pull requests.

## Building

```sh
latexmk -pdf main.tex
```

The sources are `main.tex` (preamble and title page), `editors_note.tex` (the editor's note), `macros.tex`, `conventions.tex` and one file per lecture in `lectures/`; the figures are in `figures/`.
