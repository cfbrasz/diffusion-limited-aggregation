# diffusion-limited-aggregation

Repository for interactive simulations of diffusion-limited aggregation.

Starts with single seed pixel (or a line or square of seed pixels), and random walkers are added one at a time, allowed to walk until they contact the existing structure, at which point they freeze.

Implemented features:
- Color scale for walker number
- "Pixel" size
- Checkbox for whether to show the random walkers or not
- Sliders for speed
- Checkbox for diagonal vs. perpendicular neighbors
- Options for alternative attractors (line, square)
- "Stickiness" parameter

Options to add:
- Options for alternative walker starting points (Voronoi diagram edges, bias based on existing angle)

Programming notes:
Javascript sets don't generalize to two-dimensional coordinates. So convert coordinates to integers based on known dimensions of grid.
