Requirements:
  * `pdflatex`-system package
  * `biber`-system package
  * some additional tex-packages

In order to test the repository or compile the example switch in the example folder
```
$ cd $REPOFOLDER/beamer/example
```
and compile the `LaTeX`-File Using
```
$ TEXINPUTS=../:$TEXINPUTS pdflatex example.tex
$ biber example
$ TEXINPUTS=../:$TEXINPUTS pdflatex example.tex
```
