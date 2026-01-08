# iris-classifier-neural-network
neural network for classifying iris flowers into 3 species with 93% accuracy using PyTorch.

 Results:
Test Accuracy: 93.3% (28/30 correct predictions)
Training Time: < 1 minute
Final Loss: 0.038

 Model Architecture
Input Layer (4 features)
Hidden Layer 1 (8 neurons) --> ReLU
Hidden Layer 2 (9 neurons) --> ReLU
Output Layer (3 classes) --> LogSoftmax


Dataset Features:
Input Features--> (flower measurements in cm):
Sepal Length
Sepal Width
Petal Length
Petal Width
  
Output Classes:
 Setosa (0)
 Versicolor (1)
 Virginica (2)




Data:
url='https://gist.githubusercontent.com/curran/a08a1080b88344b0c8a7/raw/0e7a9b0a5d22642a06d3d5b9bcbad9890c8ee534/iris.csv'


 Technologies
 PyTorch
 Pandas (data manipulation)
 NumPy
 Matplotlib (visualization)
 scikit-learn (train/test split)

 Key Features
 Feedforward neural network from scratch
 Train/test split methodology
 Cross-entropy loss optimization
 Adam optimizer with learning rate tuning
 Model persistence (save/load)

 Training Process
Epochs: 200
Learning Rate: 0.01
Optimizer: Adam
Loss Function: Cross-Entropy

