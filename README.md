Project Title:
Facial Emotion Recognition Using CNN and OpenCV

-----------------------------
Overview:

This project focuses on building a real-time facial emotion recognition system using a CNN model trained on grayscale facial images of size 48x48.

The goal is to classify emotions into seven categories: Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral

The system works in real time using the webcam. Once a face is detected:

The image is passed to the model

The prediction is displayed in the terminal and on the camera window

The prediction updates every 0.5 seconds only when a clear face is detected

-----------------------------
Libraries Used:

TensorFlow and Keras – to build and train the model

OpenCV – to capture the webcam and detect faces

NumPy and Pandas – for data handling

Matplotlib – for training visualization

Scikit-learn – for data splitting (if needed)

-----------------------------
Dataset Used:
https://www.kaggle.com/datasets/msambare/fer2013?resource=download

-----------------------------
Challenges Faced:

Overfitting after 35 epochs

Path issues on Windows (backslashes, incorrect paths)

Keras warning about saving in .h5 format

ModuleNotFoundError for some packages

‘Q’ key not always closing the camera

Model predicting without any face detected

-----------------------------
Output:

Emotion predictions are shown on both the terminal and the camera window.

Updated every 0.5 seconds.

Press “Q” to exit (camera window must be active).
