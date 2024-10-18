Example files for writing an APA-formatted academic paper via LaTeX and knitr. To compile:

1. Ensure that these files are in R's working folder. Then, in R, run `knitr::knit("template.Rnw")`
2. From the command line (outside R), run `pdflatex template.tex`

Step 2 requires that LaTeX is installed on your system. If you haven't done this, see the [tinytex package](https://yihui.org/tinytex/), especially its `tinytex::pdflatex()` command (where Step 2 would then be run inside R, as opposed to outside R).
