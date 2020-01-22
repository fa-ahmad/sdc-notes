# Overview
We, as humans, identify lane lines based on their color--white and yellow, their shape--thick rectangular stripes, and their surroundings--relatively dark surface of the road. Computer vision algorithm cannot reason about the extents of the road and rely on identifying lanes by their color and shape alone. Color varies a lot based on lighting conditions, shadows and so many other factors. Detecting potential rectangles is also not simple. However we can approximate detecting rectangles by detecting the boundary lines that make up the longer edges of those rectangles.

## Canny Edge Detector
