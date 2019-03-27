# E18 Latex Mall v0.9
Any improvement suggestions are appreciated. –> ***georgij.michaliutin (at) me.com***

## Import in to Overleaf
1. Download ZIP file (**Clone or download** button)
1. Go to Overleaf, click on **New Project** and select **Upload Project**
1. Upload the ZIP file



Before editing ***main.tex*** and files in ***Settings/*** folder inspect the code and dependencies.

## Useful information

### General Latex information:
[Latex Tutorials](https://www.latex-tutorial.com)

[Tex Documentation Lookup](http://texdoc.net)


### Text layout:
* Know difference between `\newpage` vs `\pagebreak`
* Easy syntax control with [fancy verbatism](http://texdoc.net/texmf-dist/doc/latex/fancyvrb/fancyvrb.pdf)

### Figures:
* In MatLab save your plots as vector-based (EPS format) with the following command:
`print -depsc -tiff example1`. Also check out `print` and `saveas` help pages as output may vary between platforms and Matlab versions.

### Tables:
[Examples](https://www.latex-tutorial.com/tutorials/tables/)

### Reference system:
Current reference system is based on IEEE standard

[About BibTex](https://en.wikipedia.org/wiki/BibTeX)

[BibTex Tutorial](https://www.latex-tutorial.com/tutorials/bibtex/)

### Matlab code display:
[Matlab code interpreter](https://github.com/nasa/nasa-latex-docs/blob/master/support/packages/mcode/mcode.sty)

### Warning handling:
* Ignore sensitive latex code: `\begin{verbatim} Ignored latex code... \end{verbatim}` or with `\`
* Silencing stupid warnings: `\WarningFilter{latex}{Warning info...}`

