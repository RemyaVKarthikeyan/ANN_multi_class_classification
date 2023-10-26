# ANN_multi_class_classification

Applying Artificial Neural Network to support clinicians in screening pregnancies to identify those which potentially have issues so that they can receive further medical attention.

Dependencies:  Python, Google Colab

1. Importing libraries

![image](https://github.com/RemyaVKarthikeyan/ANN_multi_class_classification/assets/145346713/8df20d9d-abf4-4ea0-8e79-86cd467e2c96)

2. Inspecting the dataset

![image](https://github.com/RemyaVKarthikeyan/ANN_multi_class_classification/assets/145346713/944776cb-fc8e-421c-8d3f-0100848a8a56)

![image](https://github.com/RemyaVKarthikeyan/ANN_multi_class_classification/assets/145346713/7c8d2c52-2702-437a-8151-b2bfdc27b59d)

![image](https://github.com/RemyaVKarthikeyan/ANN_multi_class_classification/assets/145346713/934f7cce-363e-44b0-8503-5d8c65518fe9)

3. The column 'NSP' is identified as the target variable

![image](https://github.com/RemyaVKarthikeyan/ANN_multi_class_classification/assets/145346713/04a272d4-45c8-4e5d-ac91-ee296b651262)

4. Building training and test dataset and standardising the data

![image](https://github.com/RemyaVKarthikeyan/ANN_multi_class_classification/assets/145346713/b749361c-c516-45dd-9743-0feacf05bf2f)

5. Building and training nueral network. Adding a hidden layer of 9 nuerons and using ReLU function as activation function. Adding 3 neurons in the output layer and utilizing softmax activation function

![image](https://github.com/RemyaVKarthikeyan/ANN_multi_class_classification/assets/145346713/ab206740-f486-44a1-8abd-1454825dd4ef)

6. Compiling the model. Selecting optimizer and loss function

![image](https://github.com/RemyaVKarthikeyan/ANN_multi_class_classification/assets/145346713/61e26c8f-1ad5-4bf2-9991-1056dbc9c77f)

7. Summary of the model

![image](https://github.com/RemyaVKarthikeyan/ANN_multi_class_classification/assets/145346713/b6b34df3-4dad-49f3-9c65-e0c187eb5ece)

8. Adding weights to different claases using inverse class frequency weighting method and setting the hyperparameters

![image](https://github.com/RemyaVKarthikeyan/ANN_multi_class_classification/assets/145346713/e198109f-4931-4d82-ad27-291ac691d919)

9.Evaluating Neural Network

![image](https://github.com/RemyaVKarthikeyan/ANN_multi_class_classification/assets/145346713/de00c791-a866-4390-a13e-b0d4361b6149)

![image](https://github.com/RemyaVKarthikeyan/ANN_multi_class_classification/assets/145346713/77987b24-6197-46ea-a302-7df077a169ce)

10.Importing the confusion_matrix and classification_report functions to evaluate our model performance on the test data and genertaing predictions

![image](https://github.com/RemyaVKarthikeyan/ANN_multi_class_classification/assets/145346713/d84605e8-5d18-405e-8801-7861eba1e597)

11.Visualizing confusion matrix using sns heatmap

![image](https://github.com/RemyaVKarthikeyan/ANN_multi_class_classification/assets/145346713/ff26bdd0-47f2-4273-8a2e-0f2aa6e41138)

12.Priniting classification_report  to view some key evaluation metrics for the model

![image](https://github.com/RemyaVKarthikeyan/ANN_multi_class_classification/assets/145346713/1e7cce00-2127-46a8-aff3-f1a4700590be)














