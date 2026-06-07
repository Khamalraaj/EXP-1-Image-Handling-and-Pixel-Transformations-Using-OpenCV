# Image-Processing-with-OpenCV

## AIM

To write a Python program using OpenCV to perform image handling and pixel transformation operations such as reading and displaying images, adjusting brightness and contrast, performing geometric transformations, and applying bitwise operations.

## REQUIREMENTS

Python 3.7 (Anaconda recommended)
Jupyter Notebook
OpenCV (cv2)
NumPy
Matplotlib

## DESCRIPTION

This project demonstrates the basic concepts of image processing using the OpenCV library in Python. Initially, an image is loaded from the local directory and displayed using Matplotlib. The properties of the image such as height, width, and number of channels are obtained to understand its structure.

Various geometric transformations such as cropping, resizing, and flipping are applied to modify the image. These operations help in extracting regions of interest and changing the size and orientation of the image.

The project also includes image annotation, where text is added and shapes like rectangles are drawn to highlight specific objects in the image. This is useful in applications like object detection and image labeling.

Brightness and contrast adjustments are performed to enhance image quality. Brightness is controlled by adding or subtracting pixel values, while contrast is modified using scaling factors.

Further, the image is split into its individual color channels (Blue, Green, Red) and then merged back to reconstruct the original image. The HSV color model is also explored by splitting and merging its components (Hue, Saturation, Value).

Finally, bitwise operations are applied to generate transformed images, demonstrating how pixel-level manipulations can be performed effectively.

## STEPS / ALGORITHM

1)Read the image from the local directory using OpenCV.
   
2)Display the image and print its dimensions (height, width, channels).

3)Save the image in PNG format and reload it as a color image.

4)Crop a specific region of interest from the image.

5)Resize the image by scaling it to twice its original size.

6)Flip the image horizontally.

7)Load another image and perform annotation by adding text and drawing a rectangle.

8)Read a new image and create a matrix to adjust brightness.

9)Generate brighter and darker versions of the image.

10)Modify the contrast of the image using scaling factors.

11)Split the image into Blue, Green, and Red channels.

12)Merge the B, G, R channels to reconstruct the image.

13)Convert the image to HSV format and split into H, S, V channels.

14)Merge the HSV channels back to form the image.

15)Apply bitwise operations to generate a new processed image.

## OUTPUT


## Display of grayscale and color images


<img width="605" height="502" alt="Screenshot 2026-04-28 092757" src="https://github.com/user-attachments/assets/d948dc75-0dbc-4a60-aa8a-f5f78bad447c" />
<img width="604" height="503" alt="Screenshot 2026-04-28 092805" src="https://github.com/user-attachments/assets/622c67f5-1f2d-42cd-84d9-339acdbf38b9" />


## Cropped, resized, and flipped images


<img width="627" height="502" alt="Screenshot 2026-04-28 092814" src="https://github.com/user-attachments/assets/17c18f90-7d4e-4691-acda-d35a40ca9044" />
<img width="605" height="502" alt="Screenshot 2026-04-28 092823" src="https://github.com/user-attachments/assets/38f45426-404a-4da0-920c-0b66e4276858" />
<img width="621" height="511" alt="Screenshot 2026-04-28 092919" src="https://github.com/user-attachments/assets/d319d8ef-f28f-44ce-964c-e3bb6f47b039" />


## Annotated image with text and rectangle


<img width="642" height="390" alt="Screenshot 2026-04-28 092929" src="https://github.com/user-attachments/assets/351c16aa-40bd-4642-ae6b-3b4e677ce2c6" />


## Brightness adjusted images (brighter and darker)


<img width="1085" height="321" alt="Screenshot 2026-04-28 092936" src="https://github.com/user-attachments/assets/83b471c7-bd6c-4434-abb3-d22b672e2814" />


## Contrast enhanced images


<img width="1053" height="305" alt="Screenshot 2026-04-28 092941" src="https://github.com/user-attachments/assets/762c47d3-36e5-472d-985e-378b628fc494" />


## Individual B, G, R channel images (in grayscale)


<img width="711" height="537" alt="Screenshot 2026-04-28 093939" src="https://github.com/user-attachments/assets/8040673a-3b19-4330-a553-87b10a80ee00" />
<img width="688" height="544" alt="Screenshot 2026-04-28 093945" src="https://github.com/user-attachments/assets/41830e11-401a-4754-8edc-0468ffaf5c37" />
<img width="691" height="529" alt="Screenshot 2026-04-28 093953" src="https://github.com/user-attachments/assets/2e98967e-0c4c-4e33-a544-1e47229eeab8" />


## Reconstructed color image from merged channels


<img width="633" height="512" alt="image" src="https://github.com/user-attachments/assets/e7fe7e97-75d0-4582-96fc-e00dd611a37d" />


## HSV channel images


<img width="686" height="532" alt="Screenshot 2026-04-28 093242" src="https://github.com/user-attachments/assets/e5e3191b-5859-45c8-a92e-f88dc02af03c" />
<img width="686" height="539" alt="Screenshot 2026-04-28 093247" src="https://github.com/user-attachments/assets/1b10ea99-9c1c-4710-8e03-13d705bd4439" />
<img width="685" height="548" alt="Screenshot 2026-04-28 093304" src="https://github.com/user-attachments/assets/7e0f15e1-e2d3-458b-96b2-a50b5eff0568" />



## Merged Final Image


<img width="630" height="510" alt="Screenshot 2026-04-28 093313" src="https://github.com/user-attachments/assets/9ad6ea96-f1c2-4cac-87a1-764963b6ac1c" />

## RESULT

Thus, the Python program for image handling and pixel transformations using OpenCV was successfully implemented. The operations such as image reading, transformation, brightness and contrast adjustment, channel manipulation, and bitwise processing were carried out successfully.
