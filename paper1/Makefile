compile:
	python compile.py
	make -f Makefile all

all:
	python proceedings.py > proceedings.tex
	pdflatex proceedings
	pdflatex proceedings
	pdflatex proceedings

view:
	open proceedings.pdf


review:
	python reviews.py > reviews.tex
	pdflatex reviews

clean:
	rm -f *.aux *.log *.out *.toc
