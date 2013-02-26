# Zurich Beamer Theme

The Zurich beamer theme is a simplistic theme for
[Beamer](https://bitbucket.org/rivanvx/beamer/wiki/Home), a fairly popular LaTeX
class for creating presentations. The theme is heavily based on the excellent
[Flip Beamer template](http://www.lepp.cornell.edu/~pt267/files/code/FlipBeamerTemplate.pdf)
and I mainly changed the main colors from to red to blue. 

![Example slide](http://pletscher.org/assets/img/pletscher2012thesis-talk_small.png)


## Installation

1. Install XeLaTeX and latexmk (not really required).
2. Clone the git repository from github `git clone git@github.com:ppletscher/beamerthemeposterzurich.git`.
3. run `make` to compile the file `example_talk.tex`.
4. If you like the theme, simply copy the files
`appendixnumberbeamer.sty`,
`beamercolorthemeZurich.sty`, `beamerfontthemeZurich.sty`,
`beamerinnerthemeZurich.sty`, `beamerouterthemeZurich.sty` and
`beamerthemeZurich.sty` to a path where LaTeX is looking for additional code,
such as `~/texmf`.
