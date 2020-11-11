# Fraudulent-Credit-Card-Transactions-Prediction-Using-2D-Convolutional-Neural-Network
Fraudulent credit card is one of the most alarming concerns in this modern age. With few misuse of credit card, thousands of dollars can be mishandled. This paper focused on detecting fraud credit card transaction using 2D-Convolutional neural network. The paper reports the categorization of two designated categories- Genuine and fraud transactions. In the pre-processing stage we applied under-sampling technique to handle imbalance dataset. For the improvement of the accuracy, we have decreased the number of convolutional layers with a sigmoid layer at the top. The proposed technique achieved an accuracy of 94%.

DATASET DISTRIBUTION

The dataset contains the details of transactions made by credit card holders in September 2013 by european cardholders. This dataset contains data of 492 frauds out of 284,807 transactions. We split the dataset in 80:20 ratios for training and testing.

METHODOLOGY AND PROPOSED MODEL

To handle the imbalance data set with only 492 fraud entries out of 284,807 total entries, we applied under-sampling technique to the genuine class. Under-sampling process involves removing few observations randomly in order to balance the dataset to enhance the accuracy. In our proposed model, we used a simple stack of two convolutional layers with rectified linear circuit (ReLu) activation followed by normalization and dropout layers. Very few layer makes this model a low latency and higher efficiency model.
• Convolutional layers – In the convolutional neural network, a convolutional layer is a linear operation that involves multiplication of weights with the input, must like a customary neural network. The input shape (1, 34, 981) in the sequence of (sample height, sample width) is being fed to the first convolutional layer. The activation function ReLu prioritizes only positive part of the argument, so the values less than zero are automatically neglected.
• Batch Normalization – It is specially used for standardizing the inputs of the deep neural network. This technique is applied to the input variable of the layer or to the activation function from the previous layer.
• Dropout layers– It is a widely used regularization process for deep learning network. Dropout lessens the chances of over fitting, by haphazardly turning off certain neurons in the network which forces the data to discover new paths.
• Dense layers– It is a layer where input neuron is connected with the output neuron. We used a dense layer of 64 nodes to transform the output of the previous level.

CONCLUSION

In this work, a highly imbalanced dataset is being used. In the pre-processing stage, in order to balance the dataset, under sampling technique is applied to the major class. A two layer CNN is being used to classify the data and achieved the overall accuracy of 94%. As an extension to this presented model, authors are intended to work for further betterment of the accuracy.
