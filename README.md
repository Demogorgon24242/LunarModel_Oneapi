# LunarModel_Oneapi

This Model was constucted by me and other team members including Akanksha Bansal, Nehal Sahukar and Kuber Vajpayee of my team, for the Intel OneAPI Hackathon. 
It contains code for the constructed model of object detection using OpenCV library and Convolutional networks. The model is designed to recognise the big rocks present on the surface of the moon so that it can help the rover to navigate using its sensors.
The model is developed using U-Net architecture and OpenCV library.

# Introduction

The model is using instance segmentaion to classify the images into 4 classes of sky, ground, small rocks and big rocks denoted by grey, black, depp grey and white respectively. Further information about the Unet architecture can be viewed at :- "https://towardsdatascience.com/unet-line-by-line-explanation-9b191c76baf5"

The model can be optimized using parallel processing libraries or Intel Open Vino Toolkit, which we shall try to update soon.


# TechStack

- Python


## Run Locally

### To construct model

Clone the project

```bash
  git clone https://github.com/Demogorgon24242/LunarModel_Oneapi.git
```

Go to the project directory

Execute all the cells

In order to import the dataset provide the necessary path using the Kaggle api

## Note :- This is for testing only not for deployment
