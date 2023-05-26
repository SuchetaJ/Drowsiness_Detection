# Drowsiness_Detection

To detect drowsiness base on the eye aspect ratio. The model calculates the eye aspect ratio for each frame and if the eye aspect ratio is less than a certain threshold (0.20 here) for consecutively 15 frames we declare that the person is drowsy during that time.

The notebook drowsiness_detection_list takes as input a list of images, check for each image if the EAR is less than the threshold, if this happens consecutively 5 times for a list of images then the model declares that the person is drowsy.
