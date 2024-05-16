# Bioactivity Prediction App

This application is designed to predict the bioactivity of compounds towards inhibiting the Acetylcholinesterase enzyme, a crucial drug target for Alzheimer's disease.

## Features

- Upload your CSV data: The application accepts a CSV file as input. The CSV file should contain the molecular structures of the compounds.

- Molecular descriptor calculation: The application calculates molecular descriptors for the uploaded compounds using the PaDEL-Descriptor software.

- Bioactivity prediction: The application uses a pre-trained machine learning model to predict the bioactivity of the compounds. The model was trained on a dataset of known bioactivities of various compounds against the Acetylcholinesterase enzyme.

- Download predictions: The application allows you to download the predictions as a CSV file.

## How to Use

1. Clone this repository to your local machine.
2. Install the required Python packages using the command `pip install -r requirements.txt`.
3. Run the application using the command `streamlit run app.py`.
4. Open the application in your web browser using the URL provided by Streamlit.
5. Upload your CSV data using the file uploader in the sidebar.
6. Click the 'Predict' button to calculate molecular descriptors and predict bioactivity.
7. Download the predictions using the 'Download Predictions' link.

## Requirements

- Python 3.6 or later
- Streamlit
- Pandas
- PIL
- Subprocess
- OS
- Base64
- Pickle

## Note

This application is for research purposes only. The predictions made by the application should not be used for medical or clinical decisions.
