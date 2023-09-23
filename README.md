# Image processing using OpenCV
### Code Description:
![Screenshot (8)](https://github.com/kareemmaged/kareemmaged/assets/124416540/9f52f346-db85-4a8a-936b-acdfd64e7ce5)
First, we run Jupyter Notebook by using the Command Prompt
![Screenshot (3)](https://github.com/kareemmaged/kareemmaged/assets/124416540/c30894a3-b355-43c4-8665-28cbd0665cb1)
Write the code in line [1] to install OpenCV library

Used in line [2] import cv2 for package installation

![Screenshot (4)](https://github.com/kareemmaged/kareemmaged/assets/124416540/0903f718-48f0-40b5-b223-4366f2bd4872)

In line [5] img ( variable for installing images)

cv2 ( our package )

imread ( function for reading an image )

Line[7] imshow command (function for displaying image)

Now the image already appeared but also disapeared immediately, the 
solution is using command in line [8] [ cv2.waitKey(0) ]

The 0 means appear image for unlimited time.
 Also the time between brackets is in milliseconds ,
 for example (2000) = 2 seconds

 ![Screenshot (7)](https://github.com/kareemmaged/kareemmaged/assets/124416540/7e6b6d3a-cf54-43a0-97c6-10ab15282ce8)
Line [55] I used numpy library to be able to use kernel (to be 
able to work with arrays).

### Sharpening Images
![Screenshot (9)](https://github.com/kareemmaged/kareemmaged/assets/124416540/d523a462-0034-4495-acd6-a1bf7e28f8ff)

-The idea behind sharpening images is you need to
make a bigger difference between the central pixel and all its 
neighboring pixels. How to do it? Simply by making the numbers 
negative in the filter values and then more positive in the central 
pixel value. 
### NOTE
* if you add all the (-1) s the answer will be (-4), so the central 
value must be greater than ( 4 ) otherwise the image will be 
black

## Final Result
![Screenshot (10)](https://github.com/kareemmaged/kareemmaged/assets/124416540/4c74837c-fd0f-4667-9d17-1ece9fdff84e)

