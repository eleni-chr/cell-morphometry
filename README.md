# cell-morphometry

Morphometric analysis of cells in microscopy images.

*README written by Eleni Christoforidou*

Disclaimer: The code provided in this toolkit has not been peer-reviewed and is subject to errors. Users are encouraged to thoroughly test the code and verify its accuracy for their specific use cases. The author of this code is not responsible for any errors or inaccuracies in the results obtained from using these functions. Additionally, the code may be subject to updates or modifications, and users should keep an eye out for future releases to ensure the most accurate and up-to-date functionality.

REQUIREMENTS: Single-channel, single-frame images in TIFF format. Each image contains a single cell whose full structure is visible (by labelling with phalloidin, for example).

INSTRUCTIONS:

1. Run the MATLAB function **morphology.m**, which calculates the following parameters:
- Cell area
- Cell perimeter
- Cell circularity
- Cell eccentricity (shows how much of an elliptical shape the cell has)
- Cell extent (the ratio of pixels in the object to pixels in the total bounding box [i.e., how far the cell extents])
- MajorAxisLength
- MinorAxisLength
- Fractal dimension
- Convex hull area
- Convex hull perimeter

2. Run the MATLAB function **visInspect.m** to visually inspect each image to check how the previous function performed.
