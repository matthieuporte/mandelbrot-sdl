# mandelbrot-sdl

My second attempt at creating a mandelbrot explorer.
This version made with sdl allows palletting and custom palettes. 
You cannot save image or resize the window. Thoses functionalities are available
[in the gtk version](https://github.com/matthieuporte/mandelbrot)

My first version was a fractal [in ocaml](https://github.com/matthieuporte/mandelbrot-ocaml)

### How to use the app

run
```
make
./main
```

Then left click to zoom and right click to unzoom. A linked list is used to save
previously explored areas.


### How to use color palettes

run
```
./main path/to/your/palette.theme
```

A palette is a file made out of hex colors. Some examples in /palettes.

For example you can run

```
./main palettes/fire.theme
```

