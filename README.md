# FDF - WIREFRAME

This project consists to create a graphical representation of a land by wireframe("Fil De Fer - FDF" in French) by connecting different points (x, y, z) by segments.
The land will be stocked in a file passed in parameters.

### Installing

Clone the project

```
git clone https://github.com/BABAK0T0/FRACTOL
```

Then execute Makefile to create an executable

```
make re
```

### Running

Choose a fractal :
* mandelbrot
* julia
* tricorn
* burn
* chameleon
* sword
* all


```
./fractol [name_fractal]
```

### Events

KEYS | DESCRIPTION
:-- |:-:| --:
`ESC` | Exit the program
`ARROW` | Move map(x,y)
`1/2/3` | Movement speed
`4/5/6` | Color
`I/J` | Iteration
`+ / -` | Zoom
`Space` | Only available on Julia
`Mouse` | DeepZoom/Hover after pressed space on Julia
`R` | Reset

### Example

![fractol_Julia](./fractol.png "fractol_Julia")

### Deployment

Develop for UNIX systems

### Built With

* [Minilibx] - The framework for graphical user interface development

