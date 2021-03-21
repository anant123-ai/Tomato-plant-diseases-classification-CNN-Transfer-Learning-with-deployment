# Tomato-plant-diseases-classification-CNN-Transfer-Learning-with-deployment
# Problem statemnet : Tomato plant diseases classification CNN Transfer Learning
# Business problems : 
Tomato is the most popular crop in the world and in every kitchen, it is found in different forms irrespective of the cuisine. After potato and sweet potato, it is the crop which is cultivated worldwide. India ranked 2 in the production of tomato. However, the quality and quantity of tomato crop goes down due to the various kinds of diseases. so in this problem we will use deep learning technique to detect tomato plant diseases.
# Objective :
To build Web - App for classsifing Tomato plant diseases.
# Data 

Download the data set from the kaggle https://www.kaggle.com/noulam/tomato
1. Here we are having 10 categories of diseases  

    where the categories are numbered 0 to 9, in the following order:
    
    <b>
    0 Tomato___Early_blight
    1 Tomato___healthy
    2 Tomato___Tomato_mosaic_virus
    3 Tomato___Tomato_Yellow_Leaf_Curl_Virus
    4 Tomato___Late_blight
    5 Tomato___Target_Spot
    6 Tomato___Septoria_leaf_spot
    7 Tomato___Bacterial_spot
    8 Tomato___Spider_mites Two-spotted_spider_mite
    9 Tomato___Leaf_Mold <b/>
    
# Model Building 
Model-1 we have build VGG16 with with Adam optimizer, got validation acuuracy of 92%.

Model-2 we have build InceptionV3  with with Adam optimizer, got validation acuuracy of 92%.


# Deployment:
for we choose best model and used flask framework for deployement
