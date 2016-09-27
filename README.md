# A template for the MSc project dissertation

Files are in one of two directories `tex` (for the tex files) and `img` (for
image files) directory which contains:

    tex
    ├── chapters
    │   └── appendix.tex
    │   └── chapter1.tex
    │   └── chapter2.tex
    │   └── chapter3.tex
    │   └── chapter4.tex
    ├── acknowledgements.tex
    ├── bibliography.bib
    ├── executive_summary.tex
    ├── main.tex
    ├── summary.tex
    ├── title.tex
    img
    ├── cardiff_logo.jpg
    ├── image1.png

Compiling the `main.tex` file pulls in all the other files as required.  The
`chapter{1,2,3}.tex` files would be where the main part of your content goes.
To read more about multi file LaTeX projects see this [wiki
page](https://en.wikibooks.org/wiki/LaTeX/Modular_Documents).

To handle all these files I recommend compiling with `xelatex`.
