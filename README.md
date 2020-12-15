# FaceDetection and Anonymization
It uses **Haar features** framework implemented in OpenCV to detect mainly faces positions and eyes position. It uses then this information to add different accessories to the faces ( moustache, eyes etc).

## Dependencies

* OpenCV(3.2.0)
* Python 2.7x

## Currently detection are available:
* Detect Faces
* Detect Eyes

## Currently following filters are available:
* GaussianBlur ( Bluring )
* MedianBlur ( Bluring )
* Bilateral Filter ( Bluring )

## Currently it is possible to add these different accessories:
* Moustache Filter
* Eyes Filter
* Black eyes Filter

## How to run the program
* Press a to detect face
* Press b to detect eyes
* Press c to apply GaussianBlur Filter
* Press d to apply MedianBlur Filter
* Press w to apply Bilteral Filter
* Press h to add a moustache 
* Press f to anonymize the eyes with black boxes
* Press g to add eyes 👀 
* Press s to save the image in your computer
