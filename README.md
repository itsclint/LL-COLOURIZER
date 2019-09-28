# LL-COLOURIZER
this is a machine learning algorithm that uses low level computer vision techniques to process images.


# SKIN DETECTION 
Skin detection is the process of finding skin-colored pixels and regions in an
image or a video
Human Skin
The color of human skin is created by a combination of blood (red) and melanin (yellow, brown).
Skin colors lie between these two extreme hues and are somewhat saturated.
The human skin is a fraction of the actual color cube, about 0.25 % of the total colors
Except for extremely hairy subjects, which are rare, skin has only low-amplitude texture.

Skin detection using HSV and YCbCr color space is based on the threshold value of the individual
component of corresponding color space. Due to non-uniform and device dependent nature, RGB color space
not widely used for color based analysis. This section explains the methodology used for the skin detection in
color images using two different color spaces. 

YCrCb Color Space
Encoded nonlinear RGB signal, commonly used in video coding and image compression work.
constructed as a weighted sum of the RGB values, and two color difference values Cr and Cb that are formed by subtracting luma from RGB red and blue components
16 to 235 for Y, 16 to 240 for Cb and Cr
Skin pixels form a compact cluster in the Cb-Cr plane.
\displaystyle Y = 0.299R + 0.587G + 0.114BY=0.299R+0.587G+0.114B
\displaystyle C_r = R - YC 
r
​	 =R−Y
\displaystyle C_b = B- YC 
b
​	 =B−Y
Transformation simplicity and explicit separation of luminance and chrominance components makes this colorspace attractive for skin color modelling
