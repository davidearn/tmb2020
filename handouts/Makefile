tmbinfo_2020.pdf: tmbinfo_2020.tex

%.tex: %.Rnw
	Rscript -e "library(knitr); knit('$*.Rnw')"
%.pdf: %.tex
	texi2pdf $<
clean:
	rm -f unnamed*
	rm -f *.{aux,tikz,out,log,blg,toc}
fresh: clean
	rm -f tmbinfo_2020.pdf
