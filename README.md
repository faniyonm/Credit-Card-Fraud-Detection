# Credit Card Fraud Detection

- **Load the Dataset:** Loaded the credit card dataset into a DataFrame, checked its dimensions, and examined its structure with summary statistics.  

- **Exploratory Data Analysis:** Analyzed the class distribution between normal and fraudulent transactions, calculated the fraud ratio, and visualized correlations between features using a heatmap.  

- **Preparing the Data:** Separated features (X) and target (Y), split the dataset into training and testing sets.  

- **Building and Training the Model:** Trained a Random Forest classifier on the training data.  

- **Evaluating the Model:** Generated predictions on the test set, evaluated performance with a confusion matrix, classification metrics, ROC-AUC, and precision-recall curve. The model achieved **high accuracy (0.9996)**, strong **precision (0.9747)**, good **recall (0.7857)**, an **F1-score of 0.8701**, and an **MCC of 0.8749**, showing it reliably detects fraud with very few false alarms, though some fraudulent cases were missed.  

