# diffusion-limited-aggregation

Repository for interactive simulations of diffusion-limited aggregation.

Starts with single seed pixel, and random walkers are added one at a time, allowed to walk until they contact the existing structure, at which point they freeze.

Implemented features:
-Color scale for walker number
-"Pixel" size

Options to add:
-Checkbox for whether to show the random walkers or not
-Slider for speed
-Checkbox for diagonal vs. perpendicular neighbors
-Options for alternative attractors (line, multiple points, circles)
-Options for alternative walker starting points (Voronoi diagram edges, bias based on existing angle)
-"Stickiness" parameter

Programming notes:
Javascript sets don't generalize to two-dimensional coordinates. So convert coordinates to integers based on known dimensions of grid.