doc = 2017_apc_ws
bib = ref
pdf: ${doc}.tex
	pdflatex ${doc}.tex

bib: ${doc}.tex
	bibtex ${doc}


REMOVE = rm -rf
clean: 
	$(REMOVE) *.dvi *.aux *.log *.bbl *.blg *.toc *.out *.nav *.snm *.lot *.lof *.vrb *.tdo

realclean: clean
	$(REMOVE) *.pdf *.ps *~


