Prerequisites
-------------

The typesetting of this article requires the [iucr.cls](ftp://ftp.iucr.org/templates/latex/iucr.cls) style class and the [iucr.bst](ftp://ftp.iucr.org/templates/latex/iucr.bst) bibliography style that shall first be installed in a place visible by the LaTeX system. For TeXLive on MacOS, those files should go in the directories `~/Library/texmf/tex/latex` and `~/Library/texmf/bibtbx/bst` respectively. 

Moreover, authors wishing to contribute to this article are advised to read the [IUCr recommendations](http://journals.iucr.org/d/services/latexstyle.html).

Typesetting
-----------

The body of the article is in the file `smtbx.tex` which is written so as to be typeset with `pdflatex`. In particular, this means that pictures shall only be in the PDF, PNG, JPEG or GIF format. An EPS file shall therefore first be converted to PDF using e.g. the program `epstopdf`.

Ignores LaTeX intermediate files
--------------------------------

We recommend to add the following lines to the global .gitignore, so as to ignore all intermediate files produced by LaTeX (the last 2 are specific to the MacOS program TeXShop).

        # LaTeX
        *.log
        *.aux
        *.bbl
        *.blg
        *.out
        *.fls
        *.synctex.gz
        *.fdb_latexmk
