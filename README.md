
# Credit Card Customer Churn Prediction using ANN
The aim was to design and develop a basic ANN model for customer churn prediction in a credit-card customer churn dataset. 

The input parameters for the model are: 
CreditScore,	Geography, 	Gender,	Age,	Tenure,	Balance,	NumOfProducts,	HasCrCard,	IsActiveMember,	EstimatedSalary and	Exited.

### Model performance
For the improvement in the model performance, following steps have been applied:

- increase no. of epochs
- apply different activation function, relu can be effective.
- increase no. of nodes in the hidden layer
- increase the no. of hidden layers. But, adding no. of hidden layers unnecessarily can create the problem of overfitting.
- By adding 'accuracy' as metrics during compilation, we can see accuracy in every epochs along with loss.

![image](https://github.com/BigyanBhatta/ANN_Customer-Churn-Prediction/assets/143421101/192707e6-9888-4452-8ccd-9c9f70c0ee98)
The performance of the neural network yielded an accuracy of 87%.

The loss value and accuracy was evaluated between the training and validation data.

![image](https://github.com/BigyanBhatta/ANN_Customer-Churn-Prediction/assets/143421101/8207a9fe-5825-4139-ba10-370958d32c9b)

![image](https://github.com/BigyanBhatta/ANN_Customer-Churn-Prediction/assets/143421101/b17271cb-eb15-430a-a54f-6dbcdbeb4e8c)

Finally, we can observe from both comparision graphs:

- The model is somehow performing satisfactory.
- The gap between the blue and the orange plot shows us the level of overfitting happening in our model.
- with oncepts like regularization, dropout of layers, etc we could mitigate these factors in our model.



