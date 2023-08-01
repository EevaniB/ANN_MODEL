#ANN_MODEL

Abstract:
In this study, I explored the impact of Activation Functions (AF) on the performance of Artificial Neural Networks (ANN). I developed a 1-hidden layer neural network model that autonomously adapts to the most suitable activation function based on the dataset. The model learns the best AF by using a flexible functional form, k0 + k1x, where k0 and k1 are parameters learned during training. This approach saves time and effort in manually tuning the model and opens new avenues for discovering essential features of lesser-known AFs.

Introduction:
As I delved into the world of machine learning and neural networks, I realized the significance of choosing the right activation function for classification tasks. It can be a time-consuming and sometimes frustrating process, trying various AFs until the best approximation is found. This study aimed to find an elegant solution by using the data's inherent clues to automatically identify the most suitable activation function. My proposed Ada-Act activation function, defined as g(x) = k0 + k1x, offers the flexibility to adapt to different datasets by learning the parameters k0 and k1 during training.

Implementation:
I loaded the dataset from a CSV file and converted the features to float values. I normalized the dataset to a range of 0-1 to prepare it for effective training and unbiased performance evaluation. I adopted k-fold cross-validation to ensure robustness in evaluating the model's performance. My neural network architecture comprised an input layer, a hidden layer, and an output layer, with the Ada-Act activation function employed in the hidden layer for adaptive learning. I used forward and backward propagation for effective training and fine-tuning of the model.

Evaluation Metrics:
After training, I assessed my model's performance by calculating accuracy and F1-Score. Accuracy reflects the percentage of correct predictions, while F1-Score measures the balance between precision and recall.

Results:
My model's performance was evaluated through k-fold cross-validation, and I reported the mean accuracy and mean F1-Score as the final performance metrics. My results demonstrated my model's ability to achieve competitive accuracy and F1-Score, validating its potential in automating AF selection and enhancing neural network training efficiency.

Conclusion:
This study highlights the importance of the Ada-Act activation function and its ability to adapt to different datasets. By using back-propagation to learn the parameters k0 and k1, my model autonomously evolved and performed exceptionally well. This study opens new possibilities for automating AF selection and streamlining neural network training. 
