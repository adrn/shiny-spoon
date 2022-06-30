# APW: I apologize for this Makefile. It is not worthy of our make prowess.

.SUFFIXES: .tex .pdf

all: $(patsubst %.tex,%.pdf,$(wildcard *.tex))

.tex.pdf:
	pdflatex $*
