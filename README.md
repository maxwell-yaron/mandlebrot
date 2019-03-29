# Mandlebrot Set

The goal for this project was to make an interactive mandlebrot set in a single HTML file as quickly as possible and without any libraries.

This project allows you to zoom into the fractal with the mouse wheel to explore the set.
If you want a demo of the app you can click [link].

### Current issues include:
* Maximum zoom level is ~40 for floating point precision reasons.
* It's quite slow. This could probably be fixed by smarter scaling instead of adaptively increasing solver iterations based on zoom level.
* CSS laziness.

[link]: http://htmlpreview.github.com/?https://github.com/maxwell-yaron/mandlebrot/blob/master/index.html
