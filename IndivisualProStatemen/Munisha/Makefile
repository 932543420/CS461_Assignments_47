TARGET = ProposalStatementCapstone


all:
	latex ProposalStatementCapstone.tex
	dvips -R -Poutline -t letter ProposalStatementCapstone.dvi -o ProposalStatementCapstone.ps
	ps2pdf ProposalStatementCapstone.ps
	rm ProposalStatementCapstone.aux
	rm ProposalStatementCapstone.dvi
	rm ProposalStatementCapstone.log
	rm ProposalStatementCapstone.ps
	rm ProposalStatementCapstone.out