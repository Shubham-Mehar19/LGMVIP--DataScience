
# Image to Pencil Sketch with Python using cv2 library

<img src = "BEGINNER LEVEL TASK/TASK 4/image to pencil sketch.png"/>

![App Screenshot](https://cdn-media-1.freecodecamp.org/images/1*cFcDUhcYTBx4AtGpXzeyXw.png)

The term Computer Vision (CV) is used and heard very often in artificial intelligence (AI) and deep learning (DL) applications. The term essentially means giving a computer the ability to see the world as we humans do.

Computer Vision is a field of study which enables computers to replicate the human visual system. As already mentioned above, It’s a subset of artificial intelligence which collects information from digital images or videos and processes them to define the attributes. The entire process involves image acquiring, screening, analysing, identifying and extracting information. This extensive processing helps computers to understand any visual content and act on it accordingly. 

Computer vision projects translate digital visual content into explicit descriptions to gather multi-dimensional data. This data is then turned into a computer-readable language to aid the decision-making process. The main objective of this branch of artificial intelligence is to teach machines to collect information from pixels. 

Source of info:-https://www.mygreatlearning.com/blog/opencv-tutorial-in-python/#sh1


- Step 1
We need to read the image in RBG format.

- Step 2
Converting image to a grayscale image. This will turn an image into a classic black and white photo.

- Step 3
 Then the next thing to do is invert the grayscale image also called negative image, this will be our inverted grayscale image. Inversion can be used to enhance details.
 
 - Step 4
 The blurring of an image means smoothening of an image i.e., removing outlier pixels that may be noise in the image.

 - Step 5
  Then we can finally create the pencil sketch by mixing the grayscale image with the inverted blurry image. This can be done by dividing the grayscale image by the inverted blurry image. Since images are just arrays, we can easily do this programmatically using the divide function from the cv2 library in Python.
