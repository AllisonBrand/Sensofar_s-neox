# Sensofar_s-neox
Utilities for thickness and surface mapping using s-neox.

Interpolates z focus positions found with manual focusing over the wafer or coupon. This avoids the need for autofocus, which was struggling with the rough surface of my transparent substrate (Sq = 0.79 um surface roughness, areal RMS).  Generates a .csv of XYZ postions which can be uploaded in MMR mode. It allows for a sparse grid unlike extended measurement mode, mapping out the wafer thickness at a useful resolution while reducing measurment time and file size, with 0.3 um resolution surface topography samples at every grid point.

I vibe-coded this for my transparent 10-20 um thick (backside thinned) 4H-SiC sample bonded with translucent CrystalBOND 590. 
