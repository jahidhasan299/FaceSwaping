# FaceSwaping
# THE STEPS ARE TAKEN TO COMPLETE THIS PROBLEM
1. Download the pre-trained model for shape predictor.
2. Creating a function for extracting the index.
3. Load the source and destination image from the internet.
4. Converting the image into numpy array.
5. Converting image into greyscale for better results.
6. Load face detector and face landmarks predictor using dlib.
7. Perform triangulation on the image to cut out the face.
8. Create empty masks for images.
9. Swapping the images for the face onthe destination image
10. Using seamless cone for adjusting color scheme.

# Face Swap
1. In this project, we will be using opencv and dlib to extract faces of human-beings from a given image. We will use a pretrained model to extract landmarks from the faces.

2. We will use DLIB for this project and it's landmark's facial detector with pre-trained models, dlib is used to estimate the location of coordinates(x,y) that map the facial points on a person's face.

3. This project can be used for learning and understanding different concepts for computer vission. It's used to build Augmented Reality Applications like Snapchat.

# Conclusion
We started with downloading the pretrained model for face landmark and download the images from the internet on which we will work. Next we used CV2 and Dlib for preprocessing the images and used different functionalities to make reach to the end which is swapping the face of destination image with source image.

# Scope
This project can be used for learning and understanding different concepts of computer vision. This project can be use to build Augmented Reality applications like Snapchat, etc.

# Results:
<img width="1429" alt="Screen Shot 2022-06-01 at 11 13 33 AM" src="https://user-images.githubusercontent.com/49092540/171321426-2bef306b-58c7-4a75-9056-1825b5df31c5.png">
<img width="1429" alt="Screen Shot 2022-06-01 at 11 13 39 AM" src="https://user-images.githubusercontent.com/49092540/171321440-770e62a0-1804-4bc5-9ed4-fd1ff1ca28c5.png">
