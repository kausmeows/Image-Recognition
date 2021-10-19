# Image-Recognition
Manipulating images using numpy, Cascade Classifier and OpenCv

## image.ipynb file consists of the code which converts a normal image to RGB type and some other basic image manipulation

## face.ipyng file extracts the face from the photo and recognizes the facial part by putting a rectangle on it.

If we take the original image like this -

![The image](doctor_strange.jpg)

Some manipulations are done to extract just the face of the given image...

![image](https://user-images.githubusercontent.com/82315953/137709868-1abb6613-f22b-4720-ac1d-4d8f45bd87ff.png)

The face is then detected by using the Casscade Classifier's Haarcascade dataset and then a rectangle is formed around the image using OpenCv

![image](https://user-images.githubusercontent.com/82315953/137708914-a440003d-ba7a-4de5-8aaf-7cf93628c3b4.png)
