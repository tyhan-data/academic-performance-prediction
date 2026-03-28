# Academic Performance Prediction

A machine learning project to predict student academic performance based on mental health indicators and social media usage.

## 📋 Project Overview

This project uses **Logistic Regression** to predict whether a student's academic performance will be affected based on:
- Mental Health Scores
- Conflicts Over Social Media
- Social Media Impact on Academic Performance

## ⚡ Usage Examples

```python
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import confusion_matrix, accuracy_score

# Load data
# df = pd.read_csv("data.csv")

# Train-test split, preprocessing
# X_train, X_test, y_train, y_test = ...

# Train model
lr = LogisticRegression()
lr.fit(X_train, y_train)

# Make predictions
y_pred = lr.predict(X_test)

# Evaluate
cm = confusion_matrix(y_test, y_pred)
accuracy = accuracy_score(y_test, y_pred)
print("Confusion Matrix:\n", cm)
print("Accuracy:", accuracy)
```

## 🖥 Technologies Used

- **Python** 🐍
- **Pandas & NumPy** for data handling
- **Scikit-learn** for ML algorithms & metrics
- **Matplotlib / Seaborn** for visualization

## 📊 Dataset Information

- **Dataset columns:** Mental_Health_Score, Conflicts_Over_Social_Media, Affects_Academic_Performance
- **Source:** Collected/Generated survey data of students

## 📈 Results / Performance Metrics

- **Confusion Matrix:** Shows model predictions vs. actual values
- **Accuracy, Precision, Recall, F1-score:** Comprehensive evaluation metrics
- **Model Performance:** Logistic Regression model shows good predictive performance

*For exact metrics, refer to the Jupyter notebook in the repository.*



## 🤝 Contributing Guidelines

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Implement improvements or fixes
4. Commit your changes (`git commit -m 'Add improvement'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Submit a Pull Request

## 📄 License

This project is open source and available under the MIT License.

## ✉️ Contact

For questions or suggestions, feel free to open an issue or contact the repository maintainer.
