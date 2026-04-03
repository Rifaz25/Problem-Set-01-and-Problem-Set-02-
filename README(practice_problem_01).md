# Problem-Dataset-01
🧠 Approach  

This project is designed as a binary image classification problem, where the goal is to classify chest X-ray images into two categories:

Normal
Pneumonia   
 
A Convolutional Neural Network (CNN) is used because it is highly effective in extracting spatial features from images such as edges, textures, and patterns. The model learns directly from pixel data without requiring manual feature extraction.

The overall approach involves training the CNN on labeled X-ray images and then using the trained model to predict the class of unseen images.

⚙️ Methodology
1. Data Preparation
The dataset contains 5,863 chest X-ray images
Organized into:
train/
val/
test/
Each folder contains two subfolders:
NORMAL
PNEUMONIA

2. Data Preprocessing
Images resized to a fixed size (e.g., 150×150)
Pixel values normalized to range [0,1]
Data augmentation applied on training set:
Rotation
Zoom
Horizontal flipping

3. Model Architecture

A CNN model was built using:

Convolutional layers for feature extraction
ReLU activation function
MaxPooling layers for dimensionality reduction
Fully connected (Dense) layers for classification
Output layer with Sigmoid activation for binary classification

4. Model Training
Loss Function: Binary Crossentropy
Optimizer: Adam
Batch Size: 32
Epochs: 10 (can be increased for better performance)

The model was trained using the training dataset and validated using the validation dataset.

5. Model Evaluation

The trained model was evaluated using:

Accuracy
Confusion Matrix
Precision, Recall, and F1-score

Testing was performed on unseen data from the test set.

📈 Findings
The CNN model achieved high accuracy in classifying chest X-ray images
It successfully learned important visual patterns associated with pneumonia
Data augmentation helped improve generalization and reduce overfitting

 
