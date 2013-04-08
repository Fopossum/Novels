Générer le pdf
==============

xelatex Ecorche.tex

Générer l'epub
==============

pandoc -S --toc --latex-engine=xelatex -f latex -t epub3 -o Ecorches.epub Ecorches.tex

Attention !!!!!
---------------

pandoc ne supporte pas le package lettrine. Donc tous les débuts de chapitres sautent pour l'instant

