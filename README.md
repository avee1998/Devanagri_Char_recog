# Devanagri_Char_recog
1. Devanagri character recognition using CNN
2. Taught very well at Eckovation Machine Learning Course(https://www.eckovation.com/course/machine-learning-value-package ),
   This code helps you classify different alphabets of hindi language (Devanagiri) using Convnets.
3. The techniques used are Deep Neural networks for prediction and OpenCV for pre-processing of images.
4. For pre-processing we read the images in grayscale format for 2-D images rather than 3-D (if we read in RGB).
5. We trained the model on images after resizing it to 32x32x1.
6. The Basic Architecture of Project :
 	 Conv -> MaxPool -> Conv -> MaxPool -> Flatten -> Dense -> Dense ->O/P
7. Due to some problems with my system i have used Theano Backend and Keras for the implementation.
8. Accuracy:
  a) Train(78,200 images) :96.2
  b) Test  (13,800 images) :95.4 
9. Some add-ons:
  One can add more layers.
  More epochs(8 used) can be used.
  Regularisation param can be tweaked to avoid overfitting.
  More images if available will be enhancement for accuracy.



CASE: 
1. This project can be useful for getting insight to CNN and Deep Neural networks, also for a decent intuition to Opencv for image processing and optimise the task of training.
2. Also this can be further used to Recognise hindi words from an image after we are able to detect the word in an image and segment it into individual characters and then again uniting them to form a word making it easy for image-to-text reading.

The link for the Dataset at UCI-ML Repository.
(https://archive.ics.uci.edu/ml/datasets/Devanagari+Handwritten+Character+Dataset )
