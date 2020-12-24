# ResNet-Deployment
-We have developed ResNet architecture and experimented with various Hyperparameters. Please checkout this repository for more details [Resnet_Implementation](https://github.com/ShrutiNair5/Resnet_Implementation) <- Click
- We are using ResNet Model [ResNet-18](https://github.com/ShrutiNair5/Resnet_Implementation/blob/master/Group5_ResNet/RESNET14_18_SGD.ipynb) where we achieved an accuracy of 91.07%. 
- The TrainingNotebook.ipynb was created as an abstraction to run the model and to save `training_logs.txt` and `saved_weights.pt` which are then used during inference.
- After testing application locally we deployed it on Heroku platform

#### Steps required to deploy on Heroku platform
1)  Additional Files for Deployment- Before we deploy the web app, we need to create additional files in addition to Python files that we have created to build the app. These         files are

-requirements.txt: this is the text file that we need to create to tell Heroku to install the necessary Python packages needed to deploy our machine learning model. W used four Python libraries to build the app: numpy, streamlit, tensorflow, and pillow. Hence, we need to specify the relevant version of those libraries in this text file.
     



### Team

- [Akshay Amrit](https://github.com/akshayamrit) - E20004
- [Aman Gupta](https://github.com/aman1608) - 
- [Prashantha Shivshankarrao](https://github.com/ksshaan) - E20022
- [Shivam Babbar](https://github.com/shivam9711) -
- [Shruti Nair](https://github.com/ShrutiNair5) - E20033

## Flask App


![App Preview](FirstImage.png)

![App-Result](UploadImage.png)


**Check ResNet Deployment : [ResNet](https://resnetdeployment.herokuapp.com/)**
