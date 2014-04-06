BASE=petersen-crosscap-presentation

all: $(BASE).pdf

$(BASE).pdf: $(BASE).tex
	latexmk -pdf $(BASE)

$(BASE).tex: $(BASE).markdown
	pandoc -s -f markdown -t beamer -o $(BASE).tex < $(BASE).markdown

clean:
	latexmk -CA
