# Facial-Expression-Recognition

A deep neural network project created using Convolutional Neural Network (CNN) in keras from scratch to recognize facial expression in real time. The dataset consists of train and test data each containing 48x48 pixel grayscale images of faces. The objective is to classify each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral).


OpenCV is used to automatically detect faces in images and draw bounding boxes around them. Along with this, web interface is created to show video data on which real-time face recognition is performed. Once the CNN is trained, saved and exported, the trained model predictions is directly served to web interface and perform real-time facial expression recognition on video and image data. The CNN is trained on the GPU device using Tensorflow-gpu.

### Libraries Used:
* OpenCV
* Flask
* Tensorflow - Keras
* Tensorflow-gpu (along with CUDA, CUDNN and GPU driver to train model on GPU)

### Block Diagram of CNN
![Block Diagram of CNN](/model.png)

### Steps to run the project
* Download the project
* Run the Facial_Expression_Training python notebook to train the CNN
* Run main.py to start the server
* Go to localhost in browser to access web interface
