<b>Main Task:</b> To correctly classify the eye XRay obtained normally via Fundus Photography into 5 classes to determine whether the patient has diabetes or not/

<b>Dataset:</b> Obtained From https://www.kaggle.com/datasets/tanlikesmath/diabetic-retinopathy-resized

<b>Classes:</b> 0 - No DR, 1 - Mild, 2 - Moderate, 3 - Severe, 4 - Proliferative DR

<b>Approach:</b> Using the csv file, we get the images based on the image column name and the label which corresponds to the level column. We then remove the local average color of the image to make the eyeball nerves more prominent and split the data into training and validation set. Further, we apply ResNet50v2 model along with 4 additional dense neural network layers the last of which is the output layer. hence, it has only 5 neurons representing the 5 classes. We train the model for 10 epochs but can be trained for more to improve the accuracy.

Open to Suggestions