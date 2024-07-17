# Plant-disease-detection-and-classification-using-CNN-Deep_Learning
This is an implementation of a Convolutional Neural Network (CNN) based deep learning model designed for the detection and classification of plant diseases from images. The model helps in identifying whether a plant is diseased or healthy, and if diseased, classifies the specific type of disease affecting the plant.The project is created using Streamlit App and deployed using Docker.
## Getting Started
Kaggle DataSet Link : https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset
Trained Model Link : https://drive.google.com/file/d/1i466c4XOs048Q54EPCqgzoG8zWcARnrj/view?usp=sharing](https://drive.google.com/file/d/1rKh-IElSdHTqax7XdfSdZTn-r8T_qWPf/view?usp=drive_link)https://drive.google.com/file/d/1rKh-IElSdHTqax7XdfSdZTn-r8T_qWPf/view?usp=drive_link
### Download and Copy the Code inside a new Folder and open VS Code
Open Google Collab : https://colab.research.google.com/

Link to a folder named : Plant-Disease of your Google Drive

Download Kaggle.json : DataSet Link->Logo->Settings->API->Create new Token

Save file in the same folder in Google Collab

Execute All the codes inside model_training_notebook->Plant_Disease_Prediction_CNN_Image_Classifier

After executing one File will be saved as:
### drive/MyDrive/Youtube/trained_models/plant_disease_prediction_model.h5
Copy this file inside Trained Model
### Go to VS Code
```
pip install -r app/requirements.txt
```
```
cd app
streamlit run main.py
```
Use samples given inside test_images
## Docker
Download Docker

Execure One-by-One
```
docker build -t plant-disease-prediction-image:v1.0 .
docker images
docker run -p 80:80 plant-disease-prediction-image:v1.0
```
Go to Localhost and Docker container will be successfully deployed


