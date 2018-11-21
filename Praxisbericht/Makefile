all:
	pdflatex richtlinien_Praxisbericht.tex
#	bibtex richtlinien_Praxisbericht
	makeglossaries richtlinien_Praxisbericht
	pdflatex richtlinien_Praxisbericht.tex
	pdflatex richtlinien_Praxisbericht.tex
	cp richtlinien_Praxisbericht.pdf tmp.pdf

zip:
	cd ..&&zip -r Richtlinien_Praxisbericht_Latex.zip Richtlinien_Praxisbericht_Latex
clean:
	rm -rf *.ist *.toc *.lot *.lof *.aux *.bbl *.blg *.log *.lol *.out *.gl?  *.glsdefs *~
