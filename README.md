Name: Soundarya Sunil Patil
Company: CODTECH IT SOLUTIONS
ID: CT6DS777
Domain: Data Science
Duration: July 1st To August 15th 2024
Mentor: Neela Santhosh Kumar
Task- 2

 OVERVIEW OF THE PROJECT

 Project: DeepLearning Image Recognition on Plant Disese Prediction using Convolutional Neural Networks (CNN)

 This project is a web application that uses machine learning to classify images of plants and identify potential diseases. Here's a breakdown of how it works:
Overview

Technology Stack: The project utilizes Python with libraries such as TensorFlow for the machine learning model, PIL (Pillow) for image processing, and Streamlit for creating the web interface.
Key Components

Model Loading:
The application loads a pre-trained TensorFlow model designed for plant disease prediction from a specified file path. This model has been trained on a dataset of plant images to recognize various diseases.

Class Indices:
A JSON file containing class indices is loaded, mapping the predicted class index (output from the model) to human-readable class names (e.g., specific plant diseases).

Image Processing:
The function load_and_preprocess_image handles the loading and resizing of uploaded images. It converts images to a format suitable for the model by resizing them to 224x224 pixels, normalizing pixel values to a range of [0, 1], and adding a batch dimension.

Prediction Function:
The predict_image_class function takes an image path and uses the model to predict the class of the plant disease. It preprocesses the image and retrieves the class name based on the model's output.

User Interface with Streamlit:
The app features a user-friendly interface where users can upload an image of a plant. Upon uploading, the image is displayed, and a button allows users to classify the image.
When the "Classify" button is clicked, the app processes the image and displays the predicted disease.

User Interaction
Users can upload images in formats like JPG, JPEG, or PNG. The application provides immediate feedback by showing the predicted disease after classification, enhancing user engagement and providing valuable insights for plant care.
This project effectively combines machine learning and web development to create a practical tool for identifying plant diseases, which can be beneficial for farmers, gardeners, and agricultural researchers.
