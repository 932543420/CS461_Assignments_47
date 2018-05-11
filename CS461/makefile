TARGET = tr


all:
	latex tr.tex
	dvips -R -Poutline -t letter tr.dvi -o tr.ps
	ps2pdf tr.ps
	rm tr.aux
	rm tr.dvi
	rm tr.log
	rm tr.ps
	rm tr.out
	
