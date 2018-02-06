# sbfsem-cardiac-cell-segmenter-v2

A matlab program to automatically segment cardiac ultrastructure from serial block-face scanning electron microscopy (SBF-SEM) data.

Required Applications/Packages
MATLAB

File and Folder Information
main.m: The main script file which the user edits and executes in matlab for running the automatic segmentation algorithm.

code: The folder that contains the codes for automatic segmenation of the SBF-SEM cardiac cell data.

sample contains a sub-stack of 52 image slices of the raw sbfsem data, and manual segmentation for execute the program as an example.

Due to file-size limitations on github, we request those interested in access to our high resolution raw and segmented data to directly contact the corresponding author, Vijay Rajagopal, at vijay.rajagopal .at. unimelb.edu.au.

Running the program
Open main.m and edit the settings parameters to customise to your dataset.
Run main.m
Folders for different organelle components will be automatically created and tiff images of the resulting segmentations will be saved in them.
Input image files should be in tiff format. Explanations of the settings parameters are given within main.m.
