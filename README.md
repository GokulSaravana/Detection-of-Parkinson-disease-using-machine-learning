# Detection-of-Parkinson-disease-using-machine-learning
Overview:

This project aims to predict the presence of Parkinson's disease based on patient data using machine learning techniques. The project utilizes a Support Vector Machine (SVM) classifier with a linear kernel to build a predictive model. The model is trained on features such as MDVP measurements and acoustic parameters extracted from voice recordings.

Dependencies:
1)Python 3.x
2)pandas
3)scikit-learn
4)NumPy

Installation Instructions:
Install the classic Jupyter Notebook with:
       pip install notebook
To run the notebook:
      jupyter notebook
      
Usage:
1)Ensure that you have the Parkinson's disease dataset (Parkinson_disease.csv) in the project directory.
2)Run the provided Jupyter Notebook parkinsons_prediction.ipynb to train the predictive model and evaluate its performance.
3)Follow the instructions in the notebook to preprocess the data, train the model, and make predictions on new data.

Data:
The dataset (Parkinson_disease.csv) contains patient data, including MDVP measurements and acoustic parameters extracted from voice recordings. It consists of features such as MDVP:Fo(Hz), MDVP:Fhi(Hz), MDVP:Flo(Hz), and target variable 'status' indicating the presence or absence of Parkinson's disease.

Model:
The machine learning algorithm used in this project is Support Vector Machine (SVM) with a linear kernel (kernel='linear'). The model is trained on the provided dataset to predict the presence of Parkinson's disease based on patient features.

Results:
The performance of the predictive model is evaluated using accuracy metrics. The accuracy of the model on training and testing data is reported, along with predictions on new data.
