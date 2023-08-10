# Pencil Sketch Generator

This repository contains a Python script that converts a regular photograph into a pencil sketch using image processing techniques. The script utilizes the OpenCV library to perform various transformations and create the final pencil sketch effect.

## How it Works

The provided Python script performs the following steps:

1. **Loading and Displaying the Original Image**: The original image is loaded from the file and displayed.

2. **Converting Image to RGB Format**: The loaded image is converted to the RGB format for correct visualization.

3. **Converting Image to Grayscale**: The RGB image is converted to grayscale, which is a single-channel image representing the intensity values of the original image.

4. **Inverting the Grayscale Image**: The grayscale image is inverted to create a negative effect.

5. **Applying Gaussian Blur**: A Gaussian blur is applied to the inverted grayscale image. This step helps smoothen the image and reduce noise.

6. **Inverting the Blurred Image**: The blurred image is inverted again.

7. **Creating the Pencil Sketch**: The final pencil sketch is created by dividing the original grayscale image by the inverted blurred image. This produces a pencil sketch-like effect.

8. **Saving and Displaying the Pencil Sketch**: The pencil sketch is saved to a file named "Final_pencil_sketch.png" and is also displayed.

## Example

Here's an example of the input and output images:

Input Image             |  Pencil Sketch Output
:-------------------------:|:-------------------------:
![Input Image](http://localhost:8888/view/PicsArt_02-28-09.06.27.jpg)  |  ![Pencil Sketch](Final_pencil_sketch.png)

## Contributing

Contributions to this repository are welcome! If you have any improvements or ideas, feel free to submit a pull request.
