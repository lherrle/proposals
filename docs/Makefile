LATEX=pdflatex
BIBTEX=bibtex

PDFFILES=rapid-rendering.pdf

all: clean $(PDFFILES)

$(PDFFILES): %.pdf: %.tex rapid-rendering.tex
	$(LATEX) $<
	$(LATEX) $<
	$(LATEX) $<
	$(LATEX) $<

clean:
	rm -f *.aux *.log *.dvi $(PAPER).pdf *.lot *.lof *.toc *.blg *.bbl *.ent *.out
