default: index.html

install:
	Rscript -e "install.packages(c('rmarkdown', 'revealjs'))"

index.html: index.Rmd style.css
	Rscript -e "rmarkdown::render('$<')"
