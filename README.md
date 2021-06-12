# Surround-view-camera-system-for-ADAS
An introduction to building a Surround view camera system for ADAS using opencv, numpy
For obtaining the surround view we have used 8 wide angle cameras with a field of view of each camera of 110°. 
Then, for getting the perspective view (top view) of these images we have used homography transformation wherein every image is converted into a perspective view.
Now, to obtain different view we have stitched each sides’ images.
In order to display all the surrounding views to the driver we project all the views in a single image.
