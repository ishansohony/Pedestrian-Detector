# Pedestrian-Detector
Matlab implementation of the HOG PEDESTRIAN DETECTOR. 

runSingleWindowExample.m - Calculates the HOG descriptor for a single image that has been cropped down to the detector size.
getHOGDescriptor.m - Calculates the HOG descriptor for a given detection window.
getHistogram.m - Calculates the histogram for a single image cell.
trainDetector.m - Trains a linear SVM on the training images. There is also already a pre-trained model saved in hog_model.mat
runSearchExample.m - Applies a pre-trained HOG detector to a sample validation image, reports the detector accuracy, and displays the image with true positives drawn.
