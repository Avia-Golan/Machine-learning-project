This project involves developing a Machine Learning solution for classifying 12 types of cells (malignant and non-malignant) based on protein expression levels within the cells. The data represents various types of mouse cancer cells, classified by their growth rate (malignancy level) based on laboratory experiments -  This project was conducted in collaboration with a lab at the Hebrew University. The goal was to identify the models that would best fit the nature of the data, using four different algorithms—Random Forest, Logistic Regression, SVM, and Decision Tree—to predict whether the cells are malignant or non-malignant. Additionally, the project includes data feature analysis and model performance evaluation, with the aim of drawing biological conclusions regarding cancer cell malignancy based on proteomic data.

Protein Correlation Analysis:

The project began by checking protein correlation in the data to identify high correlation between features, which was found. This step was performed to adapt the classification method and model building. Due to high correlation among proteins, the models were adjusted accordingly. The most influential proteins related to cell malignancy were selected, and it was noted that Decision Tree, Random Forest, and Logistic Regression with L2 regularization allowed identifying key proteins. In contrast, SVM was less effective in ranking proteins by their influence.

Model Comparison and Protein Selection:

Multiple models were applied to identify key proteins, with the main proteins being repeated in at least two models. The final selection of key proteins relied on the Random Forest and L2 models, which showed consistency in the proteins they identified. The 10 most influential proteins for each model were presented in the project. Based on the results, it was suggested that the protein lists generated by the Random Forest and L2 models be prioritized, as these models provided a simpler way to identify the main proteins.
