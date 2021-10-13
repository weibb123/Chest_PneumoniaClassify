# Chest_Pneumonia
Framework/library used: numpy, pandas, matplot, os, glob, seaborn, tensorflow, sklearn

To classify chest Pneumonia, we use pretrained model vgg19 in tensorflow and apply transfer learning.
![image](https://user-images.githubusercontent.com/84426364/137032322-d5eef10f-de10-4068-8cc1-16fc4fc37806.png)

<h1> Data and configs </h1>
IMG_size: (224, 224, 3)
batch_size = 64
epochs = 10

5216 training examples of chest
624 testing examples of chest
16 validation examples of chest
Label name: [normal, pneumonia]
  
<h2> <br> Procedures </br> </h2>
<br> Import Library </br>
<br> Grab all jpeg and put in folder-> list -> create dataset </br>
<br> Turn jpeg to array and preprocess them </br> 
<br> train_test split: 80% training, 20% testing </br>





