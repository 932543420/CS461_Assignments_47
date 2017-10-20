TARGET = p1


all:
	latex p1.tex
	dvips -R -Poutline -t letter p1.dvi -o p1.ps
	ps2pdf p1.ps
	rm p1.aux
	rm p1.dvi
	rm p1.log
	rm p1.ps
	rm p1.out
	
