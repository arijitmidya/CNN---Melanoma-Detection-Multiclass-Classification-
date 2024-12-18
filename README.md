# CNN---Melanoma-Detection-Multiclass-Classification-

## 1. General Information
- Building a CNN architecture for Melanoma Detection
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC).

## 2. Preprocessing

- Data Augmentation to increase training data
- Leveraging Augmenter class to hnadle class level inbalance

## 3. Notebook Structure

1. Import necessary libraries
2. Import the Dataset
3. Segregating the Dataset into Training and validation set
4. Data Visualization
5. Create the baseline model - Model 1
6. Data Augmentation strategy
7. Create Model 2 - adding Dropout Layer as part of the architecture
8. Class Inbalance Analysis
9. Rectify the class imbalance
10. Train the model on the data created using Augmentor - Model 3

## 4. Observations and optimization opportunities

1. The model can be further improved by increasing number of Epochs with Early stopping
3. Increasing training data by adding  images using the Augmenter class and training on it
3. Explore multiple Batch sizes 64 , 128 , 256 ...
4. Explore different positioning of Batch normalization
5. Build a deeper neural network with additional Convolutional layers
6. Build a wider neural network with bigger filters
7. Try different optimizer like RMSprop or SGD
8. Try different Dropout rate like 0.3 or 0.4
9. Try out of the box CNN models like ResNet


## 5. Technologies Used
- tensorflow
- pandas
- numpy
- matplotlib
- Seaborn
- Augmentor



## Contact
Created by [@arijitmidya] - feel free to contact me!


