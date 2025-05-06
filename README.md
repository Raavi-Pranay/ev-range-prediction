
# EV Range Prediction & Visualization of Pollution Meter 
This project explores and compares the performance of two classification algorithms — Logistic Regression and Decision Tree — on a given dataset of EV Range and pollution emissions. It includes data preprocessing, model training, evaluation, and visualization.

## 📁 Files

- `TRIAL_16_LR_DT.ipynb`: Jupyter notebook containing all code and results.

## 🧠 Models Used

- **Logistic Regression**
- **Decision Tree Classifier**

## 📊 Evaluation Metrics

- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

## 🔧 Workflow Overview

1. **Import Libraries**  
   Load necessary Python libraries such as `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`.

2. **Load Dataset**  
   Read the dataset using `pandas`.

3. **Preprocessing**  
   - Handle missing values  
   - Encode categorical variables  
   - Normalize or standardize features if necessary  
   - Train-test split

4. **Model Training**  
   Train both Logistic Regression and Decision Tree on the training set.

5. **Model Evaluation**  
   Evaluate both models using test data and compare their performance with:
   - Accuracy score
   - Confusion matrix
   - Visualization (e.g., heatmaps)

6. **Conclusion**  
   Discuss which model performs better and in what context.

## 🧰 Requirements

Install the necessary Python packages using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 📌 Notes

- Make sure to use a compatible version of scikit-learn.
- Update the dataset path if necessary before running the notebook.

## 📜 License

This project is open for educational and non-commercial use.
