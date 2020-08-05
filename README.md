## Processing Newton's Method

This code generates a sequence of images using Newton's method
to find the roots of the following equation `z ^ 4 - 1 + z ^ 3`

Feel free to play around with the equations and colors of the sketch! For example, this was generated by adjusting the brightness based on iteration count and using the equation `z ^ 8 + 15z ^ 4 - 16`

![dark](https://github.com/alazareva/newtons_method/blob/master/examples/dark)


I have pre-define some nice color palettes for the basin fill. I prefer the blue theme myself. 

![iterations](https://github.com/alazareva/newtons_method/blob/master/examples/iterations.jpeg)

![basins](https://github.com/alazareva/newtons_method/blob/master/examples/basins.jpeg)

Controls:

```
key "b" or "B" to toggle between drawing basins/iterations
```

```
key "r" or "R" to save frames
```

Note: this thing is slow! It's iterating up to 100 times per pixel, if you want to speed it up, make the canvas smaller.