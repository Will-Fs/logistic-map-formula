# logistic-map-formula
Program that graphs the logistic map formula in python using pygame.

Formula: f(x) = f(x-1) * R * (1 - f(x-1)); where the graph begins at a number between 1 and 0. This number can be found and changed on line 5; variable *i*.

The size of the window can be changed by changing the values on lines 8 and 9. *w* corresponds to the width in pixels, and *h* corresponds to the height in pixels.

# DEPENDENCIES
  - python3
  - pygame 1.9.6 or higher

# controls:
  - Drag with the mouse to move the graph around
  - # keystrokes
    - lshift + up: increase R by 0.0010
    - lctrl + up: increase R by 0.0100
    - lalt + up: increase R by 0.1000
    - lshift + lctrl + up: increase R by 1.0000
    - ---- The same commands with the down arrow will decrease R by the same amounts ----
  
  - minus: zoom out (y-axis)
  - plus: zoom in (y-axis)
