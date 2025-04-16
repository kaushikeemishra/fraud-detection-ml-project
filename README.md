
# 💳 Credit Card Fraud Detection using Machine Learning


An end-to-end Machine Learning project that detects fraudulent credit card transactions using key anonymized features. It includes model training, evaluation (AUC, ROC, confusion matrix), and deployment with an interactive widget interface in Jupyter Notebook.



Special thanks to:
- [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud) for providing the dataset
- Scikit-learn for seamless model training and evaluation
- Jupyter and ipywidgets for interactive development


No external API used. All functionality is built with:
- `scikit-learn` for ML model
- `ipywidgets` for GUI prediction
📎 Additional Resources:
- [Model Evaluation Concepts](https://scikit-learn.org/stable/modules/model_evaluation.html)
- [Logistic Regression Theory](https://en.wikipedia.org/wiki/Logistic_regression)
👩‍💻 **Kaushikee Mishra**  
BTech Student | AI/ML Enthusiast  
Email: [kaushikeemishra1@gmail.com]  
GitHub: [github.com/kaushikeemishra](https://github.com/kaushikeemishra)
![Python](https://img.shields.io/badge/Python-3.10-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

Contributions are welcome!  
Please fork the repo, make changes, and open a pull request.

Steps:
1. Fork this repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request
🔗 Demo Preview:
- Jupyter Notebook-based interactive fraud prediction system
- Predict with 4 features (`Amount`, `V14`, `V10`, `V12`) using `ipywidgets`
💻 Deployed Locally via Jupyter Notebook.  
To deploy:
1. Run all notebooks in sequence.
2. Launch `4_Model_Deployment.ipynb` for user input and prediction.
📚 Available as inline documentation in each notebook.  
- Each section is well-commented for understanding.
**Q:** What if model doesn't load?  
**A:** Make sure `fraud_detection_model.pkl` and `scaler.pkl` exist in the same directory.

**Q:** Why only 4 features?  
**A:** We selected top-performing anonymized features (`V14`, `V10`, `V12`, `Amount`) to keep the model lightweight and interpretable.
✅ Logistic Regression-based fraud detection  
✅ Feature Scaling with StandardScaler  
✅ ROC, AUC, Confusion Matrix, Accuracy  
✅ User-friendly input system with ipywidgets  
✅ Clean and modular notebook organization



Got feedback or suggestions? Feel free to open an issue or email me directly at [kaushikeemishra1@gmail.com].


👋 Hi! I'm Kaushikee Mishra, a BTech student focused on AI/ML and Data Science.  
This project is a part of my growing ML portfolio.

🚀 Passionate about AI/ML & building real-world intelligent systems.  
Focused on impactful machine learning projects.

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)]()
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kaushikee-mishra-3ba82b251)



## Other Common Github Profile Sections
👩‍💻 I'm currently working on machine learning

🧠 I'm currently learning ml projects

📁 Check my other ML projects on GitHub for more hands-on implementations!



## 🛠 Skills
🧠 Python, Scikit-learn, Pandas, NumPy  
📊 Data Visualization (Matplotlib, Seaborn)  
🧪 Model Evaluation  
📦 Model Deployment (joblib, ipywidgets)

## Installation

Install my-project with npm
```bash
    1. Clone the repository  
```
```bash
   2. git clone https://github.com/kaushikeemishra/credit-card-fraud-detection.git
```
    Open Jupyter Notebook
```

    Run notebooks in sequence
```


## Lessons Learned


---

### ✅ Lessons
```md
📘 Learned how to:
- Select best-performing features
- Train and tune a Logistic Regression model
- Visualize ROC curve and confusion matrix
- Deploy an interactive user input system


```

This project is licensed under the MIT License.


## Optimizations

What optimizations did you make in your code? E.g. refactors, performance improvements, accessibility


## Related

Here are some related projects

- [Anomaly Detection Projects](https://github.com/topics/anomaly-detection)
- [Fraud Detection Research Papers](https://arxiv.org/search/?query=fraud+detection)



## Roadmap

✔️ Train model on selected features  
✔️ Evaluate model performance  
✔️ Deploy interactive widget  
🔜 Add Flask-based web app interface (future)


## Run Locally

Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```


jupyter notebook

## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

### 🖼️ ROC Curve
![ROC Curve](assets/graphs/roc_curve.png)

### 🎯 Confusion Matrix
![Confusion Matrix](assets/graphs/confusion_matrix.png)

### 🖥️ Interactive Prediction Widget
![Widget Screenshot](assets/ui_screenshot.png)

## Tech Stack

- Python 🐍
- Jupyter Notebook
- scikit-learn
- Pandas & NumPy
- ipywidgets


## Running Tests

To run tests,
Test model with:
- Cross-validation
- Manual inputs via ipywidgets
- Comparison of prediction vs actual

## Usage/Examples

Open `Model_Deployment.ipynb` and enter values in the widget:
- Amount: 100.50
- V14: -2.54
- V10: -3.12
- V12: -1.56

Click "Predict" — Output: Fraud or Not Fraud

## ❤️ Support

Give this project a ⭐️ if you found it useful!
