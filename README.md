

This project is a real-time American Sign Language (ASL) recognition system that translates fingerspelling hand gestures into text and speech to assist communication for Deaf and Mute individuals. It utilizes a webcam to capture gestures, employing MediaPipe to accurately extract hand landmarks regardless of background clutter or lighting conditions. These landmarks are mapped onto a white background to process through a Convolutional Neural Network (CNN) built with Keras and TensorFlow. 

To improve prediction reliability, the 26 ASL alphabet letters are grouped into 8 primary classes, achieving an impressive 97-99% accuracy. Finally, the recognized gestures are combined into complete words and converted into an audio format using the `pyttsx3` library, creating a seamless and accessible human-computer interface.
