# CV-COLOR-DETECTION-HSV
Color detection using opencv and hsv parameters
# LOGIC
-first create hsv ranges for all colors(trackbars can also be used) and then create threshold values for them using inRange.
-then  create mask  of every color which will be highlighted on test image using bitwise_and.
-finally  draw bounding contours around required color.
