
# Titanic Survival Prediction 🚢

This project applies machine learning techniques to predict survival outcomes on the Titanic dataset, as part of Kaggle's classic competition: [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic).

## 📁 Project Structure

```
├── titanic dataset last.ipynb     # Main Jupyter Notebook for model development
├── data/
│   ├── train.csv                  # Training data from Kaggle
│   └── test.csv                   # Test data from Kaggle (no labels)
├── submission/
│   └── submission_rf.csv          # Final prediction file submitted to Kaggle
└── README.md                      # Project documentation
```

---

## 📊 Model Summary

We used several preprocessing steps including:

- Missing value imputation for `Age` and `Fare`
- Encoding of categorical variables (`Sex`, `Embarked`, `Pclass`)
- Feature selection and cleanup
- Model training with:
  - ✅ Logistic Regression → **Validation Accuracy: ~80.3%**
  - ✅ Random Forest → **Validation Accuracy: ~75.8%**

---

## 📤 Kaggle Submission

- Final predictions were made using the Random Forest model.
- The `submission_rf.csv` file was uploaded to Kaggle.
- ✅ **Kaggle Public Score: `0.77511`**

> ⚠️ **Note:** The `test.csv` file from Kaggle does not include actual Survived labels (as per Kaggle rules).  
> Therefore, model performance on the test set can only be evaluated by uploading the `submission_rf.csv` file to Kaggle.

---

## 📌 Author

- Nezihe Mohiuddin  


---

## 📬 Feedback

Feel free to fork the repo or open issues if you have suggestions, improvements, or want to collaborate.
