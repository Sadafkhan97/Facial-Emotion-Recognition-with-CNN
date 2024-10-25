#Facial Emotion Recognition with CNN

This project implements a Facial Emotion Recognition model using a Convolutional Neural Network (CNN) built with TensorFlow and Keras. The model classifies images into seven distinct facial emotions: Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral. By leveraging deep learning, this project demonstrates practical applications for emotion detection in fields like user experience enhancement, mental health monitoring, and automated video analysis.

##Features

1. Dataset Preprocessing: Loads images, crops face regions, and resizes images to a fixed dimension.
2. CNN Model Architecture: Utilizes multiple convolutional and pooling layers for accurate emotion classification.
3. valuation: Provides accuracy, loss curves, and a confusion matrix for performance analysis.
4. Model Saving: Saves the complete model as well as architecture and weights separately.
   
##Installation

Clone the repository:

git clone : https://github.com/Sadafkhan97/Facial-Emotion-Recognition-with-CNN/tree/main

Install the required packages:

pip install -r requirements.txt

Ensure the dataset is organized in the following structure:
/data
  ├── origin/
  └── label/label.lst
  
##Usage

Run the emotion_recognition.py script to preprocess the dataset, train the model, and evaluate its performance:
python emotion_recognition.py

Adjust parameters for training (epochs, batch size, etc.) and model configuration as needed.

##Results

The model achieves a test accuracy of around [insert accuracy here]%. Below is an example of the accuracy and loss curves generated during training.

##Confusion Matrix

The confusion matrix provides insight into the model's performance across the emotion categories, highlighting where improvements can be made.


##License

This project is licensed under the MIT License.

##Contact

For queries or collaboration opportunities, please reach out at khansadaf1836@gmail.com or connect on https://www.linkedin.com/in/sadaf-khan-389874208/.

#DeepLearning #MachineLearning #ComputerVision #EmotionRecognition #FacialRecognition #TensorFlow #Keras #Python #DataScience #AIProjects #ImageClassification
