o How many neurons and layers did you select for your neural network model? Why?
Basic Neural Network: 1 hidden layer with 44*2 neutrons, based on double of 44 input features 
Deep Learning model: 2 hidden layers with 44*2 and 44*2 neutrons

o Were you able to achieve the target model performance? What steps did you take to try and increase model performance?
No, the Random Forest model has 71.2% accuracy. 
After implementing Basci Neural Network, the accuracy went up to 73.2%.
However, with Deep Learning Model, the accuracy is about the same at 72.9%, so it showed overfitting.

o If you were to implement a different model to solve this classification problem, which would you choose? Why?
In this discussion, the model used relu for hidden layer and sigmoid for output
We could try other activations 'tanh' or 'Leaky ReLU', but if deep learning model is overfitting at 73% already.
Other activations may not improve too much as well.
