# SignLanguageTranslator
Translating Sign language in real time
This project was done with team for EPICS project (Engineering project in Community Services).

I was handling the part of real time data collection.

In this repository I'm uploading my code file of how I collected real time images through web cam.
For the project we tried to find already made datasets but we couldn’t find
dataset in the form of raw images that matched our requirements. All we	could find were the datasets in the form of RGB values.
We wanted to deal with raw images and that too square images as CNN in Keras as it was a lot more convenient working with only square images. We couldn’t find any existing dataset for that hence we decided to make our own dataset.
Hence,  We are collecting our own dataset for training and testing of our model.
Here, we are converting sign language into text therefore at first we required a photo with different signs  to take refrence for hand sign of letters in ASL.



#Some image how our interface works:
![image](https://user-images.githubusercontent.com/80167074/195491350-4fe2482d-8d62-48cd-8a11-97b6c2091015.png)


So. When we run our datacollection program it’s starts capturing input through our system’s webcam. It captures our hand sign  if we press the respective letter keys on our keyboard. 
Like if I make hand sign of B and press  B key on my keyboard then it will capture lot of images and store it in the  folder of  B created earlier. 
So, Like this we collected images of all the signs and prepared our dataset. 

No. of time of press equals no. of images.





