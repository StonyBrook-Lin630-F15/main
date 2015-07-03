Parsing & Syntactic Processing
==============================


Overview
--------

This is the primary course website for Parsing & Syntactic Processing (Lin 637), offered by the [Department of Linguistics] [department] at [Stony Brook University] [sbu]. For a brief list of topics, check the [syllabus] [syllabus].

This repository is publicly accessible and hosts the LaTeX source code for the lecture notes. Compiled pdfs of each chapter are available in the [pdf] [pdf] folder.


Prerequisites
-------------


Readings
--------

Course readings are made available through the private [readings repository] [readings]. You must be enrolled in this class in order to get access.


Homeworks
---------

Compilation Instructions
------------------------

If you want to compile the lecture notes yourself, or use them as the basis for your own course, carefully follow the steps below.

1) Make sure you have all necessary software installed and set up correctly, in particular

  - a recent LaTeX distribution with _Tikz_ >= 3.00 and recent versions of _minted_ and _forest_
  - the Python pygments package (required by minted)

2) Clone the repository via git, or download and extract the [zip file](../../archive/master.zip).
 Note that the project folder will also contain an empty _build_ folder, which is used for temporary files to speed up compilation.

3) Use the standard tex --> pdf compilation tool chain (**not** tex --> dvi --> ps --> pdf!), but make sure that pdflatex is run with the parameters --shell-escape and --etex.


Link List
---------

### Using git

- [Github app for Windows](http://windows.github.com); supports only Windows 7 or later
- [Github app for Mac](http://mac.github.com); supports only OS X 10.9 or later
- List of alternative [GUI clients for git](http://git-scm.com/downloads/guis)
- Tutorials for using [git via the command line](https://www.atlassian.com/git/tutorials)
- Official [documentation for git](http://git-scm.com/doc)

[department]: http://linguistics.stonybrook.edu
[pdf]: ../../tree/master/pdf
[readings]: ../../../readings
[sbu]: http://www.stonybrook.edu
[syllabus]: ../../blob/master/pdf/0_syllabus.pdf?raw=true
