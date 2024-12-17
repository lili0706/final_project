# final_project
We want to predict the relationship between cancer-related diseases and drugs, and deep learning can help. Deep learning models are trained using data based on cancer diseases and drugs to predict whether specific drugs are effective for certain cancer diseases, where each cancer disease may respond to multiple drugs and each drug may treat multiple cancers.

Steps:

Load data: Read data on diseases, drugs, and disease-drug matches.

Screening for Cancer-Related Diseases: Screens for cancer-related diseases based on disease classification.

Identify corresponding drugs: Identify drugs used to treat cancer diseases based on disease-drug correspondence.

Create Feature Matrix: Extract certain features of a drug and create a feature matrix to train the neural network.

Create Labeling Matrix: Create a labeling matrix based on disease-drug associations.

Training Test Set Cut: Split the data into training set and test set.

Modeling: Build a model to predict.

Training Process: Train the model.

Model Evaluation: Evaluate the model on the test set and calculate the accuracy and ROC-AUC.

Dataset

This dataset is introduced in the paper, MiRAGE: Mining Relationships for Advanced Generative Evaluation in Drug Repositioning. It contains three CSV files: diseaseInfo, drugsInfo, and mapping.

•	diseaseInfo: This tabular dataset contains information on over 1,500 diseases.
•	drugsInfo: This file provides details on approximately1,400 drugs.
•	mapping: This file represents known drug interactions and disease interactions.

These datasets are well-suited for exploring various methods for binary prediction of drug-disease interactions. Leveraging these datasets can aid in the exploration and discovery of new drug repositioning opportunities.

