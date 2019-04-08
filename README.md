# E18 Latex Mall v1.0
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
* `\newpage` vs `\pagebreak`
* Easy syntax control with [fancy verbatism](http://texdoc.net/texmf-dist/doc/latex/fancyvrb/fancyvrb.pdf)

### Figures:
* [Examples](https://nasa.github.io/nasa-latex-docs/build/html/examples/figures.html)
* In MatLab save your plots as vector-based (EPS format) with the following command:
`saveas(gcf,'filename','epsc')`. Output may vary between platforms and Matlab versions, check out [`print`](https://www.mathworks.com/help/matlab/ref/print.html) and [`saveas`](https://www.mathworks.com/help/matlab/ref/saveas.html) help pages.

### Tables:
[Examples](https://www.latex-tutorial.com/tutorials/tables/)

### Reference system:
References are managed by BibTex and is using IEEE referencing standard. Learn more:

[About BibTex](https://en.wikipedia.org/wiki/BibTeX)

[BibTex Tutorial](https://www.latex-tutorial.com/tutorials/bibtex/)

### Matlab code inclusion:
Matlab source code viewer is taken from [NASA's Github repo](https://github.com/nasa/nasa-latex-docs/blob/master/support/packages/mcode/mcode.sty)

### Draw in Latex:
* [Draw circuits with *circuitikz*](https://www.overleaf.com/learn/latex/LaTeX_Graphics_using_TikZ:_A_Tutorial_for_Beginners_(Part_4)—Circuit_Diagrams_Using_Circuitikz). 
Examples: 
[(1)](https://www.latex-tutorial.com/tutorials/circuitikz/)
[(2)](https://www.latex-tutorial.com/tutorials/more-circuitikz/)

* [CircuiTikZ Manual](http://texdoc.net/texmf-dist/doc/latex/circuitikz/circuitikzmanual.pdf)
* [A very minimal introduction to TikZ](https://cremeronline.com/LaTeX/minimaltikz.pdf)
* [TikZ examples](http://www.texample.net/tikz/examples/)

### Warning handling:
* Ignore sensitive latex code: `\begin{verbatim} Ignored latex code... \end{verbatim}` or with `\`
* Silencing stupid warnings: `\WarningFilter{latex}{Warning info...}`

