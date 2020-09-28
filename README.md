Pixel Operations and Intensity Transformations

This program contains a main application that has buttons that link to other applications that perform the image manipulations. Each application contains an option to save the images that are created. 

Built with:
MATLAB

Installation:
1. pull files from Gitlab
2. Double click on PixelTransMain.exe 
3. An empty command prompt window will appear. Click > on keyboard.
4. The main page of the application will appear.  

To compile your own executable:
1. Verify that version 9.9 (R2020b) of the MATLAB Runtime is installed. To find its location enter:  >>mcrinstaller
2. If you need to download matlab runtime installer:  https://www.mathworks.com/products/compiler/mcr/index.html
3. Enter the command: matlab -batch compiler.build.standaloneApplication('PixelTransMain.mlapp')


Tips:
1. Images to be used with the program are in the images folder. 
2. It is recommended to use maxlight.jpg and maxdark.jpg for image arithmatic. 
3. When done with the image manipulation, close the dialog box before moving on to the next type of manipulation. 

Testing and reflection:
The first big implementation for this project was its graphical user interface. Using matLab as our designer interface allowed our group to make a simple and easy to understand GUI quickly and without complications. The only downside to this is that matLab is the primary way to run our program so it is required to be installed.

To go over our GUI from top down we had 9 buttons in total. 
1.	Image set operations included union, intersection, set difference, symmetric set difference, and complements between 2 images.
2.	Power law and gamma transformation asks for a C value and gamma value in which you submit and choose an image to change.
3.	Logical operations include AND, OR, NOT, and XOR operations to perform on 2 images giving the user a resulting image.
4.	Bit plane simply ask for an 8bit input image then reveals the relative importance of its bits in 8 image planes.
5.	Arithmatic takes 2 images as input and transforms using addition, subtraction, multiplication, and division.
6.	Linear and piece wise linear transformations takes an input image and can transform using dilation, contrast stretching, and rotation.
7.	Image negative ask for an input image then outputs the complete negation of the image.
8.	Binarization and thresholding takes an image and outputs a resulting image by simply clicking the threshold or binarize buttons.
9.	Log transformation requires a log value then changes the input image by that log value for the result.

Each needed to perform its transformations properly while also being able to save the resulting images into your location of choice. It was a lot of fun creating some strange creations to use in the project, one of our favorites was using image set operations to union the images of the dog in the ball pit and dog in a bear costume. Testing each of the buttons, we made sure that the error dialogue boxes appeared at appropriate times while working on the program. We also made sure that buttons needed to be clickable and unclickable at appropriate times to avoid the program for taking too many unnecessary inputs. 
Overall it was a good working environment with up and downs when trouble shooting but we are proud of our production.

