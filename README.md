# Machine Learning Basics

A collection of machine learning implementations and tutorials covering various algorithms and techniques.

## 📚 Overview

This repository contains educational notebooks demonstrating fundamental machine learning algorithms from scratch and using popular libraries like scikit-learn. The focus is on understanding the underlying concepts through practical implementation.

## 🗂️ Repository Structure

```
ML/
├── Classification/                    # Classification algorithms
├── Regression/                        # Regression algorithms
├── Logical Regression from scratch/   # Logistic Regression implementation
├── bernoulli-naive-bayes.ipynb       # Bernoulli Naive Bayes classifier
├── gaussian-naive-bayes.ipynb        # Gaussian Naive Bayes classifier
└── README.md
```

## 📓 Notebooks

### Naive Bayes Classifiers

#### 1. Bernoulli Naive Bayes (`bernoulli-naive-bayes.ipynb`)
- **Algorithm**: Bernoulli Naive Bayes
- **Dataset**: Iris (150 samples, 4 features, 3 classes)
- **Features**: Binary/boolean features
- **Purpose**: Demonstrates classification with binary features
- **Key Topics**:
  - Data exploration and visualization
  - Binary feature conversion
  - Model training and evaluation
  - Confusion matrix and classification metrics

#### 2. Gaussian Naive Bayes (`gaussian-naive-bayes.ipynb`)
- **Algorithm**: Gaussian Naive Bayes
- **Dataset**: Iris (150 samples, 4 features, 3 classes)
- **Features**: Continuous features
- **Purpose**: Demonstrates classification with continuous features
- **Key Topics**:
  - Gaussian distribution assumptions
  - Model parameter inspection (means, variances)
  - Probability predictions
  - Custom prediction functions

### Other Directories

- **Classification/**: Various classification algorithms and implementations
- **Regression/**: Regression techniques and models
- **Logical Regression from scratch/**: Step-by-step implementation of logistic regression

## 🛠️ Requirements

### Python Version
- Python 3.7 or higher

### Dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Required Libraries
- `pandas` - Data manipulation and analysis
- `numpy` - Numerical computing
- `matplotlib` - Data visualization
- `seaborn` - Statistical data visualization
- `scikit-learn` - Machine learning algorithms and tools

## 🚀 Getting Started

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ML.git
cd ML
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

Or install manually:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Running the Notebooks

You can run the notebooks using:
- **Jupyter Notebook**: `jupyter notebook`
- **JupyterLab**: `jupyter lab`
- **VS Code**: Open the `.ipynb` files directly

## 📖 Usage Examples

### Bernoulli Naive Bayes
```python
from sklearn.naive_bayes import BernoulliNB
from sklearn.feature_extraction.text import CountVectorizer

# For binary features
model = BernoulliNB()
model.fit(X_train, y_train)
predictions = model.predict(X_test)
```

### Gaussian Naive Bayes
```python
from sklearn.naive_bayes import GaussianNB

# For continuous features
model = GaussianNB()
model.fit(X_train, y_train)
predictions = model.predict(X_test)
```

## 📊 Key Concepts Covered

### Naive Bayes Algorithms
- **Bernoulli Naive Bayes**: For binary/boolean features
- **Gaussian Naive Bayes**: For continuous features following normal distribution
- **Multinomial Naive Bayes**: For count data (e.g., text classification)

### Machine Learning Fundamentals
- Data preprocessing and exploration
- Feature engineering
- Train-test splitting
- Model evaluation metrics
- Confusion matrices
- Classification reports

## 🎯 Learning Objectives

By exploring this repository, you will learn:
- How different Naive Bayes variants work
- When to use each variant based on your data
- Data visualization techniques
- Model evaluation and interpretation
- Best practices for machine learning workflows

## 🤝 Contributing

Contributions are welcome! If you'd like to contribute:
1. Fork the repository
2. Create a new branch for your feature
3. Make your changes
4. Submit a pull request

## 📝 License

This repository is for educational purposes. Please feel free to use and modify the code for your learning.

## 📧 Contact

For questions or suggestions, please open an issue in the repository.

## 🏷️ Version History

### v1.0.0 (Current)
- Initial release
- Added Bernoulli Naive Bayes classifier notebook
- Added Gaussian Naive Bayes classifier notebook
- Comprehensive documentation and examples

## 🔗 Resources

- [Scikit-learn Documentation](https://scikit-learn.org/)
- [Naive Bayes Classifier - Wikipedia](https://en.wikipedia.org/wiki/Naive_Bayes_classifier)
- [Iris Dataset](https://archive.ics.uci.edu/ml/datasets/iris)

---

**Happy Learning! 🎓**
