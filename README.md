# Face_Mask_Detection
Simple model to detect whether a person is wearing a mask or not. 

Libraries:
  Tensorflow
  Opencv
  Numpy
  Matplotlib.pyplot
  
  
Harcascade classifier is used to detect face. The face is cropped and passed into Conv2D model ,to detect the mask and give a binary output.

Data:
  Find mask and without_mask dataset and use it to train the model, Change the path accordingly.
