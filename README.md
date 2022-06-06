# zines
A repository for storing extensible zines. This is as much a repository for text and content as for typesetting.

Zines: 
## Songbook
The songbook requires the (songs)[http://songs.sourceforge.net/] package.
It is compiled into an A6 booklet using the technique provided by Mallipivo
in (this stackoverflow-post)[https://tex.stackexchange.com/questions/179119/how-to-automatically-output-page-order-to-print-8-pages-of-a-booklet-on-a-single] .


## Things to do two hours before you go to bed.
It has some sudoku in it, for which the [sudokubundle](https://www.ctan.org/pkg/sudokubundle) package was very useful (the specific sudoku puzzles come from the collection there, but it can also generate new puzzles - and solve them, actually), and some mandalas to colour - mostly from images created by graphical artists, but also some created directly in LaTeX by the participants in [this LaTeX competition](https://tex.stackexchange.com/questions/496414/tex-art-fun-mandalas) - and also some other things.
To create an a5-booklet from the resulting pdf, install the package [pdfbook2](https://github.com/jenom/pdfbook2) (included in texlive-extra-utils if you use ubuntu, which can be installed via sudo apt-get).
Then just run pdfbook2 your_regular_file_formatted_as_a4_article_for_example.pdf and it outputs an a5 booklet.