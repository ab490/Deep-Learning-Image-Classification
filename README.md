
# Optimizers for backpropagation algorithms and autoencoders <br>
<!-- In this repository with the help of the two tasks, I have explained different optimizers for backpropagation algorithms and have also explained about the uses and autoencoders and the uses of noise in the data. Problem statement is given below :-  -->
Task 1 is to train the fully connected neural network (FCNN) using different optimizers for the backpropagation algorithm and compare the number of epochs that it takes for convergence along with their classification performance. <br> 
Task 2 includes building an autoencoder to obtain the hidden representation and use it for classification.
<ol>
  <li><strong>Task based on different optimizers:-</strong></li>
  <ol>
   a. Develop an FCNN with 3 hidden layers. Use cross-entropy loss. Train each of the architectures using 
   (a) stochastic gradient descent (SGD) algorithm - (batch_size=1), (b) batch gradient 
   descent algorithm (vanilla gradient descent) – (batch_size=total number of training 
   examples), (c) SGD with momentum (NAG) – (batch_size=32), (d) RMSProp 
   algorithm – (batch_size=32), and (e) Adam optimizer – (batch_size=32). Use
   the difference between average error of successive epochs fall below a threshold 10-4 as 
   convergence criteria. Consider β1 = 0.9, β2 = 0.999 and ε = 10-8 for Adam optimizer. 
   Consider momentum parameter as 0.9, learning rate as 0.001 and β = 0.99 for RMSProp. 
   
   <ol>
   i. Observe the number of epochs considered for convergence for each of the 
   architectures. Tabulate and compare the number of epochs considered by each of 
   the optimizers.<br>
   ii. Present the plots of average training error (y-axis) vs. epochs (x-axis). <br>
   iii. Give the training accuracy and validation accuracy for each of the optimizers in 
   each of the architectures.<br>
   iv. Choose the best architecture based on validation accuracy. Give the test 
   confusion matrix and test classification accuracy along with training accuracy 
   and confusion matrix for the chosen best architecture.<br>
   </ol>
  </ol>
</ol>

<ol>
  <strong>2. Task based on autoencoder:-</strong>
  <ol>
   a. Develop an autoencoder that learns a compressed representation of the input features for 
   a classification predictive modeling problem. Train the autoencoder using Adam 
   optimizer. Use sigmoid activation function for the nodes in all the hidden layers. Use the 
   difference between average error of successive epochs fall below a threshold 10-4 as 
   convergence criteria.
   
   <ol>
   i. Build autoencoders with one hidden layer and 3 hidden layer architectures. For 
   each architecture, experiment with a different number of neurons in hidden 
   layers including the compressed layer. Present the average reconstruction error for training data for each of the architectures.<br>
   ii. Choose the best architecture for (a) encoder with one hidden layer
   (b) encoder with 3 hidden layer architectures based on validation error. Give the test reconstruction error for the chosen best architectures.<br>
   iii. Present the plots of average training reconstruction error (y-axis) vs. epochs (x-axis) for the best architecture for (a) encoder with one hidden layer and (b) 
   encoder with 3 hidden layer architectures. <br>
   iv. Take one image from the training set and one image for the validation set, from 
   each of the classes, and give their reconstructed images for each of the experiments.<br>
   v. Classification using the compressed representation from the encoder with one hidden layer:<br>
   <ol>
      • Present each training data to the best encoder with one hidden layer and 
      save the output of the hidden layer (compressed layer). This gives the 
      compressed representation of training data. Similarly obtain the 
      compressed representation of validation and test data. <br>
      • Build the FCNN using Adam optimizer for classification. Report the training and validation accuracy along 
      with the confusion matrix. <br>
   </ol>
    vi. Classification using the compressed representation from the encoder with 3
    hidden layers: Repeat the experiments as described in previous question (Task 2.a.iii)<br>
  </ol>
 
</ol>
