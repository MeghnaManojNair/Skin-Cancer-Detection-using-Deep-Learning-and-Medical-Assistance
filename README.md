# CSE4019-Digital-Image-Processing---Skin-Cancer-Detection-using-Deep-Learning-and-Medical-Assistance
Skin cancer, particularly melanoma, is a significant health concern globally. Early detection plays a crucial role in successful treatment outcomes. Leveraging advancements in deep learning and medical assistance, this project aims to develop an application that assists in the early detection of melanoma and provides users with essential medical guidance. The application will be developed using Python, JavaScript, HTML, and CSS. It will utilize a vast dataset comprising thousands of images sourced from a medical repository on Kaggle. This dataset will include images of skin affected by melanoma at various stages. Upon accessing the application, users can upload an image of a portion of their skin. The uploaded image will be processed by a trained deep learning model designed to detect skin cancer. The model will output a prediction rate indicating the likelihood of melanoma. If the prediction exceeds a predefined threshold of 75%, users will be alerted as they fall into the high-risk category. For high-risk users, the application will prompt them to provide their location and basic details. It will then display information about nearby hospitals specializing in dermatology and cancer treatment services. This feature aims to encourage users to seek medical assistance promptly. Additionally, the application will feature an interactive chatbot providing users with information, clarifications, and updates related to skin cancer detection and treatment.

Steps to execute the project:

Step 1: Download the ISIC Skin Cancer Classification Dataset from: https://www.kaggle.com/competitions/siim-isic-melanoma-classification/data

Step 2: Execute the "model.ipynb" file in order to train and develop the CNN Model for classification of skin cancer images

Step 3: Save the trained model as "model.h5"

Step 4: Install flask in your system using the command: pip install flask

Step 5: Then execute the python file "integrate.py" by running the command: flask integrate.py

Step 6: Open up the index.html file from the "Web Application" Directory or by heading over to 127.0.0.5

Step 7: In the web application, switch over to "Detect Cancer" tab in the navigation bar, upload the lesion image and analyze the type of cancer detected by the model

Step 8: In order to get a list of hospitals near the location of the user, head over to the "Seek Help" tab in the navigation bar, enter the location address and view the hospitals and health centers nearby which offer cancer treatment

