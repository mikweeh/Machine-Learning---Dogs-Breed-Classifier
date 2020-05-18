Dogs breed classifier with CNN

This is the last project from "Machine Learning Engineer" Udacity's nanodegree.

The scope of this project is clearly defined since it is one of the pre-established options that Udacity provides. In this sense, the project consists, broadly speaking, in developing a convolutional neural network model (CNN) that, from an image given by the user, is capable of identifying the dog breed that appears in the image.

It also needs to be able to identify if a human is detected in the image, and then it will provide an estimate of the dog breed that is most resembling.

The project is developed on jupyter notebook. To run it you will need the original notebook (dog_app.ipynb). You will also need to have a folder with the data (images) of dogs and people. This folder will be in the same directory as the dog_app.ipynb file.

You can download the dog images from here: https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip

You can download the images of people from here: https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip

In this project, we use OpenCV's implementation of Haar feature-based cascade classifiers to detect human faces in images. OpenCV provides many pre-trained face detectors, stored as XML files on github (https://github.com/opencv/opencv/tree/master/data/haarcascades). You will need to download one of these detectors (i.e. haarcascade_frontalface_alt.xlm) and put it in a folder (folder's name --> haarcascades).

At the end of the document, some tests are carried out with your own photos. You should have a folder called "final_test_images" with the images you want to test.

Throughout this project, two CNN models are trained, one from scratch and the other pre-trained. Once you've executed one time, if you want to skip this step, you must NOT execute the two cells corresponding to the training, and directly execute the next one that loads the model.
