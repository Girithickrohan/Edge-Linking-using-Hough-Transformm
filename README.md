# Edge-Linking-using-Hough-Transformm
## Aim:
To write a Python program to detect the lines using Hough Transform.

## Software Required:
Anaconda - Python 3.7

## Algorithm:
### Step1:

Import all the necessary modules for the program.
### Step2:

Load a image using imread() from cv2 module.
### Step3:

Convert the image to grayscale.
### Step4:

Using Canny operator from cv2,detect the edges of the image.
### Step5:

Using the HoughLinesP(),detect line co-ordinates for every points in the images.Using For loop,draw the lines on the found co-ordinates.Display the image.
## Output

### Input image and grayscale image

![output](https://raw.githubusercontent.com/Girithickrohan/Edge-Linking-using-Hough-Transformm/refs/heads/main/1.png)

![output](https://raw.githubusercontent.com/Girithickrohan/Edge-Linking-using-Hough-Transformm/refs/heads/main/2.png)

### Canny Edge detector output

![output](https://raw.githubusercontent.com/Girithickrohan/Edge-Linking-using-Hough-Transformm/refs/heads/main/3.png)

### Display the result of Hough transform

![output](https://raw.githubusercontent.com/Girithickrohan/Edge-Linking-using-Hough-Transformm/refs/heads/main/4.png)

## Result:
Thus, the program to detect the lines using Hough Transform implemented successfully.
