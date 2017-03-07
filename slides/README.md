# Slide show

Directory contents:

* ``README.md`` -- this file
* ``compile`` -- Bash script to compile the LaTeX file (see below)
* ``git-winona-slides.pdf`` -- PDF version of the presentation
* ``git-winona-slides.tex`` -- LaTeX Beamer source of the presentation

This is the main LaTeX Beamer presentation used at the workshop. The instructor followed along in the command line.

For the lesson plans, see: <http://swcarpentry.github.io/git-novice/>

The URL to the corresponding page of the lesson is shown on each slide.

Some of the SVG files from the lesson plans were converted to TikZ using Inkscape.

## A note on compiling from source:

Because these slides use the ``minted`` package (for syntax highlighting), they require [Pygments](http://pygments.org/) to be installed, and for the ``--shell-escape`` flag to be present when running ``pdflatex``. The file ``compile`` is a shell script the author uses for convenience, since his IDE is not configured to provide the ``--shell-escape`` flag.
