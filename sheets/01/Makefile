filename=submission_01

all:
	pdflatex ${filename}.tex
	rm ${filename}.aux ${filename}.log ${filename}.out ${filename}.thm

MAKEFLAGS := --jobs=$(shell nproc)
