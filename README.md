# Transfer-learning-on-MNIST-Fasion-MNIST
Automated classification of items and numbers have always been an important topic in machine learning. 
Numerous methods have been invented to solve this problem. 
In this report, we used pre-trained model to extract useful features from the dataset first. 
Then, various techniques were employed on these extracted features to classify items. 
Two different datasets are used in this study.
1. MNIST dataset. It contains more than 60,000 training and 10,000 test 28*28 images of numbers.
2. Fashion-MNIST dataset. It contains  more than 60,000 training and 10,000 test 28*28 images of fashion apparel. 

We use ResNet-50 to extract useful features. It is first proposed by He Kaiming. We apply it by freezing its convolutional layers and blocks for feature extraction. Extracted features are used as inputs for fully connected layers to perform classification.
Since MNIST and Fashion-MNIST have identical format, we performed the same procedure on both
We also attempted to use WRN-50-2 to perform feature extraction. 


 Reference 
  [1] He K, Zhang X, Ren S, et al. Deep Residual Learning for Image Recognition[J].  2015:770-778.
  
  [2] Xiao H, Rasul K, Vollgraf R. Fashion-MNIST: a Novel Image Dataset for   Benchmarking Machine Learning Algorithms[J].  2017.
  
  [3] Lecun Y, Cortes C. The mnist database of handwritten digits[J].  2010



