beamer-lu
=========

Beamer template for University of Latvia

[Prerequisites]
1. A XeLaTeX or LaTeX compilator with latex-beamer package is a must, TeX Live MiKTeX or MacTex will be just fine.
[Optional]
2. An Unicode *.tex editor like Texmaker.
3. To compile the provided 'test-lu.tex' file you should have MS true type fonts Cambria, Calibri and Consolas installed into Your system and it should be compiled using 'xelatex' command. Otherwise a few changes have to be made in the LaTeX code.
4. 'fixlatvian' (http://code.google.com/p/fixlatvian/) pakotne, to ir iespējams aizstāt ar standarta instalācijās pieejamo 'polyglossia'

[File list]
beamerthemelu.sty - main theme file
test-lu.tex - an example LaTeX source
test-lu.pdf - compiled exeample
pdf/* graphical elements neccessary for successful compilation
pdf/bg-full.pdf - background for the title page
pdf/bg-top.pdf - background for the frame pages
pdf/bg-watermark.pdf - watermarks for the title page
pdf/bg-watermark-frame.pdf - watermarks for the frame pages
pdf/lu-logo-full-page.pdf - LU logo for the title page
pdf/lu-logo-white.pdf - LU logo for the frame pages
svg/* - SVG source files of the graphical elements, generally not neccessary for a common user
