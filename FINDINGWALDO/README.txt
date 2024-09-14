finding waldo
 template matching using difference analysis

this project implements template matching using a difference analysis algorithm to find the best match of a template within
a given image. the algorithm slides the template across the image,computes a correlation score at each position,and identifies
the areas where the template best matches the image.


##features key
template matching: uses correlation to find the similarity between the template and various of the image.

high correlation indicator: when a high correlation value is found, a green bounding box is displayed, indicating the area 
of the image that closely matches the template.

low correlation indicator: a red bounding box is displayed around the areas with the lowest correlation,showing the least 
matching sections in the images.

how it works:
the algorithm moves the template across the entire image.at each position, a correlation score is calculated between the template
and the current section of the image.the highest score indicates the best match, and the lowest score indicates the least match.
the image is then annotated with green and red bounding boxes to visually indicate the best and worst matching areas,respectively.




##license
All right reserved. this project is not for public use or distribution without prior written permission from the owner.