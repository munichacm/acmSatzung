all:
	pdflatex -synctex=1 -interaction=nonstopmode Beitragsordnung.tex;
	pdflatex -synctex=1 -interaction=nonstopmode Beitragsordnung.tex;
	pdftotext Beitragsordnung.pdf - | wc -w

clean:
	rm *.aux
	rm *.log
	rm *.run.xml
	rm *.synctex.gz
	rm *-blx.bib