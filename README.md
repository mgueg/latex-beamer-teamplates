# My LaTeX Beamer Template

## [Beamer PPrime theme](./pprime/)

- adaptation for new pprime institute theme (www.pprime.fr)

## [Beamer Pprime Poster theme](./poster/)

- adaptation for new pprime institute theme (www.pprime.fr)

## Usage

- Work with xelatex 
- See `pprime.sty` and `google.tex` in `./pprime/` directory to adapt to your own latex beamer file

```
% !TEX program = xelatex
```

- clone it :

```
$ git clone git@github.com:mgueg/latex-beamer-teamplates.git
```

- add `\usepackage{}` in your latex file;

```
\usepackage{hyperref,/path/to/latex-beamer-teamplates/pprime/pprime}
```


## Improvements

- some theme images (background;logo) are hardcoded in `.sty` : need to be changed

