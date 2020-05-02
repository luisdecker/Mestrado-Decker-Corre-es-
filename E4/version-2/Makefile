PAPER=2018-samsung-technical-report-e4

all:
	pdflatex -synctex=1 -interaction=nonstopmode $(PAPER).tex


clean: 
	rm -f *.dvi *.log *.toc *.aux *.bbl *.blg *.loa *.los *.out *.cb *.lof *.lot *.tdo *.thm *.synctex.gz

cleanall: clean
	rm -f $(PAPER).pdf

