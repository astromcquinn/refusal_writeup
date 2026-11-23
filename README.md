# refusal_writeup

LaTeX draft: "Why does rewording flip a refusal? A perturbation analysis of Gemma-2-2b-it".

- `main.tex`: the draft. The references are in a `thebibliography` block at the end.
- `figures/`: PNG figures copied from the analysis project's `results/` folder.
- `main.pdf`: the compiled draft, committed for convenience.

Build with `latexmk -pdf main.tex`.

Section 2 of the draft defines every quantity used in the results as an equation; it goes beyond `WRITEUP.md`, which is the plain-language version.

The text was first converted from `WRITEUP.md` in the analysis project (`LLM_instabilities`), which is the source for every number; its Section 8 lists the report behind each result. The author field in `main.tex` is a placeholder.
