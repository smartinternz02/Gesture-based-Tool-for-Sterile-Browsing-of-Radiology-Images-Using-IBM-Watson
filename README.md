# A Gesture-based Tool for Sterile Browsing of Radiology Images Using IBM Watson

In our project 
1. We have used CNN(Convolution Neural Network) to train the model using various images of different hand gestures.
2. Made a wweb application using flask where the user can upload the image which he wants to browse through. After the image is uploaded, the integrated webcam 
   is used to capture the video frame using OpenCV. The gesture captured in the frame is compared with the trained images and is identified.
if the prediction is,
0 - image converted to rectangle
1 - image is Resized into (200,200)
2 - image is rotated by 45॰ 
3 - image is blurred  
4 - image is Resized into (400,400) 
5 - image is converted into grayscale

3. We have also deployed the model on IBM Watson Studio

## Output
<pre>
Home page:                                              Introduction page:
<img src="https://github.com/DarshGupta1910/Images/blob/main/Intro.png"  width="400" height="200" />  <img src="https://github.com/DarshGupta1910/Images/blob/main/Intro.png" width="400" height="200" />

Model launch page:                                      Predicting results using Random Image:
<img src="https://github.com/DarshGupta1910/Images/blob/main/launch.png" width="400" height="200" />  <img src="https://github.com/DarshGupta1910/Images/blob/main/output1.png" width="400" height="200" />

                                                  Real Time Example:
                                <img src="https://github.com/DarshGupta1910/Images/blob/main/output2.png" width="400" height="200" />

</pre>
## Dataset 
- https://drive.google.com/file/d/19TYmAbZD1uDvoBJlXbTwosd_i0ibyLiD/view?usp=sharing

## Model Training and Testing
- https://drive.google.com/file/d/1uYexf8gLwqDxKRuUCAonM81mnIRxPoMv/view?usp=sharing

## Flask
- https://drive.google.com/drive/folders/1a6VhgaR2KZcKGkynQw4bOISLd3IT917m?usp=sharing


## IBM Deployment Files
- https://drive.google.com/drive/u/0/folders/1Pst64-F51OhD3qD-2Vkuc7TBcQ4WoI21

## Video Demonstration link
- https://www.youtube.com/watch?v=qC1SR3rWMiI
