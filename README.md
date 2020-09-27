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