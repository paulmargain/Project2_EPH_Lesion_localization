# Project2_EPH_Lesion_localization
This project is about culprit lesion localization on cardiology images.


##How to run 

We have two diffrenrent CNN implementations:
      
      The first one is a Unet, in the folder: "UNET_FINAL.ipynb"
      The data has to be put in two folders, "raw" with the raw images and "labelled" with red and green dot on the culprit regions.
      
      The first part of the code is dedicated to the targets creation.
      After threshold selection of the culprit region, a clustering algorithms is used to create target with only one culprit regions.
      
      Then the Unet archtecture is implemented and the training of the model.
      
      The second one is a CNN regresion, in the folder: "Regression_NN.ipynb"
      The code structure is similar to the Unet implementation but the target is composed of (x,y) the culprit region center coordinates.
      
      
      
      
      
