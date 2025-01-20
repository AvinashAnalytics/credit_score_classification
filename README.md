
# <blink>**Credit Score Classification**</blink>

## **📊 Project Overview**
This project aims to build a machine learning model to predict and classify credit scores based on various financial features. By classifying customers based on their credit score brackets, this solution can help financial institutions optimize lending strategies and minimize risk.

## **📋 Dataset Information**
The dataset contains **1 Lakh records** with **28 features** related to customer details and their financial history. Key features include:

- **Customer Information:** Age, Occupation, Annual Income
- **Credit Information:** Number of Loans, Credit Cards, Outstanding Debt
- **Credit Utilization:** Credit Score, Credit History, Payment Behavior

## **📂 Project Structure**
The project is structured as follows:

```plaintext
├── data/                         # Dataset folder
├── notebooks/                     # Jupyter notebooks for exploratory data analysis
├── reports/                       # Folder containing project reports and findings
│   └── credit_score_classification_report_by_Avinash.pdf  # Full project report
├── src/                           # Source code for preprocessing & model training
│   ├── data_preprocessing.py      # Data preprocessing script
│   ├── model_training.py          # Model training script
│   └── model_evaluation.py       # Model evaluation script
├── requirements.txt               # Required dependencies
├── LICENSE                        # License file
└── README.md                      # Project Readme file
```

## 📑 Reports Folder
The reports/ directory contains a detailed PDF report, summarizing the methods, results, and insights derived from the project. It includes an in-depth analysis of model performance, feature engineering steps, and key findings. You can access the report here:

## [REPORTS](https://github.com/AvinashAnalytics/credit_score_classification/blob/main/reports/credit_card_classification_report_by_Avinash.pdf)


## **🔧 Installation**
### **Prerequisites**
To run the project, you will need:
- Python 3.x
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

### **Install Dependencies**
Clone the repository and install dependencies:

```bash
git clone https://github.com/avinashanalytics/credit-score-classification.git
cd credit-score-classification
pip install -r requirements.txt
```

## **💻 Usage**
Once you've set up the environment, you can run the project by following these steps:

1. Preprocess the data:  
   `python src/data_preprocessing.py`
2. Train models:  
   `python src/model_training.py`
3. Evaluate the models:  
   `python src/model_evaluation.py`
4. Interactive work through Jupyter Notebook:  
   Open `notebooks/credit_score_classification.ipynb`

## **🔍 Model Evaluation**
Here’s a summary of the performance of different models:

| Model              | Accuracy | Precision | Recall | F1-Score |
|--------------------|----------|-----------|--------|----------|
| Logistic Regression| 61.8%    | 0.63      | 0.59   | 0.61     |
| Decision Tree      | 69.7%    | 0.72      | 0.68   | 0.70     |
| Random Forest      | 79.7%    | 0.81      | 0.79   | 0.80     |

## **📝 Contributing**
If you wish to contribute to this project:
1. Fork the repository.
2. Create a new branch:  
   `git checkout -b feature-branch`
3. Commit your changes:  
   `git commit -am 'Add new feature'`
4. Push to your branch:  
   `git push origin feature-branch`
5. Create a pull request to merge into the main branch.

## **📜 License**
This project is licensed under the [MIT License](LICENSE).

## **📞 Contact**
If you have any questions, feel free to contact me:
- **Email**: masteravinashrai@gmail.com
- **GitHub**: [@avinashanalytics](https://github.com/avinashanalytics)

---

Made with ❤️ by [AvinashAnalytics](https://github.com/avinashanalytics)
```
