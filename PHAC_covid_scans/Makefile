push:
	git add *.html
	git commit -am "update"
	git push
%.html: %.md
	Rscript -e "rmarkdown::render(\"$<\")"
%.docx: %.md
	pandoc $< -o $*.docx
%.pdf: %.md
	pandoc $< -o $*.pdf
