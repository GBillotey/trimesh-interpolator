
!------------------------------------------------------------------------------!
Interpolates inside a triangular mesh.
Uses matplotlib.tri triangular mesh.
!------------------------------------------------------------------------------!

TriLinearInterpolator : linear interpolator
TriCubicInterpolator : C1-piecewise interpolator based on reduced 
Hsieh-Clough-Tocher (reduced HCT) element.

Note:
Also used to make higher-quality tricontour plots, using C1-piecewise
interpolation on a refined mesh and matplotlib tricontour function.
SmoothTriContour.py shows the principles.
