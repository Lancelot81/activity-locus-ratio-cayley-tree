# activity-locus-ratio-cayley-tree

This Mathematica notebook provides a way to approximate the activity locus for Cayley trees.
Furthermore, it provides a way of finding the possible locations of points for which the spherical derivative tends to zero.

The notebook is set up in a way that makes it possible to spread out the computations over numerous days. It uses the import and export command to create files with the computed data.

My experience with the program is that computations tend to take a while when one tries to make plots with higher resolutions. The amount of iterations used does not seem to affect computation time as much.
The computation of the derivatives seems to take up most of the time. While I was able to calculate these derivatives for plots with a resolution of about 700.000 points, I do not recommend making the resolution much higher than 1 or 2 million points. But this is completely up to the user and will probably depend on the hardware used.
