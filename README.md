# Sentinel-2-image-match
For the solution I used LightGlue model from Kornia. This lib provides an easy way to achive task using pretrained model. In case i used pretrained model, dataset is not needed, but for test i used "Deforestation in Ukraine from Sentinel2 data" from kaggle, which was mentioned in the task. 
In the tests i saw good performance on images from similar seasons:
![image](https://github.com/user-attachments/assets/8244f7ff-c3bd-4bc5-9c95-f7142affd8b3)

and acceptable performance when one image is snowy and other is not:
![image](https://github.com/user-attachments/assets/0e2390c1-e6b0-4777-9fb6-933e0e857032)

Notebook adapted for Sentinel2 images, but can be easily used with any type of images. 
