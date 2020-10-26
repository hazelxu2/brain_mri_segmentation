# brain_mri_segmentation
Brain MRI images can help to detect brain tumors. This project is focusing on segmenting Brain MRI images using a basic Unet architecture, Unet+FPN and Unet with ResNeXt50 backbone.

# code_description
Data Preparation: Create structured pandas dataframe

Data Visualization:  Using stacked bar chart/ hot colormap with samples of images with a positive and negative diagnosis

Data Generator and Augmentaions: Using Python Package Torch and Albumentations

Model Building: UNet,FPN,and UNet ResNeXt50

Train Models: Using GPU and recorded train history

Performance evaluation: Segmention Quality Metric/ Segmentation Loss

Visualization of the prediction on test data using Gif
