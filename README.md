# Mandlebrot Set

The goal for this project was to make an interactive mandlebrot set in a single HTML file as quickly as possible and without any libraries.

This project allows you to zoom into the fractal with the mouse wheel to explore the set.
If you want a demo of the app you can click [demo].

## Example Images
![alt text][basic]
![alt text][seahorse]
![alt text][zoom1]
![alt text][spirals]
![alt text][zoom2]

### Current issues include:
* Maximum zoom level is ~40 for floating point precision reasons.
* It's quite slow. This could probably be fixed by smarter scaling instead of adaptively increasing solver iterations based on zoom level.
* CSS laziness.

[demo]: http://htmlpreview.github.com/?https://github.com/maxwell-yaron/mandlebrot/blob/master/index.html
[basic]: https://github.com/maxwell-yaron/mandlebrot/raw/master/images/basic.png
[seahorse]: https://github.com/maxwell-yaron/mandlebrot/raw/master/images/seahorse.png
[zoom1]: https://github.com/maxwell-yaron/mandlebrot/raw/master/images/zoom1.png
[spirals]: https://github.com/maxwell-yaron/mandlebrot/raw/master/images/spirals.png
[zoom2]: https://github.com/maxwell-yaron/mandlebrot/raw/master/images/zoom2.png
