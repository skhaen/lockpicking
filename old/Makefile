

lockpicking.pdf:
	pdflatex lockpicking.tex
	pdflatex lockpicking.tex

lockpicking.zip: lockpicking.pdf
	# TODO: avoid zipbomb
	zip lockpicking.zip lockpicking.tex lockpicking.pdf images/*

zip: lockpicking.zip
