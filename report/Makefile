BASENAME=petersen-graph-embedded-on-crosscap
LATEXMKOPTS=

TEX=$(BASENAME).tex
PDF=$(BASENAME).pdf

.DEFAULT: all
.PHONY: $(PDF) all clean
all: $(PDF)
$(PDF): $(TEX)
	latexmk $(LATEXMKOPTS) -pdf -pdflatex="pdflatex -interactive=nonstopmode" -use-make "$(TEX)"
clean:
	latexmk -CA
