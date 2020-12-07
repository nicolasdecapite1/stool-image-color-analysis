Image Detection of Red Colors(Blood) in Stool Images
===
Names: 
* Nick DeCapite
* Jin Zhou

## Timeline
Start Date: **May, 2020**

## Process

* Images
    * Blood
    * Concerning
    * Good

* CSV Files 
    * For Every Good and Blood image, the pixel concentration for each color in the ISCC system is recorded.
    * Done for all 267 colors and all 47 "red" colors.
* PCA Dimension Reduction
    * The color dimensions(267 or 47) are reduced to 10.

* KNN Analysis
    * Based on the reduced dimensions, the Good and Blood images are compared in order to create the the training and test models.
    * Currently, the highest accuracy at detecting the presence of blood is 72.22%.


## Future Steps

I will be working on fine-tuning the input paramaters to have a more accurate model. In addition, I will be testing out other machine learning techniques on blood detection.

Other than blood detection, I will be working with the concerning color images in order to create a process for the detection of these images.

