#Comp110-Worksheet 2

##Pseudo Code


###Overlaying an image on top of an existing image
```
Load image from directory and display image to screen

Initialise image to overlay
Initialise targetX 
Initialise targetY
  DO WHILE get the range of pixels in a section of the image 
     Then overwrite them to original image starting at targetX and targetY
  END DO
Display image
```
###Enlarging a section of an image
```
Make picture from file.
Initialise soruceX value
Initalise soruceY value
    DO WHILE targetX is less than resolution of the pixels to copy
      Get pxiels starting at SourceX and SourceY
         DO WHILE targetY is less than resolution of the pixels to copy
           Set colour of pixels from targetX and targetY to the value of sourceX and sourceY
           Scale up sourceX by 70%

    END DO
Display image
```


##Flowcharts
#####This flowchart displays the overall design of how the program will start. The user will be shown an image and will choose which part of the image they would like to zoom in to.
![alt text](https://raw.githubusercontent.com/Alli1223/comp110-worksheets/master/Worksheet%202/design_function_1.png "Flow Chart 1")
#####This flowchart outlines the design of how the images get overlaid an existing image, and how the user will pick which image they would like to see in greater detail.
![alt text](https://raw.githubusercontent.com/Alli1223/comp110-worksheets/master/Worksheet%202/design_function_2.png "Flow Chart 1")

