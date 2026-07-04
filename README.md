# XL Presentation Beamer Template

A clean LaTeX Beamer template with a navy, blue, and teal color palette.

## Files

- `XL_beamer.tex`: main presentation file
- `XLthemeBeamer.sty`: layout, title page, frame title, and footer
- `XLcolorBeamer.sty`: color palette and Beamer color settings
- `reference.bib`: bibliography file used by `XL_beamer.tex`
- `figures/Logo-University.png`: optional title-page logo
- `figures/SCUTPhoto.jpg`: example image used in the image slide

## Compile

```bash
pdflatex XL_beamer.tex
biber XL_beamer
pdflatex XL_beamer.tex
pdflatex XL_beamer.tex
```
