Project Overview:


This project aims to provide a real-time solution for detecting vitiligo in video feeds. By leveraging CNNs and OpenCV, it can analyze camera input to identify frames that potentially contain signs of vitiligo. A GUI built with Tkinter makes it easy to use, providing a simple interface for live video analysis.

Requirements:
Python 3.7 or later,
TensorFlow 2.x,
OpenCV,
Pillow,
Tkinter,
Architecture.


Model: The model is a Convolutional Neural Network designed to classify frames into two categories: "Vitiligo" or "No Vitiligo." It comprises several convolutional layers, followed by dense layers for classification.
Video Feed: The live video feed is captured using OpenCV, processed with Pillow for Tkinter compatibility, and displayed in the GUI.
GUI: Built with Tkinter, the GUI provides a simple interface for interacting with the video feed and displaying the results of the detection.
Model Training
The CNN model was trained on a dataset of images labeled as either containing vitiligo or not. The dataset was split into training and testing sets, and the model was optimized to maximize accuracy. During training, various data augmentation techniques were used to increase the robustness of the model.

Methodology
Data Collection: The project began with collecting a dataset of images with and without signs of vitiligo.
Data Preprocessing: Images were resized and normalized to ensure compatibility with the CNN model.
Model Architecture: A CNN with multiple convolutional and dense layers was defined to classify images into binary categories.
Training: The model was trained using TensorFlow, with binary cross-entropy as the loss function and Adam as the optimizer.
Real-Time Detection: OpenCV was used to capture real-time video from the webcam, and Pillow was used to process frames before feeding them into the CNN model for prediction.



Contributing


Contributions are welcome! If you'd like to contribute to the project, please:



Fork the repository on GitHub.


Create a new branch for your feature or bug fix.


Submit a pull request with a detailed explanation of your changes.


Ensure your code follows the existing style and is well-documented.



RESULT:
![image](https://github.com/kashayp0607/Vitiligo-Detection/assets/105981293/e4b20c8f-5001-4606-8221-b144c54f11a7)
