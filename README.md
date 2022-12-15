# Handwritten Character Number Recognition

Project Overview:<br>
<ul>
  <li>This is a project for handwritten character-number recognition.</li>
  <li>Created a sequential model using for predicting number from handwritten images.</li>
  <li>MNIST dataset is used as a dataset.</li>
  <li>MNIST stands for Modified National Institute of Standards and Technology.</li>
  <li>Dataset containes <b>60,000</b> 28x28 pixel grayscale images of handwritten digits from 0 to 9.</li>
  <li>Steps performed:
    <ul>
      <li>Importing necessary libraries.</li>
      <li>Loading MNIST dataset.</li>
      <li>Loading the dataset on training and testing axes.</li>
      <li>Normalizing the pixel values(between 0 and 1).</li>
      <li>Creating model, adding layers and training the model.</li>
      <li>Model evaluation.</li>
    </ul></li>
    <br>

![image](https://user-images.githubusercontent.com/72664379/205631840-4cd8264a-ecca-4c5d-b958-5f264b3f553c.png)
<br>The above figure shows the model description of the sequential model created.<br>
  
  ![image](https://user-images.githubusercontent.com/72664379/205634161-7a724fb9-b057-4073-bff0-b57668536808.png)
<br>The above plot shows the training and validation ACCURACY vs no. of epochs.
  
  ![image](https://user-images.githubusercontent.com/72664379/205634529-9d6bb620-8366-4044-8613-51f4c64874ae.png)
<br>The above plot shows the training and validation LOSS vs no. of epochs
  
  <h4>Accuracy achieved   : <b>~98</b>%</h4>
  <h4>Loss                : <b>~8</b>%</h4>
 
  <h3>Conclusions:</h3>
  <ul>
    <li>In the ACCURACY plot, the growth could be seen over the later and later epochs.</li>
    <li>On the other hand, in the LOSS plot, the loss could be seen degrading.</li>
    <li>Hence, this model could be considered to be as an efficient model.</li>
  </ul>
