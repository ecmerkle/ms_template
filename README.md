Example files for writing an APA-formatted academic paper via LaTeX and knitr. To compile:

1. Ensure that these files are in R's working folder. Then, in R, run `knitr::knit("template.Rnw")`
2. From the command line (outside R), run `pdflatex template.tex`
3. From the command line (outside R), run `biber template`
4. From the command line (outside R), run `pdflatex template.tex` two more times to get the references in place.

Steps 2-4 require that LaTeX is installed on your system. If you haven't done this, see the [tinytex package](https://yihui.org/tinytex/), especially its `tinytex::pdflatex()` command (where Steps 2-4 would then be run inside R, as opposed to outside R).
