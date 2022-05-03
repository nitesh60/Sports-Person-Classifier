# Sports-Person-Classifier

# Face Detection using Haar Cascades
Goal
We will see the basics of face detection using Haar Feature-based Cascade Classifiers
We will extend the same for eye detection etc.

# Haar-cascade Detection in OpenCV is used to 
OpenCV comes with a trainer as well as detector. If you want to train your own classifier for any object like car, planes etc. you can use OpenCV to create one. Its full details are given here: Cascade Classifier Training.

Here we will deal with detection. OpenCV already contains many pre-trained classifiers for face, eyes, smile etc. Those XML files are stored in opencv/data/haarcascades/ folder. Let’s create face and eye detector with OpenCV.

First we need to load the required XML classifiers. Then load our input image (or video) in grayscale mode.

Now we find the faces in the image. If faces are found, it returns the positions of detected faces as Rect(x,y,w,h). Once we get these locations, we can create a ROI for the face and apply eye detection on this ROI (since eyes are always on the face !!! ).

# Some OutPut Images
![alt text](https://github.com/nitesh60/Sports-Person-Classifier/blob/master/UI/Screenshot%20(112).png?raw=true)
