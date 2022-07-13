# Fractals in PostScript

This project contains implementations of fractals (and cellular automata) in the PostScript language.

### Why PostScript?

Most general-purpose languages require a lot of boilerplate code to generate and display a image.
PostScript is designed specifically for the generation of raster images,
and has built-in graphics primitives and affine transformation functions.
This makes it a very concise language for implementing chaotic attractors and other fractals.

## Contents

* **<tt>fern.ps</tt>** The classic Barnsley fractal fern
* **<tt>1dca.ps</tt>** 1-dimensional cellular automata with a random seed
* **<tt>LogisticMap\*.ps</tt>** Two implementations of the Logistic Map, one zoomed in on the chaotic range 3.0-4.0
* **<tt>e\*.ps</tt>** Chaotic attractors from Clifford Pickover's book "Computers, Pattern, Chaos and Beauty"

## How to view
* **MacOS** Just double-click a <tt>ps</tt> file to open it in Preview
* **Windows** Use GSView or PSViewer
