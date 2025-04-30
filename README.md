# Signal-Classification-Using-Recurrent-Neural-Networks-RNNs-
This project demonstrates how Recurrent Neural Networks (RNNs) can be used to classify different signal types—sine, square, and triangle waves—based on their sequential patterns. The model is built using TensorFlow and Keras.
🚀 Project Overview This project follows these major steps: 
Data Generation Synthetic signals for sine, square, and triangle waves are generated using NumPy. 
Data Preprocessing The raw signals are transformed into input sequences and labeled accordingly for supervised learning.
Model Building An RNN model is constructed using Keras with an RNN layer and dense layers for classification. 
Model Training The model is trained using the Adam optimizer and Sparse Categorical Crossentropy loss function.
Model Evaluation The model is evaluated on test data to measure accuracy and generalization. 
Inference New signals are passed to the trained model for classification to demonstrate real-world usage. 
🛠 Requirements To run the project, install the following dependencies:  bash Copy Edit pip install tensorflow numpy scikit-learn matplotlib pandas
