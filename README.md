# OVERVIEW ML
Here is an overview of ML's contribution to the Beras.AI project

## 1. Implementing Machine Learning Technology
We have created a Machine Learning model that can classify the quality of rice into 3 labels namely Premium, Medium, and Not Feasible using the CNN algorithm with the TensorFlow and Keras libraries, also MobileNet architecture to increase good accuracy. 
![TensorFlow_logo svg](https://github.com/dianrizqisaputra/ricequality/assets/91761759/b8764477-dddd-4b1f-9f26-390107984bc4)

Here is the flowchart that we use. describes our entire process for creating rice quality detection features starting from datasets processing to model implementation.
![flowchart](https://github.com/dianrizqisaputra/ricequality/assets/91761759/6f03a030-6a10-409c-9e5b-8ee8da2c291c)



## 2. The Dataset We Used
The dataset that we have created is then subjected to data cleaning to produce 1800 images After that, we distribute the cleaned data into 2 parts, namely 1440 images for training and 360 images for validation. Then, we categorize the data for each label, namely in the training data there are 480 images on each label and validation data there are 120 images on each label.  
Here is the dataset link: https://drive.google.com/drive/folders/15ivrjRRt9wq649F0kd-vv66_xNVM5Ctq

![Data seet](https://github.com/dianrizqisaputra/ricequality/assets/91761759/a2e99a52-9aa9-440d-8a02-fbd4d076060a)

## 3. Deployment Model
Then we deployed model with two options, the first option is for on-device by saving the model into TensorFlow Lite and the second option is for the server by saving the model into the .h5 file format to be deployed using Docker and Google Cloud Run so as to produce an API that can be used online. Here is the TensorFlow Lite and API link: https://github.com/Beras-AI/ML-Model & https://ricequality-model-2q5w4z2mgq-et.a.run.app/docs  
  
![Deploy](https://github.com/dianrizqisaputra/ricequality/assets/91761759/a8702751-559a-4391-9b30-345007e77933)


