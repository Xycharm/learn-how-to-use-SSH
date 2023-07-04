all: template.pdf 

template.pdf: template.tex
	xelatex template
	bibtex template.aux
	xelatex template
clean:
	rm -f *.aux *.log *.pdf \
	*.toc *.snm *.nav *.out \
	*.thm *.bbl *.ps *.dvi *.blg

.PHONY: all clean
