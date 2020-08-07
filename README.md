# Aging_human_dermal_fibroblast_nucleus_DAPI

This image repository is for Nature Protocol paper(2020): *A robust unsupervised machine learning method to quantify the morphological heterogeneity of cells and nuclei*

Dataset Size: 1.96GB (Download time ~10min @ 100Mbps)

Sample Size:\
7 Ages : 3, 29, 35, 45, 55, 85, 96\
2 Technical repeat\
36 Images per repeat\
7 x 2 x 36 = 504 images total

Cell Count: 2300 cells\
AG04054_1 = 144\
AG04054_2 = 143\
AG04059_1 = 213\
AG04059_1 = 251\
AG08904_1 = 163\
AG08904_1 = 187\
AG09162_1 = 100\
AG09162_2 = 131\
AG09558_1 = 254\
AG09558_2 = 243\
AG11796_1 = 137\
AG11796_2 = 127\
GM05565_1 = 107\
GM05565_2 = 100

Analysis time with i9-10900K @4.8Ghz, CellProfiler 3.1.9, Windows 10\
CellProfiler segmentation: 10min\
Boundary detection from segmented image: 5min\
Building the model: 4sec\
Applying the model: 10sec
