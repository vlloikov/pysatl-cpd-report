.PHONY: all clean

all: vkr.pdf

vkr.pdf: $(wildcard *.tex) matmex-diploma-custom.cls
	latexmk -xelatex -shell-escape -interaction=nonstopmode -halt-on-error -file-line-error vkr.tex

clean:
	latexmk -C vkr.tex
