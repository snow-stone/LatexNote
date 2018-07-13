# Elsevier template

For JNNFM

## Files
Latex package : elsarticle.zip
tex example   : elsarticle-template-1-num.tex : [source](https://www.overleaf.com/17828824qhytxytvfxhc#/67575788/)
sample.bib    : bib file
placeholder.png : image to hold place

## usage
1. install elsarticle => get `elsarticle.cls` and `elsarticle-*.bst`
2. latex elsarticle-template-1-num.tex (`elsarticle.cls` can be found by putting it to `$HOME/texmf/tex/latex/elsartcls`)
3. bibtex elsarticle-template-1-num (Have to copy `elsarticle-harv.bst` to the local directory, tried the other two `elsarticle-num-names.bst` and `elsarticle-num.bst`. Well they don't work...)
4. latex elsarticle-template-1-num.tex
5. pdflatex elsarticle-template-1-num.tex
6. get the pdf and see at Section1 whether the reference is good.
