# Driver-Drowsiness-Detection-using-Deep-Learning

This project aims to develop a deep learning-based system to detect driver drowsiness using eye images. The system uses a convolutional neural network (CNN) to classify eye images as either "open" or "closed", indicating whether the driver is awake or drowsy. The project utilizes Python programming language and Jupyter Notebook for development and testing.

# Objects :-

1) EyeImage: Represents an eye image, which is the input to the system.
   
Attributes:

image_data: The pixel values of the eye image.

label: The label of the eye image, either "open" or "closed".

2) CNNModel: Represents the convolutional neural network model used for driver drowsiness detection.
   
Attributes:-

model_architecture: The architecture of the CNN model.

model_weights: The trained weights of the CNN model.

3) DriverDrowsinessDetector: Represents the driver drowsiness detector object, which uses the CNN model to detect drowsiness.

Attributes:

cnn_model: The trained CNN model used for detection.

Methods:-

detect_drowsiness(): Takes an eye image as input and detects whether the driver is drowsy or not.

# Requirement ( library & IDE ) :-

Download and Install :- jupyter notebook 

library :-

Pillow, tensorflow==2.14.0, protobuf==3.20.*, streamlit==1.5.1, opencv-python, click==7.1.2 , pygame, altair==4

# Tools and Technologies:

Python programming language

Jupyter Notebook for development and testing

Deep learning framework (Keras) for building and training the CNN model

MRL Eyes Data dataset for training and testing the model
 

# Detailed steps to set up the project :-

# Step 1: Download the model.keras file.

Download the model.keras file from the provided link: https://drive.google.com/file/d/1qGmTM_XD_9uq2VkDEScKs-dkyvl4dP2p/view?usp=sharing

# Step 2: Download the MRL Eyes Data file.

Download the MRL Eyes Data file from the provided link: https://drive.google.com/file/d/1yePKN89sTQxpTNyiq9AMhK2pchNbww4x/view?usp=sharing

# Step 3: Extract the MRL Eyes Data file.

Extract the downloaded MRL Eyes Data file to a folder named MRL Eyes Data.

# Step 4: Create a Prepared_Data folder.

Create a new folder named Prepared_Data inside the MRL Eyes Data folder.

# Step 5: Divide the data into Open Eyes and Close Eyes folders.

Create two subfolders inside the Prepared_Data folder: Open Eyes and Close Eyes.

# Step 6: After than run the Data Preparation.ipynb as its in the jupyter notebook.

# Step 7: Create train and test folders

Create two new folders inside the Prepared_Data folder: train and test.

# Step 8: Create Open Eyes and Close Eyes folders in train and test folders.

Create two subfolders inside the train folder: Open Eyes and Close Eyes. Create two subfolders inside the test folder: Open Eyes and Close Eyes.

# Step 9: Divide the data into train and test folders.

Move 2500 images from the Open Eyes folder in Prepared_Data to the Open Eyes folder in train. Move 2500 images from the Close Eyes folder in Prepared_Data to the Close Eyes folder in train. Move the remaining images from the Open Eyes folder in Prepared_Data to the Open Eyes folder in test. Move the remaining images from the Close Eyes folder in Prepared_Data to the Close Eyes folder in test.

# Step 10 :- And delete the empty two folder open eyes and close eyes folder.

# Step 11: Run Model Training.ipynb as its in Jupyter Notebook.

# Step 11 :- Then run the main.ipynb.

# Authors

[ Shivam Ghodekar ] - Developer and Maintainer.

# Contact

If you have any questions, issues, or feedback, please don't hesitate to contact us:

Email:- svghodekar1903@gmail.com

Instagram :- i_am_shivamghodekar

GitHub: https://github.com/svghodekar



