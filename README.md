# Sea Turtle Image Segmentation
This project entails a comparison of image segmentation models for the purpose of detecting sea turtles and segmenting sea turtle anatomy using SeaTurtleID2022 Data Set (https://www.kaggle.com/datasets/wildlifedatasets/seaturtleid2022). The comparison was of the performance differences between the following image segmentation models: Fully Convolutional Network (FCN), Deeplabv3+, PP-LiteSeg, Mask R-CNN, and U-Net. 

## **Formal [pdf report](https://github.com/RandomRunt/Sea-Turtle-Image-Segmentation/blob/6d87fc61f3ed1c8ea10a97c90dc54aa3b02634ad/Sea%20Turtle%20Image%20Segmentation%20Model%20Comparison%20Report.pdf) detailing analysis and findings is in the root repository.**

## Guide to setting up method folders and files.

### Method Code Location - Jupyter Notebook (.ipynb)
Each method is written entirely within one jupyter notebook with code blocks to separate each step and comments to detail their respective functionality. Each of these notebooks are placed in their own method folder.

**Method Folder Names:**<br>
DeepLabv3+ Method<br>
FCN Method<br>
MaskRCNN Method<br>
PP-LiteSeg Method<br>
U-Net Method


### Add "data" folder from SeaTurtleID2022 to each Method Folder
It is **required** to extract the "data" folder from the SeaTurtleID2022.zip via "SeaTurtleID2022.zip/turtles-data/data": 

**File Path:**<br>
SeaTurtleID2022.zip  
└── turtles-data  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└── data 

This data file then needs to be copied and placed into each method folder. 

### Executing Method Code
Ensure all libraries are imported to the python environment prior to executing the code in Jupyter Notebook (.ipynb) files. Each code block can now be executed in sequential order. The code in general: prepares the data and model, trains the model and retrieves results. 
