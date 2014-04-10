all:
	latex prct10.tex
	latex prct10.tex
	bibtex prct10
	latex prct10.tex
	latex prct10.tex
	dvips -o prct10.ps prct10.dvi
	ps2pdf -sPAPERSIZE=a4 -DMaxSubsetPct=100 -dCompatibilityLevel=1.2 -dSubsetFonts=true -dEmbedAllFonts=true memte.ps memte.pdf

clean:
	rm -f *.toc *.ps *.log *.lof *.lot *.dvi *.aux *.blg *.bbl