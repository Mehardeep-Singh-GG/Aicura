Certainly! Here's the updated README file with a reference to the Google Colab file for detailed model training:

---

# Project README

## Project Overview:

This project focuses on training a model for diabetic retinopathy detection using Gaussian filtered images and a dataset containing information on kidney diseases.

## Files:

- **gaussian_filtered_images:** This directory contains Gaussian filtered images used for training the diabetic retinopathy detection model.

- **kidney_diseases_1.csv:** This CSV file contains data related to kidney diseases and is used for training the model. It's utilized in the `hj.py` script.

- **hj.py:** This Python script is responsible for training the model using the `kidney_diseases_1.csv` dataset.

- **diabetic_retinopathy.py:** This Python script is used for training the diabetic retinopathy detection model. It utilizes the Gaussian filtered images located in the `gaussian_filtered_images` directory. The original training process occurred in Google Colab files, which are listed below.

- **app.py:** This Python file contains the Flask application code that connects the frontend to the backend of the project.

## Usage Instructions:

1. **Uploading Data:**
   - To upload the `kidney_diseases_1.csv` dataset, follow these steps:
     - Locate the `kidney_diseases_1.csv` file in the project directory.
     - Use the appropriate command or method to upload the file to your desired location or platform.

2. **Training the Model:**
   - To train the model for diabetic retinopathy detection, execute the following steps:
     - Run the `hj.py` script, passing `kidney_diseases_1.csv` as input.
     - Run the `diabetic_retinopathy.py` script, ensuring that the `gaussian_filtered_images` directory is accessible. For detailed model training, refer to the Google Colab files listed below.

3. **Running the Application:**
   - To run the Flask application, execute the `app.py` script.
   - Access the application through the provided URL.

## Libraries Used:

- **OpenAI:** *(Version not specified)*
- **Flask:** Version 1.1.2
- **OS:** *(Standard library)*
- **ReportLab:** *(Version not specified)*
- **NumPy:** Version 1.19.2
- **Pandas:** Version 1.1.3
- **Matplotlib:** Version 3.3.2
- **Time:** *(Standard library)*
- **Pathlib:** *(Standard library)*
- **IPython.display:** 
- **Scikit-learn:** 
- **Google's GenerativeAI:** 

## Additional Information:

- For detailed model training, refer to the Google Colab files:
  -https://colab.research.google.com/drive/1P-ChGUiU61DuzHrLz_Gwu6ZrbYQMeGvM?usp=sharing
  https://colab.research.google.com/drive/1dz0E3nLpj68LQWRq6RQVcsE2Zfhqz3mu?usp=sharing

  Google Drive Link-https://drive.google.com/drive/folders/1IFWvak1a3zNPHZ9qBs8rBFrAu91_M2fe?usp=sharing
