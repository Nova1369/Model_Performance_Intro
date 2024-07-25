# Model_Performance_Intro
Checks performance of different models after feature extraction

<br>
a.
Model 1: Add a convolution layer with 32 3×3 filters with stride 2 and relu activation. Add a maxpooling layer with kernel size 2×2 with stride 1. Add a convolution layer with 16 4×4 filters with stride 2 and relu activation. Add a maxpooling layer with kernel size 4×4 with stride 2. Flatten the output and add a fully connected layer with 8 neurons with relu activation. Add a fully connected layer with 10 neurons and softmax activation. Extract the features from second last fully connected layer having 8 neurons and model it using a Random Forest classifier. Use Adam optimizer with batch size 128, learning rate 0.01 and epochs set t o 5.
</br>

<br>
b.
Model 2 : Add a convolution layer with 32 3×3 filters with stride 2 and relu activation. Add an average pooling layer with kernel size 2×2 with stride 1. Add a convolution layer with 16 4×4 filters with stride 2 and relu activation. Add an average pooling layer with kernel size 4×4 with stride 2. Flatten the output and add a fully connected layer with 8 neurons with relu activation. Add a fully connected layer with 10 neurons and softmax activation. Extract the features from second last fully connected layer having 8 neurons and model it using a Random Forest classifier. Use Adam optimizer with batch size 128, learning rate 0.01 and epochs set to 5.
</br>

<br>
c.
Model 3 Extract the deep features from Model 1 and Model 2 stack the features horizontally and model it using a Random Forest classifier.
</br>

<br>
d.
Model 4: Extract the deep features from Model 1 and Model 2 stack the features horizontally , r e duce the dimension to either 8, 10 or 12 using principal component analysis PCA and model the reduced features using a Random Forest classifier. Identify the best number of reduced components of PCA.
</br>
