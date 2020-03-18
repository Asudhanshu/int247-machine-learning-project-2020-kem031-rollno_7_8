Project:----****Painting style transfer to selfies and other photos OR Neural style transfer****

**Concept:**
Neural style transfer is an optimization technique used to take two images
—a content image and a style reference image (such as an artwork by a famous painter)
—and blend them together so the output image looks like the content image, but “painted” in the style of the style reference image.

**Technique:**
This is implemented by optimizing the output image to match the content statistics of the content image and 
the style statistics of the style reference image. These statistics are extracted from the images using a convolutional network.

**Example:**
![Content](https://raw.githubusercontent.com/Lovely-Professional-University-CSE/int247-machine-learning-project-2020-kem031-rollno_7_8/master/outputs/3/content3.jpg)
![Style](https://raw.githubusercontent.com/Lovely-Professional-University-CSE/int247-machine-learning-project-2020-kem031-rollno_7_8/master/outputs/3/style2.jpg)
![output](https://raw.githubusercontent.com/Lovely-Professional-University-CSE/int247-machine-learning-project-2020-kem031-rollno_7_8/master/outputs/3/100.png)
![output](https://raw.githubusercontent.com/Lovely-Professional-University-CSE/int247-machine-learning-project-2020-kem031-rollno_7_8/master/outputs/3/200.png)
![content](https://raw.githubusercontent.com/Lovely-Professional-University-CSE/int247-machine-learning-project-2020-kem031-rollno_7_8/master/outputs/Jon%20snow/content6.jpg)
![style](https://raw.githubusercontent.com/Lovely-Professional-University-CSE/int247-machine-learning-project-2020-kem031-rollno_7_8/master/outputs/Jon%20snow/style6.jpg)
![output](https://raw.githubusercontent.com/Lovely-Professional-University-CSE/int247-machine-learning-project-2020-kem031-rollno_7_8/master/outputs/Jon%20snow/Figure_3.png)
![output](https://raw.githubusercontent.com/Lovely-Professional-University-CSE/int247-machine-learning-project-2020-kem031-rollno_7_8/master/outputs/Jon%20snow/Figure_5.png)
