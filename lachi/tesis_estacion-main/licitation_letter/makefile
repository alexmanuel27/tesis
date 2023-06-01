FILE=thesis_licitation.tex

compile:
	latexindent -l -m -s -w $(FILE)
	latexmk -pdf -file-line-error -interaction=nonstopmode -synctex=1 -output-format=pdf -output-directory=out $(FILE)