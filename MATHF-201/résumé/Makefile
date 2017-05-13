all: résumé.pdf
	evince résumé.pdf &

résumé.pdf: résumé.tex
	pdflatex résumé.tex
	pdflatex résumé.tex

clean:
	rm -f résumé.aux
	rm -f résumé.out
	rm -f résumé.log
	rm -f résumé.toc
