# opensym2016

This directory contains a version of the talk given at the
[OpenSym2016 Conference](http://www.opensym.org/os2016/) in August 2016.


## to view the presentation

* checkout this repo
* switch to the `opensym2016` subdirectory
* checkout [revealjs](https://github.com/hakimel/reveal.js) under the name `reveal.js`
* open the `slides.html` file in your browser

## to build the slides

* checkout this repo
* switch to the `opensym2016` subdirectory
* checkout [revealjs](https://github.com/hakimel/reveal.js) under the name `reveal.js`
* edit the source of the slides: the `slides.md` file

* install [pandoc](https://github.com/jgm/pandoc/releases/)

### html slides

use `pandoc -s --mathjax -i -t revealjs slides.md -o slides.html` to convert the slides to a html presentation

### latex slides

use `pandoc -t beamer slides.md -o slides.pdf` to convert the slides to a latex beamer presentation

