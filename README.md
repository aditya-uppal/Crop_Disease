# Crop_Disease
A Deep Learning model to detect vulnerablities and diseases in a variety of crops/plants
The input is a video feed and the output is if the given crop is diseased or not.
The first step is using a YOLOv5 to detect which frames contain valuable leaf information, followed by a VGG-19 classifier using the leaf information to make predictions on the diseases
