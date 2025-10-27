# Breast Cancer Diagnosis App
It is a machine-learning app designed to assist medical professionals in determining if a breast cancer cell is benign or malignant. It provides a visual representation of the input data using radar chart and displays predicted diagnosis and the probability of the mass being benign o amlignant. it has toggle side bar that can be used for manually inputing the measurements

The app was developed aa a learning ptoject using [Breast Cancer Wisconsin (Diagnostic) Data Set](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

A deployed version of this app can also be found on [Streamlit Community Page](https://cancerassist-wwjac4bhyem2wpjcf6cxgh.streamlit.app)



## Installation 
You can install the dependencies using virtual environment in your IDE of choice 

``
python3 -m venv venv
source ./venv/bin/activate
``

To install the required packages, run:

``
pip install -r requirements.txt
``


## Running the app

To run the app, type into the terminal:

``
streamlit run app/main.py
``

The app will then open in your default browser, where you can use the image of the cells to analyse and adjust various settings and receive the prediction.
