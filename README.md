# Computational-Imaging-Metrology
3D objects to be used to benchmark Computational Imaging Systems (CT, MRI, etc)

Those charts were designed to allow bencmarking of a computational Imaging system end-to-end. The objects are designed in such a way, when scaned and recostructed, a 'frequency response' of the system can be inferred. The idea is to get a reconstructed image that looks like a Siemens Star and allows measurments.

## CI Density Chart: 
The geometry of this chart is such that a reconstructed slice, will have every point relative density proportional with its distance to the centre of the chart - this is because the height of the chart is equal with its radius and thus, by finding the radius we find the density. The centre is 0% density for odd slices and 100% density for even slices - similarly, the edge is 100% density for odd slices and 0% density for even slices.

The chart needs to be aligned parallel to the slicing plane.

## CI Frequency Chart:
The geometry of this chart is such that it requires no precise alignment - after the slices are computed, there will be one slice with a cirle that has the biggest diameter - this slice is the one that will be used to measure the system.
