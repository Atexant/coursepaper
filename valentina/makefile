
NAME =coursepaper

all: $(NAME).pdf

clean:
	rm -rf *.log *.aux *.toc  *.dvi *.ps *.pdf *.mps

$(NAME).pdf: *.tex
	rm -rf *.log *.aux *.toc  *.dvi *.ps *.pdf *.mps
#	mpost graphics end
	latex $(NAME).tex
	latex $(NAME).tex
	latex $(NAME).tex
	dvips $(NAME).dvi
	ps2pdf $(NAME).ps $(NAME).pdf
	rm -rf *.log *.aux *.toc  *.ps *.mps
