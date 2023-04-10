# Hotel-Booking-Cancellation-Prediction-with-Logistic-Regression
This is a project to predict hotel booking cancellations using a Logistic Regression model. The goal of this project is to build a predictive model that can help hotel managers better understand which bookings are more likely to be cancelled, so that they can take proactive measures to mitigate cancellations and improve their business operations.
## Dataset
The dataset used in this project is from BRAEMAR Hotel & Resorts, which contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things.
The column is_canceled is also present in the dataset which has two values 1 and 0 represent booking canceled or Not respectively.
## Model
We have used a Logistic Regression model to predict whether a booking is likely to be cancelled or not, based on the features in the dataset. The model was trained on a subset of the data and then evaluated on a holdout set to assess its performance.
## Repository Contents
- data/: Folder containing the dataset used in the project
- notebooks/: Jupyter notebooks containing the code for data exploration, model training and evaluation
- models/: Folder containing the trained Logistic Regression model
- requirements.txt: File containing the Python libraries required to run the code
- README.md: This file
## Getting Started
To run this project on your local machine, you will need to clone this repository and install the required Python libraries listed in 'requirements.txt'. The Jupyter notebooks in the notebooks/ folder can be run in order to reproduce the data exploration, model training, and evaluation steps.
## Conclusion
In this project, we were able to build a Logistic Regression model that predicts hotel booking cancellations with reasonable accuracy. This model can be used by hotel managers to gain insights into their business operations and take proactive measures to reduce cancellations and improve customer satisfaction.
