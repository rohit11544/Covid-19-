# Covid-19 virus Classifier model 
this CNN Model classifies weather a person is normal, Viral Pneumonia or has covid by giving there chest x-ray images.

### Covid-19 virus
Coronaviruses (CoV) are a large family of viruses that cause illness ranging from the common cold to more severe diseases.
A novel coronavirus (nCoV) is a new strain that has not been previously identified in humans.
The new virus was subsequently named the “COVID-19 virus”.

### LIBRARIES
* os
* cv2
* tqdm
* numpy
* pandas
* seaborn
* matplotlib
* sklearn
* pickle

### About the model
This model is built with 5 convolution layers on around 300 chest x-ray images. This model has a accuracy more than 95.23% on test set.

### About the dataset
This dataset is downloaded from kaggle weblsite. The data set can be downloaded from the zip file in this repository. This data set contains 3 classes 
Covid, Normal, Viral Pneumonia. This data set contain total of 312 examples (including training ,validation and testing sets).

## preview of this data set


## plots
### loss function vs the number of epochs

<img src="https://user-images.githubusercontent.com/61901749/86909689-1997e080-c136-11ea-9ab8-ba25b04946bf.png" width=400>

### accuracy vs the number of epochs

<img src="https://user-images.githubusercontent.com/61901749/86909693-1bfa3a80-c136-11ea-8015-30d36b66c41c.png" width=400>

 ## MODEL ACCURACY : 96.88%
 
