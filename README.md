# Face-emotion-recognition

**Overview**

This project is an implementation of a Face Emotion Recognition system using Convolutional Neural Networks (CNN). The goal of this project is to accurately recognize emotions from facial expressions in real-time images or video streams. The model is designed to detect and classify various facial expressions, including happiness, sadness, anger, surprise, fear, and neutral emotions.

**Features**

Real-time Emotion Recognition: The CNN model is capable of analyzing facial expressions in real time, making it suitable for applications that require live emotion detection from camera feeds or video streams.

**Multi-class Emotion Classification:**

The model can classify facial emotions into multiple classes, such as happiness, sadness, anger, surprise, fear, and neutral, providing a comprehensive understanding of the subject's emotional state.

**Deep Learning Architecture:** 

The CNN architecture used for emotion recognition is capable of automatically learning and extracting meaningful features from facial images, enabling accurate emotion prediction.

**Pre-trained Model Option:**

For faster development and deployment, a pre-trained CNN model may be included as part of this project. However, it is recommended to train the model on a custom dataset specific to the user's application for optimal accuracy.

**User-friendly Interface:**

The implementation may include a user-friendly interface that allows users to interact with the emotion recognition system easily.

**Dataset**

The emotion recognition model requires a labeled dataset of facial images representing different emotional expressions. A popular dataset "FER-2013" was used for training the model. Ensure that the dataset is divided into training, validation, and testing subsets to evaluate the model's performance.

**Outputs**

<img width="960" alt="Screenshot 2023-07-17 044333" src="https://github.com/Grunt-prog/Face-emotion-recognition/assets/86661317/75f06ca1-9d3a-4858-aaaf-1ed477281d75">

<img width="960" alt="Screenshot 2023-07-17 044216" src="https://github.com/Grunt-prog/Face-emotion-recognition/assets/86661317/79e692b6-239b-46fd-aa8a-e13b5a28b44c">

<img width="960" alt="Screenshot 2023-07-17 044139" src="https://github.com/Grunt-prog/Face-emotion-recognition/assets/86661317/f5fe54c5-4b61-4068-91e6-d5ec65a22589">

<img width="960" alt="Screenshot 2023-07-17 044206" src="https://github.com/Grunt-prog/Face-emotion-recognition/assets/86661317/866a7509-fd9d-4441-b7ee-b5493839b64a">

**Code Files Summary:**

To create a face emotion model, we start by using the "face-emotion.ipynb" notebook in Google Colab. This notebook generates two crucial files: a JSON file containing the model architecture and a .h5 file containing the learned weights of the model. The model is trained to recognize emotions from facial expressions.

Google Colab's powerful GPU acceleration is utilized to expedite the computation during the training process, ensuring faster model convergence and reduced training time.

Once the model files (JSON and .h5) are generated, we can proceed to implement the inference step using the "face-emotion.py" script. By loading the model architecture and weights from the respective files, we can utilize the trained model to predict emotions from new facial images.

In summary, we leverage Google Colab with GPU acceleration to efficiently train and generate the face emotion model files, and then integrate these files into the "face-emotion.py" script to perform emotion recognition on unseen facial data. This approach combines the benefits of cloud-based computing and GPU acceleration to achieve accurate and efficient emotion prediction from facial expressions.
