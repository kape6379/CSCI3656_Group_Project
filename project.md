# Group Project: Interpolation on Topographic Data using SciPy
Eben Fluto, Kai Schuyler Gonzalez, Kate Pendavinji, Richard Terrile
## Background
(Brief description of what everyone originally did and why we decided to do the experiment we did)

Eben:

Kai:

Kate: 

Richard:

## Key Problems
(Discuss scipy package)

## Stakeholders
(who made scipy)

## Metrics and Features
Scipy has a sub-package dedicated to interpolation. Scipy.interpolate offers functions that can interpolate in many dimensions utilizing various. For our project we utilized three functions. 
- # scipy.interpolate.NearestNDInterpolator
	<p> This function performs a simple nearest neighbors interpolation in any dimension.</p>
- # scipy.interpolate.LinearNDInterpolator
	<p> This function performs a piecewise barycentric linear interpolation in any dimension. For our example we can think of this in the following. If we have all our points in 3d this function is going to connect all these points together by constructing a triangular grid. Then when we wish to get the value for a new point within a certain triangle in the grid we take the weighted average of the objective values at the three vertices based on distance.  Here is an image that helps visualize this process. </p>
- # scipy.interpolate.CloughTocher2DInterpolator
	<p> This works similar to the linear interpolator. It triangularizes the data but interpolates points within using bezier polynomials.

## Experiment
(insert images descerbe what they mean)

