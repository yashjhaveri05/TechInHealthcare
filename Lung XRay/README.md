<b>Main Task:</b> To correctly classify the lung x-ray images into the possible diseases.

<b>Dataset:</b> Obtained From https://www.kaggle.com/datasets/jtiptj/chest-xray-pneumoniacovid19tuberculosis

<b>Classes:</b> Normal, Pneumonia and Tuberculosis

<b>Approach:</b> Take approximate same number of images for each of the three classes and split them into training and validation sets. Use the ResNet50 v2 model and fine-tune it. Set the hyperparameters accordingly and lastly added a global average pooling layer and a dense layer with 3 neurons since we have 3 classes. Data augmentation is also used to increase the size of our dataset for better training.

<b>Note:</b> Covid-19 class is not considered since it might not be a long lasting and common disease and hence, might not be used for general applications. 

Open to Suggestions