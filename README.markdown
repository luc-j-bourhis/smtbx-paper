Prerequisites
-------------

The typesetting of this article requires the iucr.cls style class that may be found at the following URL: ftp://ftp.iucr.org/templates/latex/iucr.cls

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
