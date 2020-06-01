# CannyEdgeDetection
This project is for ENGR7761 Image Processing and is a student project to help re-construct OpenCV's Canny function.

README FILE	AUTHOR: JOSEPH NUTT	FAN:NUTT0012	SRN:2167074

OVERVIEW
This readme file is for the ‘MyCannyEdgeDetection.ipynb’ file. The format of this 
file is a Jupyter Notebook, developed using Python (Version 3.7.4) on a Windows 10 
machine leveraging the Jupyter IDE.

EVIRONMENT SETUP
The default ANACONDA Python distribution was used for the development of this 
project with the following native modules being used:

	- numpy
	- matplotlib

ADDITIONAL THIRD-PARTY MODULES REQUIRED: (will require install)

	- OpenCV – version 3.4.9.31

EDITS YOU MUST MAKE BEFORE RUNNING CODE:
There are two variables you must set before executing the code. Both are the 
directory locations of the image you wish to process. These variables are declared 
separately so that code segments running the experimental and OpenCV Canny edge 
detection algorithms could be run independently of one another.

Variable Names:

	image = cv2.imread('INSERT IMAGE LOCATION HERE',0)  eg. ‘C:/User/myFile/image.jpg’

	originalImage = cv2.imread('INSERT IMAGE LOCATION HERE',0)	eg. ‘C:/User/myFile/image.jpg’
