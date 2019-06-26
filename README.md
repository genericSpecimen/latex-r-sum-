# latex-résumé

## About

A résumé template made with [LaTeX](https://www.latex-project.org/).

To see what it looks like, open this [PDF](./resume.pdf).

## Modifications

Note: You need to install [LaTeX](https://www.latex-project.org/) first.

The sections of the résumé are divided into separate .tex files, which are then included in the main [resume.tex](./resume.tex) file.

To add a new section, simply create a new file `new_section.tex` and include it in the [resume.tex](./resume.tex) by typing the following lines:

```latex
\section {new_section}

\input {new_section.tex}
```

To test the new changes, use the command:

`pdflatex resume.tex`

This will overwrite the resume.pdf file.

