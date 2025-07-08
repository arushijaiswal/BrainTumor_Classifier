Brain Tumor Classification using Naive Bayes:
This project applies a **Gaussian Naive Bayes classifier** to predict brain tumor types based on gene expression data. It uses machine learning techniques like preprocessing, feature scaling, and cross-validation to ensure robust model performance.


Dataset
- File: `Brain_GSE50161.csv`
- Classes: `Normal`, `Ependymoma`, `Glioblastoma`
- Source: Gene Expression Omnibus (GEO)

> Make sure to upload the dataset manually in Google Colab or place it in your working directory.



Project Workflow:
1. Load and preprocess the dataset
2. Encode categorical target labels
3. Handle missing values using mean imputation
4. Feature scaling using StandardScaler
5. Train the model using **Gaussian Naive Bayes**
6. Evaluate using accuracy, classification report, and confusion matrix
7. Perform 5-fold cross-validation
8. Visualize results using plots



Technologies & Libraries Used:
- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib

Install dependencies :
pip install pandas numpy scikit-learn matplotlib seaborn


How to Run:
1. Open the notebook in **Google Colab** or Jupyter Notebook.
2. Upload the `Brain_GSE50161.csv` file.
3. Run all the cells to see results and visualizations.


Sample Output:
* Accuracy Score
* Classification Report
* Confusion Matrix Heatmap
* Cross-validation Accuracy Plot

You will see results printed in the output section and visualizations generated using matplotlib and seaborn.


Author:
ARUSHI JAISWAL

