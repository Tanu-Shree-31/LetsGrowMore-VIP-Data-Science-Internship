# Photo-Sketching
A small code that can convert an image to a pencil sketch like image. An image is basically an array of numbers to Python. So we can perform a variety of matrix manipulations to get some very interesting results. This code shows how to reduce an image into a ‘pencil’ outline.

# Problem given
![image](https://user-images.githubusercontent.com/69342524/128593609-fe024dfb-ee0e-42e4-a2ea-b783d0aa63cf.png)

# Steps Followed:
- Importing the required libraries
- Loading the original image
- Converting an original image into gray_scale image
- Inverting the image
- Smoothing the image
- Dodge these two images(gray and inverted images). These two images reinforces some edges and complements some edges. Alternatively, these two images can be blended with different weights
- Show the image and wait for a keystroke to close the display

# Results:
![image](https://user-images.githubusercontent.com/69342524/128593513-d12b3098-4232-44f6-8f19-919f28013664.png)
