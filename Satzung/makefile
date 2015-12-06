all:
	pdflatex -synctex=1 -interaction=nonstopmode Satzung.tex;
	pdflatex -synctex=1 -interaction=nonstopmode Satzung.tex;
	pdftotext Satzung.pdf - | wc -w

clean:
	rm *.aux
	rm *.log
	rm *.run.xml
	rm *.synctex.gz
	rm Satzung-blx.bib