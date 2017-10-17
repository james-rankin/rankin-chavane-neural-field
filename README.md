# rankin-chavane-neural-field
Matlab code accompanying the paper

"Neural field model to reconcile structure with function in primary visual cortex", *PLOS Computational Biology*
by James Rankin (University of Exeter) and Frédéric Chavane (CNRS & Aix-Marseilles University)
doi: [xxx](http://journals.plos.org/ploscompbiol/)

A brief description of each file is given here, with detailed comments 
(referencing equations in the paper) provided primarily in `RunModel.m`

* `RunModel.m` - Main script to run the model.
Edit the string `FigString` to reproduce different figures from the paper. The following are valid figure strings: {'1', '2B'}

* `ModelRHSForODE.m` - Defines the main equations, 
i.e. model Right Hand Side

* `MultiRing.m` - Used to define Gaussian rings in connectivity

* `BuildMultiRingFcns.m` - constructs components of connectivity

* `RadFindSlope.m` - Function used for Naka-Rushton fits

* `utoVSD_FCN.m` - Function for computing VSD signal

* `FCNHSVAngMtx.m` - Plotting tool for orientation/selectivty colormaps

* `AngSelFcnFCN.m` - Computes mean activity and selectivity from VSD signal

* `ComputeFiringRate.m` - Firing rate function (sigmoid)

* `ComputeFTRadialHankel.m` - Numerical computation of Hankel Transform

* `make_colors.m` - defines some colours for plotting

* `OrientationMapsJi.mat` - Matlab data file with orientation maps J

* `MapShiftVals.mat` - 5 map locations used in study 

LaTeX Citation:

```
...
```
