# A General LaTeX Beamer Template for Presentations

- This is a general LaTeX Beamer template that I use for presentations. It is based on [this XJTU beamer template](https://www.overleaf.com/latex/templates/xjtu-beamer-theme/ddhzxgwqbvsy).
- On the bases of the original template, I have made some modifications to make it match my preferences.

## Main Changes (2023.10.12 update)
- Add support to `PingFang SC` font in the titles, footnotes, etc. of each slide.
- Apart from `xjtu.bst` bib style file, I provide support to `informs2014.bst` bib style file. The corresponding modification is made in `silde.tex`.
- Add support to `annotate-equations`, this macro package is used to annotate equations. To use this feature, I suggest updating the `TexLive` or `MacTex` to the latest version and using `latexmk` compile this project. See [this link](https://github.com/st--/annotate-equations) for more details.

## Usage
- The main file is `slide.tex`. You can modify the content of each slide in `slide.tex`.
- See the sample `.pdf` in [this XJTU beamer template](https://www.overleaf.com/latex/templates/xjtu-beamer-theme/ddhzxgwqbvsy) for more details on how to use it.