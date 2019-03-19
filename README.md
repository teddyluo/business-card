<<<<<<< HEAD
Latex Business Card (Both English and Chinese)
=============

Example:

<div>
    <img src="screenshot/ChinesePage.png" alt-="front side business card" width="200px"/>
    <img src="screenshot/EnglishPage.png" alt-="back side business card" width="200px"/>
</div>


Requirements
------------

* Recent TeX installation (tested on a 2017 one)
* XeLaTeX


Building the Final Document
------------------

Build the front and back sides with XeLaTeX:

```shell
xelatex main.tex
xelatex main.tex
```
or:
``` shell
xelatex.exe -synctex=1 -interaction=nonstopmode main.tex
```

SVG Files
---------

LaTeX is not equipped to handle SVG files directly. A conversion to a PDF file is needed. This can be done using an external tool such as Inkscape:

```shell
inkscape --without-gui --export-area-drawing --file=logo.svg --export-pdf=logo.pdf
```

PNG Files
----
This can be also handled by the 3rd tools, such as adboe acrobat or Inkscape.

Reference
----
* [Jiaolong/latex-business-card](https://github.com/Jiaolong/latex-business-card)
* [Naereen/Business-Card](https://github.com/Naereen/Business-Card)
=======
# business-card
personal business card
>>>>>>> c5fed105d9e84f3076f524a0f7c7f4d7c7e9e2ea
