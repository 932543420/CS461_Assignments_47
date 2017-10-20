TARGET = capstone


all:
	latex capstone.tex
	dvips -R -Poutline -t letter capstone.dvi -o capstone.ps
	ps2pdf capstone.ps
	rm capstone.aux
	rm capstone.dvi
	rm capstone.log
	rm capstone.ps
	rm capstone.out
	
