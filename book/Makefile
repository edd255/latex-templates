filename=main

all:
	pdflatex ${filename}.tex
	# bibtex ${filename}.aux
	# pdflatex ${filename}.tex
	pdflatex ${filename}.tex
	rm -f ${filename}.aux \
		${filename}.bbl \
		${filename}.blg \
		${filename}.aux \
		${filename}.log \
		${filename}.out \
		${filename}.toc \
		${filename}.thm
