default: abstract.pdf

%.pdf: %.Rmd
	@Rscript -e "rmarkdown::render('$<')"
