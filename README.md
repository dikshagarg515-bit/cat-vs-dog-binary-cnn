# 🐱🐶 Cat vs Dog — Binary Image Classification (CNN)

## 📌 Objective
Build a Convolutional Neural Network (CNN) to classify images as either
a cat or a dog using deep learning.

## 📊 Dataset
- **Dataset:** Microsoft Cats and Dogs Dataset
- **Classes:** Cat 🐱 / Dog 🐶 (Binary Classification)
- **Format:** JPEG images organized in folders by class

## 🛠️ Technologies Used
- Python
- TensorFlow & Keras
- NumPy & Pandas
- Matplotlib
- Scikit-learn
- Google Colab

## 🧠 Model Architecture
- Conv2D layers for feature extraction
- MaxPooling2D for downsampling
- Flatten layer
- Dense layers for classification
- Output: Sigmoid activation (binary classification)

## ⚙️ How It Works
1. Load and preprocess cat/dog images
2. Split into training and test sets
3. Build a Sequential CNN model using Keras
4. Train the model on image data
5. Evaluate accuracy on test images

## 💡 What I Learned
- How CNNs extract features from images using convolutional layers
- Difference between binary and multi-class classification
- How to build and train deep learning models with Keras
- Handling and preprocessing image datasets

## 🚀 How to Run
1. Open `binaryCNN_MN5.ipynb` in Google Colab
2. Upload the `CATANDDOG.zip` dataset
3. Run all cells
