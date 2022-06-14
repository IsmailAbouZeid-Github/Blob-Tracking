# Blob-Pushing
Source code of a Blue blob tracking/pushing algo using OpenCV & Moveit!.

The code is works for the most part; however, it will be improved with the future use of services to declare arm states "push/dont push".
The code is capable of detecting and following a blob but if the blob is not in-view at all times, errors arise.

HSV color filtering is used then a mask is applied which produces a frame showing the area of designated color.
The HoughCircle function is then called to detect the circular shape of the blobs and their radii.  
