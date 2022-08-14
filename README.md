# Pneumonia Detection from Chest X-ray Using KNN
[Pneumonia](https://www.who.int/news-room/fact-sheets/detail/pneumonia) is a form of acute respiratory infection that affects the lungs. The lungs are made up of small sacs called alveoli, which fill with air when a healthy person breathes. When an individual has pneumonia, the alveoli are filled with pus and fluid, which makes breathing painful and limits oxygen intake.
<p align="center">
  <img src="https://www.nhlbi.nih.gov/sites/default/files/inline-images/pneumonia.png?raw=true"/>
</p>

## Goal
The aim was to take the [dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) which contains 5,863 X-Ray images, divided into normal and pneumonia, and to train a traditional (classification) machine learning algorithm to be able to detect the pneumonia cases. This is a challenge as this task would usually be done using a CNN model, instead of a machine learning algorithm.

## Metrics
The model (KNN) was evaluated on its accuracy which reached 84.45% accuracy on the test set. below is the model confusion matrix:
<p align="center">
  <img src="https://github.com/mkldhz/Pneumonia-Detection-from-Chest-X-ray-Using-KNN/blob/main/Screenshots/conf_matrix.jpg?raw=true"/>
</p>

## Predictions
Below is 16 images pulled randomly from the data test set, each image is labeled with the its true finding as well as the model prediction:
<p align="center">
  <img src="https://github.com/mkldhz/Pneumonia-Detection-from-Chest-X-ray-Using-KNN/blob/main/Screenshots/predictions.jpg?raw=true"/>
</p>
