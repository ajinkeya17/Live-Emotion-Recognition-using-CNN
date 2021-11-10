# Live-Emotion-Recognition-using-CNN
A dynamic method to determine emotions from a face of a person obtained from live video feed of computer's webcam.
Mini Xception CNN model was trained on FER2013 dataset. You can load and use the pre-trained model directly from real_time_video.py and it will directly open webcam and in a seperate window display emotional states as softmax output dynamically for the real time video.
The emotion_recognition_with_tags.py file will as a python output display the dominant emotional state as it is detecting from webcam video and raise an alert if same emotion detected for a certain number of frames.
The happy_test and sad_test are sample outputs obtained for a child's face.
