# Face-Recognition-using-One-Shot-learning-technique-and-Siamese-Network.

 Model Training file contains developing and training model using one shot learning.

 test model.ipynb contain the testing model.

 siamesemodelv2.h5 is the trained model saved in h5 fromate.
 
 The h5 fiel link is here:  https://drive.google.com/file/d/1WcDyT0kXZD8-O2U6zSRSt4NbN_4Q7-J9/view?usp=sharing
 
 One shot learning needs 3 types of data for each class.
1.Positive:The image of the person whom we will dtetect
2.Negetive :The faces excluding the face we want to detect.
3.and Anchor.:Here Anchor is the dataste of images that contains the faces of registered people.
Main difference between posiive and anchor image is that anchor image is the input which is used to compare.And positive image is the image which is compared with the anchor image.
In short ,positive or negetive image is compared with anchor image and checked whether the iamge matched with anchor or not.
 
