# makefile for generating with prelim document with bibliography

run: test.dvi test.pdf clean

test.dvi : test.tex
	latexmk test.tex

test.pdf : test.dvi
	dvipdf test.dvi

clean:
	rm test.dvi test.bbl \
           test.blg test.fls \
           test.*~ test.l* \
           test.toc test.log \
           test.out test.aux \
           test.f*
