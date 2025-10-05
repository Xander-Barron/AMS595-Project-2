AMS595-Project-2
Mandelbrot Boundary Approximation and Arc Length

This project approximates and visualizes a portion of the Mandelbrot set boundary, then fits a polynomial of degree 15 to the boundary and estimates its arc length using numerical integration.

Overview:
The Mandelbrot set has a fractal boundary with infinite length.  
This code:
- Scans vertical slices in the complex plane to approximate the boundary  
- Uses bisection to refine boundary crossings  
- Filters out trivial flat segments and invalid values  
- Fits a degree-15 polynomial to the boundary data  
- Computes the approximate arc length of the polynomial using the arc length formula from calculus  

Files:
Project_2.m
  - Mandelbrot iteration (fractal)
  - Indicator function for boundary detection
  - Bisection root-finding
  - Boundary scan and plot
  - Polynomial fitting and arc length computation

How to Run:
1. Open MATLAB or Octave
2. Place the script in your working directory
3. Run: Project_2.m

Outputs:
- A plot of the approximate Mandelbrot boundary
- Console output showing the estimated arc length
