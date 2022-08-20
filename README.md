# Covid-19-Status-Predictor


For the Graphs and Predictions - COVID 19 Patients Notebook we imported Covid-19 patient data from the Mexican Government (https://www.gob.mx/salud/documentos/datos-abiertos-152127), preprocessed it and plotted some insightful visualisations using ggplot and seaborn. Following this we use Gradient Boosting Classifier to showcase symptom importance regarding death, ICU admission and intubation. We use K-Nearest-Neighbors, Decision Trees, Logistic Regression, Support Vector Machines, Random Forest and Gradient Boosting to predict patient death based on symptoms. Decision Trees achieve the best accuracy (0.79), followed by Logistic Regression and SVM. Lastly we predict individual patient status (deceased or not) based on the user's symptoms input. 


For the Disease Symptoms Prediction Notebook we use a dataset derived from Kaggle that contains the most common symptoms found per disease. We explore the correlation between diseases and certain symptoms and we remove symptoms that had a correlation of more than 0.8. For the prediction of the disease based on the patient's symptoms we use Linear Regression, Logistic Regression, Decision Tree Regression, Random Forest Regression, SVM Regression, KNN Regression, Naive Bayes Classification, Decision Tree Classification, Random Forest Classification, SVM Classification and KNN Classification. The user inputs the symptoms and gets the prognosis based on the different prediction methods.

Co-authored by Athanasios Papanikolaou
