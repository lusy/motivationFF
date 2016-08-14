# battlemesh_v9

This directory contains a version of the talk and discussion guidelines given at the
[BattleMeshV9](http://battlemesh.org/BattleMeshV9) in May 2016.


## to view the presentation

* checkout this repo
* switch to the `battlemesh_v9` subdirectory
* checkout [revealjs](https://github.com/hakimel/reveal.js) under the name `reveal.js`
* open the `slides.html` file in your browser

## to build the slides

* checkout this repo
* switch to the `battlemesh_v9` subdirectory
* checkout [revealjs](https://github.com/hakimel/reveal.js) under the name `reveal.js`
* edit the source of the slides: the `slides.md` file

* install [pandoc](https://github.com/jgm/pandoc/releases/)

### html slides

use `pandoc -s --mathjax -i -t revealjs slides.md -o slides.html` to convert the slides to a html presentation

### latex slides

use `pandoc -t beamer slides.md -o slides.pdf` to convert the slides to a latex beamer presentation

