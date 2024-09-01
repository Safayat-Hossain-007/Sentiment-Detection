# Sentiment Detection

Humans often rely on non-verbal cues to communicate effectively. Emotions add depth and clarity to our thoughts and ideas. It becomes particularly fascinating when a computer can recognize and interpret these complex human emotions. This project outlines the process of building a model that detects emotions from images.

## Key Steps

### 1. Data Gathering and Augmentation
- The dataset used is "FER2013," which can be downloaded from this [link](https://github.com/npinto/fer2013).
- Image augmentation techniques were applied to enhance the dataset.

### 2. Model Building
- The model architecture consists of Convolutional Neural Network (CNN) layers, followed by Max Pooling, Flatten, and Dropout layers.

### 3. Training
- The model was trained by experimenting with different combinations of the layers mentioned above and adjusting various hyperparameters.
- The best-performing model achieved a validation accuracy of **60.1%**.

### 4. Testing
- The model was tested with sample images, and it successfully detected the following seven emotions:
  - **Angry**
  - **Sad**
  - **Neutral**
  - **Disgust**
  - **Surprise**
  - **Fear**
  - **Happy**

## Usage

### For Face Detection and Emotion Detection Code:
Refer to the notebook [Emotion_Detection.ipynb](./Emotion_Detection.ipynb).

### To Train Your Own Emotion Detection Model:
- Follow the instructions in the [facial_emotion_recognition.ipynb](./facial_emotion_recognition.ipynb) notebook.
- Pre-trained model weights are available in the `/Models` directory.

### For Emotion Detection Using Webcam:
1. Clone the repository.
2. Install the required dependencies by running:
   ```bash
   pip install -r requirements.txt
   python Emotion_Detection.py


