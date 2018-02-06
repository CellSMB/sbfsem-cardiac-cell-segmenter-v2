# sbfsem-cardiac-cell-segmenter-v2

A matlab program to automatically segment cardiac ultrastructure from serial block-face scanning electron microscopy (SBF-SEM) data.

Required Applications/Packages
MATLAB

File and Folder Information


code.zip: it contains main.m and other m files under code folder. 
	main.m: The main script file which the user edits and executes in matlab for running the automatic segmentation algorithm.
	code: The folder that contains the codes for automatic segmenation of the SBF-SEM cardiac cell data.

a sample image files will be found in https://cloudstor.aarnet.edu.au/plus/s/TNu7hTrGdZIRVWl
Due to file-size limitation, we cannot upload this sample images here. We request those interested in access to our high resolution raw and segmented data to directly contact the corresponding author, Vijay Rajagopal, at vijay.rajagopal .at. unimelb.edu.au.

Running the program
Open main.m and edit the settings parameters to customise to your dataset.
Run main.m
Folders for different organelle components will be automatically created and tiff images of the resulting segmentations will be saved in them.
Input image files should be in tiff format. Explanations of the settings parameters are given within main.m.
