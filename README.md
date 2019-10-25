# Classifying-Chest-X-Ray-Images
Classifying Chest X-rays as normal, bacteria pneumonia, or viral pneumonia.

#### Author
[Kellen Sorauf](https://www.linkedin.com/in/kellen-sorauf-3983505/)

### Problem:
Classiying chest x-ray images as either normal, bacteria, or viral infected. The project was adapted from a [Kaggle Project](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia) and the Kaggle project orginated from an [academic journal](https://www.cell.com/cell/fulltext/S0092-8674(18)30154-5). The problem as presented in Kaggle was to classify chest x-rays as either normal or pneumonia infected. For this project images were reorgnized into three cateorgies: normal, bacteria, and viral.  With three categories and a reagangement of the images the project became a multi-classification problem instead of a binary-classification.  

The data downloaded from Kaggle was in these folders: 
train pneumonia: 3876,
train normal: 1342, 
validation pneumonia: 9, 
validation normal: 9, 
test pneumonia: 390, 
test normal: 234,

After reorganizing the data into multi-calssification data:
train bacteria: 2038,
train virus: 1000,
train normal: 1000,
validation bacteria: 500,
validation virus: 345,
validation normal: 351,
test bacteria: 242,
test virus: 148,
test normal: 234,

The images are now split into three categories with more validation images.

### Reorganizing the data:
Data was reoganized into normal, bacteria, and viral categories using Python in this [notebook]()
Sample x-ray images images of normal, bacaria and virus are shown below: 
![Sample x-ray](https://github.com/Mrsnellek/Classiyfing-Chest-X-Ray-Images/blob/master/Sample%20xray%20images.png)

### Main finding:
Using a convolutional nerual network images were correcly classified with an accuracy over 88% baised on the test data provided.  
There was a XXX false positive and XXX false negitive rate for 

