all: pdf clean

pdf:
	# pdflatex Formulation
	pdflatex -interaction=nonstopmode Formulation.tex
	# bibtex Formulation
	# pdflatex -interaction=nonstopmode Formulation.tex
	# pdflatex -interaction=nonstopmode Formulation.tex
	pdflatex -synctex=1 -interaction=nonstopmode Formulation.tex

clean:
	rm -f *.aux *.log *.bbl *.blg *.toc *.lof *.lot *.out *.mtc* *.stc* *.maf *.dvi *.tdo
	# rm -f References/*.aux References/*.log
	# rm -f Chapter1/*.aux Chapter1/*.log

autocommit:
	git add .
	git commit -m "Auto Commit"