# FRACTOL

This project consists to create a small fractal exploration software.
[What is a Fractal ?](https://en.wikipedia.org/wiki/Fractal)

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
`Space` | Only available for Julia
`Mouse` | DeepZoom/Hover after pressed space on Julia
`R` | Reset

### Example

![fractol_mandelbrot](./fractol.png "fractol_mandelbrot")

### Deployment

Develop for UNIX systems

### Built With

* [Minilibx] - The framework for graphical user interface development

