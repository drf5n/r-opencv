# r-opencv
Automatically exported from http://code.google.com/p/r-opencv

There isn't much in this repository, only two functions demonstrating loading a file and displaying it.  

I haven't tested any of it.  -- drf5n 2016-01-23 


    library(ropencv)
    p <- loadImage(filename)
    showImage(filename)
    
test/test.R has this:

    library(ropencv)
    showImage("~/Bilder/ying-hukou.jpg")



