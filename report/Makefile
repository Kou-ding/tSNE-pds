SHELL := /bin/bash

TEX_MAIN = main.tex

.PHONY: all clean

all: $(TEX_MAIN)
	latexmk -pdf $(TEX_MAIN)

clean:
	latexmk -C $(TEX_MAIN)
