# Chest_Pneumonia

<h1> Objective </h1>
<img width="400" alt="Screen Shot 2021-10-13 at 8 49 57 PM" src="https://user-images.githubusercontent.com/84426364/137232248-292a5bb3-8d78-4a90-ae77-3cc171b512ad.png">
<br> Given chest images, we need to classify which chest is normal/or has pneumonia using deep learning approach. </br>

<h1> Framework/library used: numpy, pandas, matplot, os, glob, seaborn, tensorflow, sklearn </h1>

To classify chest Pneumonia, we use pretrained model vgg19 in tensorflow and apply transfer learning.
![image](https://user-images.githubusercontent.com/84426364/137032322-d5eef10f-de10-4068-8cc1-16fc4fc37806.png)

<h2> <br> Procedures </br> </h2>
<br> Import Library </br>
<br> Grab all jpeg and put in folder-> list -> create dataset </br>
<br> Turn jpeg to array and preprocess them </br>
<br> train_test split: 80% training, 20% testing </br>
<br> import/train pretrained model vgg19 </br>

<h3> Number of examples </h3><img width="248" alt="Screen Shot 2021-10-13 at 6 15 26 PM" src="https://user-images.githubusercontent.com/84426364/137231918-38146404-9a98-40ca-8ff6-64940c617e0c.png">


<br> Training Dataframe </br><img width="453" alt="Screen Shot 2021-10-13 at 6 15 34 PM" src="https://user-images.githubusercontent.com/84426364/137231693-b55b0b10-724c-4c31-996e-3bcb2fde39ed.png">




5216 training examples of chest, 624 testing examples of chest, 16 validation examples of chest
<br> Label name: [normal, pneumonia] </br> Label name will be one-hot encoded to fit the model.
  


<br> Metric: Accuracy, loss </br><img width="400" alt="Screen Shot 2021-10-13 at 6 05 14 PM" src="https://user-images.githubusercontent.com/84426364/137231757-4eb7f93e-3a63-4f2c-8d97-b3b27e6e7fe8.png">

<br> Training process </br> <img width="400" alt="Screen Shot 2021-10-13 at 6 04 59 PM" src="https://user-images.githubusercontent.com/84426364/137231865-f7b04b53-9b6c-46ee-af76-65fe443e2351.png">

<h2> RUNTIME AND DOWNSIDE </h2>
Runtime of notebook is about 280-300s, and the downside is that the notebook needs large amount of memory.









