# Project 2: MI3 Group5
MI3 Data Analysis for Project 2 Group 5 for DS 4002

Team Members:
Sally Sydnor(srs8yy): Group Leader,
David Bergman(dtb9de),
Minh Nguyen(hvn9qwn)

## Repository Contents

This repository contains 2 markdown files: README.md and LICENSE.md, as well as 3 folders: SRC, DATA, and Figures. The README.md file contains information about the contents of the repo as well as explanations for the src, data, and figures folders. LICENSE.md contains an MIT license for our work. The SRC folder contains the main code file for our project. More information about how the code works will be provided in the next section of this document. The data folder contains instructions on how to download the data file used for this project. A data dictionary is provided in the data section of this readme. The figures folder will contain all of the graphics generated from this project. A description of each figure is provided in the figures section of the readme. Lastly, all of our references will be displayed in the references section of this readme.

## SRC

### Installation/Building of Code

#### Implement the following steps to install and build the code:

## Data

| Variable    | Variable Type | Description                                            |
| ----------- | ------------- | -------------------------------------------------------|
| Image       | jpg           | Image of a weather condition (labeled in image name)   |


Data file can be downloaded through this Mendeley Data link:
https://data.mendeley.com/datasets/4drtyfjtfy/1 


## Figures

### Project 2 Figures Table of Contents
| Figure Name      | Description |
| ----------- | ----------- |
| Image_Set_1.png | First sample run of predictive model, contains 9 images and its predictions, all the predictions were correct|
| Image_Set_2.png | Second sample run of predictive model, contains 9 images and its predictions, all the predictions were correct|
| Image_Set_3.png | Third sample run of predictive model, contains 9 images and its predictions, all the preditions were correct| 
| Training_Validation_Graph.png | Learning curves for the predictive model, created by plotting training and validation errors (losses) and accuracies against the number of epochs|
| Model Comparison.png | Learning curves showing the loss and accuracy for our predictive models|

View figures here: 


Model Values
Model: "sequential"
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 rescaling (Rescaling)       (None, 180, 180, 3)       0         
                                                                 
 conv2d (Conv2D)             (None, 180, 180, 16)      448       
                                                                 
 max_pooling2d (MaxPooling2  (None, 90, 90, 16)        0         
 D)                                                              
                                                                 
 conv2d_1 (Conv2D)           (None, 90, 90, 32)        4640      
                                                                 
 max_pooling2d_1 (MaxPoolin  (None, 45, 45, 32)        0         
 g2D)                                                            
                                                                 
 conv2d_2 (Conv2D)           (None, 45, 45, 64)        18496     
                                                                 
 max_pooling2d_2 (MaxPoolin  (None, 22, 22, 64)        0         
 g2D)                                                            
                                                                 
 flatten (Flatten)           (None, 30976)             0         
                                                                 
 dense (Dense)               (None, 128)               3965056   
                                                                 
 dense_1 (Dense)             (None, 3)                 387       
                                                                 
=================================================================
Total params: 3989027 (15.22 MB)
Trainable params: 3989027 (15.22 MB)
Non-trainable params: 0 (0.00 Byte)
_________________________________________________________________


## References
[1] Ajayi, Gbeminiyi (2018), “Multi-class Weather Dataset for Image Classification”, Mendeley Data, V1, doi: 10.17632/4drtyfjtfy.

[2] Rutledge, Kim (2022). “Weather”, National Geographic, https://education.nationalgeographic.org/resource/weather/

[3] Ongoma, Victor (2022). “The science of weather forecasting: what it takes and why it’s so
hard to get right”, The Conversation, https://theconversation.com/the-science-of-weather-
forecasting-what-it-takes-and-why-its-so-hard-to-get-right-
175740#:~:text=Weather%20forecasting%20is%20an%20important,vital%20in%20the%
20coming%20years.


### Previous Submissions
MI1:  https://myuva-my.sharepoint.com/:w:/r/personal/srs8yy_virginia_edu/Documents/MI2%20-%20Project%202.docx?d=wf0ca916897954c6d8f498221fbc6e180&csf=1&web=1&e=8x9Ol0
MI2:  https://myuva-my.sharepoint.com/:w:/r/personal/srs8yy_virginia_edu/Documents/MI2%20-%20Project%202.docx?d=wf0ca916897954c6d8f498221fbc6e180&csf=1&web=1&e=8x9Ol0

