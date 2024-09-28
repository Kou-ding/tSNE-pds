SHELL := /bin/bash

TEX_MAIN = report.tex

all: report
# --shell-escape is needed for the "minted" latex package
report: $(TEX_MAIN)
	latexmk -pdf --shell-escape $(TEX_MAIN) 

clean:
	latexmk -C $(TEX_MAIN)
	rm -f *.bbl 
	rm -r _minted-report/
