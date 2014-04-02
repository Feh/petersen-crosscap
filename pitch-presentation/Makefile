default: pdf
wiki2beamer:
	wiki2beamer crosscap-petersen.wiki > crosscap-petersen.tex
dvi: wiki2beamer
	latex crosscap-petersen
pdf: wiki2beamer
	pdflatex crosscap-petersen
clean:
	git clean -fx
