# CV-COLOR-DETECTION-HSV
Color detection using opencv and hsv parameters
# LOGIC
1. first create hsv ranges for all colors(trackbars can also be used) and then create threshold values for them using inRange. 
2. then  create mask  of every color which will be highlighted on test image using bitwise_and.
3. finally  draw bounding contours around required color.
