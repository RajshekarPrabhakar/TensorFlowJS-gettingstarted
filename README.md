# TensorFlowJS Getting Started Code
This code runs on your browser (Google Chrome / Mozilla Firefox / other modern browser supporting Java Script).
In this code you can build your own Image classifier by traning the model on images from webcam.
Currently this code consists of options to train 4 different classes, which can be easily extended to many more.

# How to run this code?
1. Just download the two files:</br>
  a. index.html</br>
  b. index.js</br>
2. Open index.html file in one of the modern browsers like Chrome / Firefox
3. Allow webcam access
4. Show some object or pose to webcam and click "Add A" button - do this for same pose / object from different angles (5 to 10 images should be enough)
5. Change the object or pose and click "Add B" button...
6. Repeat for Add C and Add No Action buttons
7. The classifier will show </br>
    prediction: A (Category)</br>
    probability: 0.6 (0 to 1)</br>
8. If the classifier accuracy is not good, just add more images to those categories with low probability / incorrect.

# Can I save this model and use it later?
I believe it is possible, this is my first TensorFlow.js code, I am yet to figure that out. 

# Will this code upload my webcam pictures?
No, this code does not upload any images to internet. All the processing, model and images reside on your computer/mobile device.
