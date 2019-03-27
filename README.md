# E18 Latex Mall v0.9
Any improvement suggestions are appreciated. –> ***georgij.michaliutin (at) me.com***

## Import in to Overleaf
1. Download ZIP file (**Clone or download** button)
1. Go to Overleaf, click on **New Project** and select **Upload Project**
1. Upload the ZIP file



Inspect the code and dependencies before editing ***main.tex*** and files in ***Settings/*** folder!

## Useful information

### General Latex information: 
http://texdoc.net

### Text layout:
* Know difference between `\newpage` vs `\pagebreak`

### Syntax:
* Ignore sensitive signs with `\begin{verbatim}` `\end{verbatim}` or with `\`

[Fancy verbatism](http://texdoc.net/texmf-dist/doc/latex/fancyvrb/fancyvrb.pdf)

### Figures:
* In MatLab save your plots as vector-based (EPS format) with the following command:
`print -depsc -tiff example1`

### Tables:
[List of examples](https://www.latex-tutorial.com/tutorials/tables/)

### Reference system:
Current reference system is based on IEEE standard

[About BibTex](https://en.wikipedia.org/wiki/BibTeX)

[BibTex Tutorial](https://www.latex-tutorial.com/tutorials/bibtex/)

### Matlab code display:
[Matlab code interpreter](https://github.com/nasa/nasa-latex-docs/blob/master/support/packages/mcode/mcode.sty)

### Warning handling:
Silencing stupid warnings with:
`\usepackage{silence}`
`\WarningFilter{latex}{Warning info...}`

