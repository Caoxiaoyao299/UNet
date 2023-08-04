# UNET
including Attention_UNet, Channel_UNet, FCN8s, ResNet34_UNet, UNet, UNetpp.

# ENVIRONMENT
Window 11 + PyCharm + python3.7 + PyTorch 1.7.1  

## HOW TO RUN:
All you need to do is import the new dataset path and reference the neural network for model training and prediction.

## INTRODUCTION
The purpose of this repository is to perform image segmentation of the longissimus dorsi muscle of meat sheep using 
CT images. This repository includes the model network code (including the model training weights pth file), the model 
training log file and the AVER_HD, MOIU&DICE, LOSS training process diagrams. 
We put in 62 original CT images of longissimus dorsi muscle of meat sheep as sample files, which are in the dcm_25 
folder, and 1471 manually labeled CT slices including 25 longissimus dorsi muscle of meat sheep, which are located in 
the label folder.In the prediction results folder£¬From left to right, the images in the prediction folder are the 
original CT image, the prediction image, and the mask image. In the prediction folder, we only keep the prediction 
results of one model, and the other five models are similar to this model. We only need to change the corresponding 
model to predict after network training.
