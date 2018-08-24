# Impainting
## How to use it:
##1.Preparations: Put the original image (the one you want to operate) as well as 
the masked image (the one with the impainting area masked by a specific color) under the same path as the matlab code.
##2.Open the plotall.m file with MATLAB modify the parameters in the function as needed
For example: [i1,i2,i3,c,d,mov]=inpaint('1.png','2.png',[255 0 0]); 
1.png -> The original image.
2.png -> The masked image.
[255,0,0] -> The color used to mask the impainting area.
##3.Examples included.
##4.Remember to leave a star if you'll be so kind.
