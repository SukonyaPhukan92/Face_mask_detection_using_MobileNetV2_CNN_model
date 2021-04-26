# Face_mask_detection_using_MobileNetV2_CNN_model

In the pandemic of Covid-19, the face has become a very important thing. The face Masks act as a physical barrier to protect from the transmission of the virus and bacterial particulates from one person to another. Masks are not only become an important thing, it becomes a live savior. But, many people refuse to wear masks as they are not used to that. For that reason, in public places like shopping malls, offices, etc., there have to assigned person to check whether people are wearing a mask or not. It will be trouble-free if this task is done by a machine i.e. if the camera itself can detect whether the person is wearing a mask or not. 

Here, I have transfer learning the pre-trained MobileNet V2 CNN model to detect whether the person is wearing a mask or not. To train the model, I have downloaded the dataset from Kaggle (https://www.kaggle.com/omkargurav/face-mask-dataset ), which consists of 3725 RGB images of with_mask and 3828 RGB images of without_mask.

![training loss and accuracy](https://user-images.githubusercontent.com/64634370/116096574-0820c480-a6c7-11eb-8ff9-f8733e05d1b5.png)

The model reached training accuracy 99% and validation accuracy 97%. 
