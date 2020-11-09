# Thin-Section-Processing-WIP

This script takes any colour image as an input, so both PPL and XPL views should work.

Above are the original scripts created on Pycharm (.py) and the Jupyter Notebooks (.ipynb)

A thin section of Andesite found on Google images was used as an example. 

Method 1: Phases - Created a new image by allocating different values corresponding to the pixel values of the minima of the filtered image histogram. For example, the first phase is for values between 0 and the first minima. The limited number of different pixel values allows for easier classification of colours, if desired.

Method 2: Using the unphased filtered data

The accuracy of the methods is decent, and each method has its perks. However, there is likely a more accurate method that I couldn't seem to come up with within the limited time I had. 

Please note that the logic behind this project is not perfect. I am aware that colour alone is not sufficient for mineral identification, but it can be a distinctive feature. The main purpose of this project was to find a reasonably accurate mineral modes in an image, not neccesarily to return the precise number of distinct minerals in the image.

Feel free to use these resources in any way you'd like!
