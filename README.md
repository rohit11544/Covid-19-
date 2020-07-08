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
#### Covid
<img src="https://user-images.githubusercontent.com/61901749/86911443-f3c00b00-c138-11ea-8353-d999fda9562a.jpeg" width=250>           <img src="https://user-images.githubusercontent.com/61901749/86911470-03d7ea80-c139-11ea-8ce6-a2971fb9fe00.jpeg" width=250>   <img src="https://user-images.githubusercontent.com/61901749/86911512-17835100-c139-11ea-8020-7ff040d08fb6.png" width=250>

#### Normal
<img src="https://user-images.githubusercontent.com/61901749/86911706-616c3700-c139-11ea-9cdf-a6c46851c199.jpeg" width=250>   <img src="https://user-images.githubusercontent.com/61901749/86911718-63ce9100-c139-11ea-84fe-ebd551ccd3a3.jpeg" width=250>   <img src="https://user-images.githubusercontent.com/61901749/86911730-67faae80-c139-11ea-9da4-75bad211a444.jpeg" width=250>

#### Viral Pneumonia
<img src="https://user-images.githubusercontent.com/61901749/86911811-8b255e00-c139-11ea-9df9-b7cdf828b8c1.jpeg" width=250>           <img src="https://user-images.githubusercontent.com/61901749/86911822-8fea1200-c139-11ea-83e2-98971b5c0a35.jpeg" width=250>     <img src="https://user-images.githubusercontent.com/61901749/86911827-91b3d580-c139-11ea-9494-4d37d80cf754.jpeg" width=250>

## plots
### loss function vs the number of epochs

<img src="https://user-images.githubusercontent.com/61901749/86912088-fcfda780-c139-11ea-803d-0f7dbb892be7.png" width=400>

### accuracy vs the number of epochs

<img src="https://user-images.githubusercontent.com/61901749/86912091-fe2ed480-c139-11ea-8cb4-8427804128c7.png" width=400>

 ## MODEL ACCURACY : 95.23%
 
