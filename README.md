PkView
======

Viewer for 3D/4D data and Pk modelling


### Usage

1) Start Viewer:
![alt text](screenshots/1.png "Example 1")


2) Load image volume by either clicking the load image volume icon or File -> Load Image Volume :

![alt text](screenshots/2.png "Example 1")

3) Zoom into any image by scrolling the mouse wheel over an image. Move through the volume using the navigation sliders :

![alt text](screenshots/3.png "Example 1")


4) Load ROI using the Load ROI button:

![alt text](screenshots/4.png "Example 1")

5) and select file:

![alt text](screenshots/5.png "Example 1")

6) Toggle between ROI and ROI outline using "Image and ROI options":

![alt text](screenshots/6.png "Example 1")
![alt text](screenshots/7.png "Example 1")


7) Load a T10 map (currently doesn't create it's own T10 maps) using File -> Load Overlay Select:

![alt text](screenshots/8.png "Example 1")


8) Adjust image contrast by moving the greyscale range on the right hand side:

![alt text](screenshots/9.png "Example 1")

9) Change overlay transparency under the "Color Overlay" tab:

![alt text](screenshots/10.png "Example 1")

10) The "Voxel Anlysis tab" allows a number of enhancement curves to be analysed at once. Note that this only works for one axial slice at a time (Axis 1):

![alt text](screenshots/11.png "Example 1")

11) Once a DCE-MRI image, ROI, and T10 map has been loaded, Pk modelling can be run on the data inside the ROI. Note that this is run on a separate processor and the GUI can still be used for other interaction while PK modelling is running. Modelling can take a long time. 

![alt text](screenshots/12.png "Example 1")

12) Once Pk modelling is completed, new overlay will appear in the "Available Overlays" using the "Color overlay" tab. Toggle between them to view. Statistics and histograms can also be generated using the "Generate" buttons in this tab. 

![alt text](screenshots/14.png "Example 1")


13) Heat maps can be changed:

![alt text](screenshots/15.png "Example 1")

14) After Pk modelling, a comparison tool can be opened under: Widgets -> PharmaViewCompare . This plots the original data (red) and Pk model fitted curve (green) for any point clicked. 

![alt text](screenshots/17.png "Example 1")

Enjoy





