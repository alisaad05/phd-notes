all: pdf clean

pdf:
	pdflatex -interaction=nonstopmode Formulation.tex
	# bibtex Formulation
	pdflatex -synctex=1 -interaction=nonstopmode Formulation.tex

clean:
	rm -f *.aux *.log *.bbl *.blg *.toc *.lof *.lot *.out *.mtc* *.stc* *.maf *.dvi *.tdo
	
autocommit:
	git add .
	git commit -m "Auto Commit"