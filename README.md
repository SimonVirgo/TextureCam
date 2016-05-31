# TextureCam
This Repository contains a suite of tools to create grain maps of marbles (and maybe other materials such as etched metals) by analysing photos from various orientation of the surface.

lightsource very close to camera, direct orthogonal reflection

steps: 
1 create markers and stick them on the flat surface

2 take a reference image orthogonal to the surface

3 take a lot of pictures from different angles and orientations

4 affine transformation of each image to the reference image

5 find the orientation with the highest reflectivity for each location on the sample, store the vector and amplitude for this location

6 visualize , segment, be happy

ideally the software performs in real time with a live image stream from a camera and displays a stereonet to indicate what orientations are already covered!

keywords:
fast array manipulation, avoid loops in python,
ArUco Markers
