# Self-Driving-Car-Lane-Detector

This program is used to extract the lane lines found on the road of any color only by using the video taken from dashcam
## laibraries used (python)
  open cv
  numpy
  moviepy (to grab frames from a video source and to store final video from processed images)
  IPython (to display the video on the webpage)
jupyter is used to run this program 

## To run this Program
  install the needed libraries . an easy way to do is to download the miniconda for your os and follow these steps provided in this link
  https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/README.md
  
  ### steps
      download CarND-Term1-Starter-Kit
      choose between anaconda or docker 
        #### for anaconda:
              https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/doc/configure_via_anaconda.md
        #### for docker
              https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/doc/configure_via_docker.md
  after installation , open terminal or cmd promte and run jupyter with this command
      jupyter notebook
  this will open your default web browser . 
  select the ProgramFinalSubmission.ipynb file . 
  go to cell -> Run all 
  
  ## Pipeline of program
    the working of this program can be breakdown into following steps
    1.Load in the videosource on which you like to find the laneLine
    2.breakdown the video frames into individual image frames
    3.on that image fram , apply these following techniques
                1.convert from BGR image to grayscale image
                2.apply gaussian_blur to the grayscale image
                3.using canny edge detection , find the edges in the given image
                4.define a region of interest (roi) for each side (Left and Right) and apply them to the image which has the edges marked
                
                
  



  


