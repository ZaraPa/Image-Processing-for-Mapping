# Small Sample Size Instance Segmentation on Bird Images
###### Image processing for mapping purposes (014855) - Final Project

<p align="justify">
The project presents an approach from the NN’s field, that was discovered in the year 2018 called “An instance segmentation with Mask R-CNN”. The assignment was to successfully identify chosen objects in a given picture. More precisely we wanted to detect birds given a bunch of individual images s.t. every image was composed of parrots and different complicated backgrounds (bird houses, the cage itself, branches, and ropes).
</p>

There were two main choices for the project:
- <p align="justify"> Since the amount of data was relatively small, came the idea to use deep learning with the help of not only transfer learning but also a data augmentation. In more detail, transfer learning enabled to take the pre-trained weights of an already trained model and use these already learned features to predict new classes.</p>
- Since we wanted to detect all the birds in each image from the data set - the answer was using Instance segmentation with Mask R-CNN.

<br />
<p align="justify">
The main reason for the project was curiosity. Mainly to see the differences between regular image processing methods
(i.e. threshold with histogram-based methods) and Instance segmentation with Mask R-CNN. Also, I wanted to investigate whether the new approach can bypass or even overtake the downsides of regular image processing methods.
</p>

<br />

**How to run the code:**  (notice that your GPU is working)
1. Upload 𝐵𝑖𝑟𝑑𝑠𝑃𝑟𝑜𝑗𝑒𝑐𝑡.𝑖𝑝𝑦𝑛𝑏 to your google drive to My Drive.
2. Upload 𝐵𝑖𝑟𝑑𝑠𝐷𝑎𝑡𝑎 to your google drive to My Drive.
