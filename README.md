For the solution, I used the LightGlue model from Kornia. This library provides an easy way to achieve the task using a pretrained model. Since I used a pretrained model, a separate dataset was not strictly necessary for training. However, for testing, I used the "Deforestation in Ukraine from Sentinel2 data" dataset from Kaggle, which was mentioned in the task. 
In the tests, I saw good performance on images from both similar seasons and when they are very different.
![image](https://github.com/user-attachments/assets/8244f7ff-c3bd-4bc5-9c95-f7142affd8b3)

![image](https://github.com/user-attachments/assets/0e2390c1-e6b0-4777-9fb6-933e0e857032)

Notebook adapted for Sentinel2 images, but can be easily used with any type of images. 
