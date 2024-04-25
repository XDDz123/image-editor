# Image Editor
This project implements techniques detailed in the paper [Poisson image editing](https://doi.org/10.1145/882262.882269) by Patrick Pérez, Michel Gangnet, and Andrew Blake. </br></br>
Specifically, the implementation includes:
* discrete Poisson solver
* seamless cloning by importing gradients
* seamless cloning by mixing gradients
* texture flattening
* local illumination changes.

Images sourced from the Poisson image editing paper.

# Libraries
* cv2 (image loading, resize)
* numpy
* scipy (linear algebra)
* matplotlib (plotting, polygon region selectors)

# Features
## Region Filling
![image](https://github.com/XDDz123/image-editor/assets/20507222/39aec542-51f7-4ada-9f5a-2173377d613c)
## Seamless Cloning
### Importing gradients
![image](https://github.com/XDDz123/image-editor/assets/20507222/a7b5b299-1195-470c-a818-a3bad06716d6)
### Mixing gradients
![image](https://github.com/XDDz123/image-editor/assets/20507222/31034796-c1dd-433f-a3bb-18badd127575)
## Samples
![image](https://github.com/XDDz123/image-editor/assets/20507222/e3114041-4e6e-4f3f-b418-22bc34b28406)
### Importing gradients vs. Mixing gradients
<img src="https://github.com/XDDz123/image-editor/assets/20507222/1a22f7cf-e6d0-4064-8ed4-1a37787f9f51" width="680" height="300"> </br>
<img src="https://github.com/XDDz123/image-editor/assets/20507222/36e6215c-0de8-47a2-be46-2f2cd4cc8d42" width="680" height="400"> </br>
## Texture Flattening
<img src="https://github.com/XDDz123/image-editor/assets/20507222/f5bea927-08bc-4662-ae11-1750bbc581b4" width="700" height="400"> </br>
## Local Illumination Changes
<img src="https://github.com/XDDz123/image-editor/assets/20507222/2d1755b8-f024-414f-99c4-3f1a62a03676" width="700" height="230"> </br>
