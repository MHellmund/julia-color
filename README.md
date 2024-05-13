# Julia Color Extension for Quarto

This extension

- provides support for Jupyter code output cells with ANSI escape sequences and
- uses the [JuliaMono font](https://juliamono.netlify.app/) as monospaced font.

It works for

- HTML,
- LaTeX/PDF output and
- Typst/PDF output.

(See the `example.qmd` file and the different output files.)


The web fonts for HTML are provided by the extension. For LaTeX/Typst/PDF you
[have to install the ttf files](https://juliamono.netlify.app/download/).



**This extension works only with a patched version of quarto!**


## Installation


```bash
quarto add MHellmund/julia-color
```


## Usage

```bash
quarto render example.qmd --to julia-color-html
quarto render example.qmd --to julia-color-pdf
quarto render example.qmd --to julia-color-typst
```
