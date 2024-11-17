# LIVE AT : https://skin-disease-prediction-app-4qdzwwpvna2fxpfns8ay6d.streamlit.app
# Skin-Disease-Prediction-Streamlit
This repository contains code for predicting skin diseases using deep learning techniques with a web-based graphical user interface (GUI) built using Streamlit. The model is trained on a dataset of skin disease images and can classify different types of skin diseases with high accuracy.

# About
Skin diseases are common and can significantly impact an individual's health and quality of life. Early detection and accurate diagnosis of skin conditions are crucial for effective treatment. This project aims to provide a simple, user-friendly web application for automated skin disease prediction using deep learning algorithms.

C# ode Overview
The key components of the code include:

Loading a pre-trained MobileNet V2 model from TensorFlow Hub.
Building a deep learning model architecture using Keras.
Compiling the model with an appropriate optimizer, loss function, and evaluation metrics.
Creating a web-based GUI using Streamlit for user interaction.
Preprocessing images, predicting diseases, and displaying results in the web interface.
# About Dataset
The dataset used for training includes images of various skin diseases that have been collected from the internet. It contains the following eight classes of skin diseases:
In this dataset image collected from internet.In this dataset there are total 8 class ,They are

1.	Bacterial Infections- cellulitis

2.	Bacterial Infections- impetigo

3.	Fungal Infections - athlete -foot

4.	Fungal Infections - nail-fungus

5.	Fungal Infections - ringworm

6.	Parasitic Infections - cutaneous-larva-migrans

7.	Viral skin infections - chickenpox

8.	Viral skin infections - shingles

The dataset was sourced from:
https://www.kaggle.com/datasets/subirbiswas19/skin-disease-dataset

# Usage
Follow these steps to use the application:

1. Clone the repository to your local machine:

        bash git clone https://github.com/Shrikant-Bodkhe/skin-disease-prediction-streamlit.git
2. Install the required dependencies:

        bash pip install -r requirements.txt
3. Run the main script to launch the Streamlit app:

        bash streamlit run app.py

Once the application is running, the Streamlit web interface will open in your default browser.

Upload an image of a skin condition through the file uploader interface.

After uploading, click the "🧠 Predict Skin Condition" button to get the predicted skin disease along with the confidence level.

The predicted disease label and confidence percentage will be displayed below the image.

# Contributors
Shrikant Bhaginath Bodkhe
