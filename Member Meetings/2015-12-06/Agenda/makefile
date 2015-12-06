all:
	pdflatex -synctex=1 -interaction=nonstopmode Agenda.tex;
	pdflatex -synctex=1 -interaction=nonstopmode Agenda.tex;
	pdftotext Satzung.pdf - | wc -w

clean:
	rm *.aux
	rm *.log
	rm *.run.xml
	rm *.synctex.gz
	rm *-blx.bib