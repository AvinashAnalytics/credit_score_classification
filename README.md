<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Credit Score Classification using Machine Learning</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            line-height: 1.6;
            background-color: #f4f7fc;
            color: #333;
        }
        h1, h2 {
            color: #4CAF50;
        }
        h3 {
            color: #333;
        }
        p {
            font-size: 16px;
        }
        ul {
            list-style-type: square;
            margin-left: 20px;
        }
        code {
            background-color: #f4f4f4;
            padding: 2px 6px;
            border-radius: 4px;
        }
        .container {
            max-width: 900px;
            margin: auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        .header {
            text-align: center;
            color: #4CAF50;
        }
        .important {
            font-weight: bold;
            color: #ff5722;
        }
        .table-container {
            overflow-x: auto;
            margin: 20px 0;
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        table, th, td {
            border: 1px solid #ddd;
        }
        th, td {
            padding: 8px;
            text-align: center;
        }
        th {
            background-color: #4CAF50;
            color: white;
        }
        footer {
            text-align: center;
            font-size: 14px;
            margin-top: 30px;
            color: #777;
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="header">
            <h1>Credit Score Classification using Machine Learning 📊</h1>
            <p><em>"In God we trust, all others bring data." – W. Edwards Deming</em></p>
        </div>

        <h2>📊 Project Overview</h2>
        <p>Welcome to the <strong>Credit Score Classification</strong> project! This repository contains a machine learning-based solution to predict and classify credit scores based on various financial attributes. By predicting the credit score category, we aim to help financial institutions reduce risk and optimize their lending strategies.</p>

        <h2>📋 Dataset Information</h2>
        <p>The dataset used in this project contains <strong>1 Lakh records</strong> with <strong>28 features</strong> related to personal and financial information of individuals. Key attributes include:</p>
        <ul>
            <li><strong>Customer Details:</strong> Age, occupation, annual income, etc.</li>
            <li><strong>Financial Behavior:</strong> Monthly salary, bank accounts, credit cards, loans.</li>
            <li><strong>Credit History:</strong> Credit utilization ratio, delayed payments, outstanding debt, etc.</li>
        </ul>
        <p>The <strong>target variable</strong> is the <em>Credit Score</em>, categorized into different brackets.</p>

        <h2>📂 Project Structure</h2>
        <p>The project is structured as follows:</p>
        <pre>
├── data/                    # Dataset folder
├── notebooks/                # Jupyter notebooks for exploration and analysis
├── src/                      # Source code for preprocessing and model training
│   ├── data_preprocessing.py
│   ├── model_training.py
│   └── model_evaluation.py
├── requirements.txt          # Project dependencies
├── LICENSE                   # License file
└── README.md                 # Project Readme file
        </pre>

        <h2>🔧 Installation</h2>
        <p>To run this project, follow these steps:</p>
        
        <h3>Prerequisites</h3>
        <ul>
            <li>Python 3.x</li>
            <li>Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn</li>
        </ul>

        <h3>Install Dependencies</h3>
        <pre>
git clone https://github.com/avinashanalytics/credit-score-classification.git
cd credit-score-classification
pip install -r requirements.txt
        </pre>

        <h2>💻 Usage</h2>
        <p>To use this project:</p>
        <ul>
            <li>Data preprocessing: <code>data_preprocessing.py</code> will clean the dataset.</li>
            <li>Train machine learning models: Run <code>model_training.py</code> to train the models.</li>
            <li>Interact via Jupyter Notebook: Open <code>notebooks/credit_score_classification.ipynb</code>.</li>
        </ul>

        <h2>🔍 Model Evaluation</h2>
        <p>Here’s a summary of model performances:</p>
        <div class="table-container">
            <table>
                <thead>
                    <tr>
                        <th>Model</th>
                        <th>Accuracy</th>
                        <th>Precision</th>
                        <th>Recall</th>
                        <th>F1-Score</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Logistic Regression</td>
                        <td>61.8%</td>
                        <td>0.63</td>
                        <td>0.59</td>
                        <td>0.61</td>
                    </tr>
                    <tr>
                        <td>Decision Tree</td>
                        <td>69.7%</td>
                        <td>0.72</td>
                        <td>0.68</td>
                        <td>0.70</td>
                    </tr>
                    <tr>
                        <td>Random Forest</td>
                        <td>79.7%</td>
                        <td>0.81</td>
                        <td>0.79</td>
                        <td>0.80</td>
                    </tr>
                </tbody>
            </table>
        </div>

        <h2>📝 Contributing</h2>
        <p>Feel free to contribute to the project by following these steps:</p>
        <ul>
            <li>Fork the repository.</li>
            <li>Create a new branch: <code>git checkout -b feature-branch</code></li>
            <li>Commit your changes: <code>git commit -am 'Add new feature'</code></li>
            <li>Push to the branch: <code>git push origin feature-branch</code></li>
            <li>Open a pull request.</li>
        </ul>

        <h2>📜 License</h2>
        <p>This project is licensed under the <a href="LICENSE">MIT License</a>.</p>

        <h2>📞 Contact</h2>
        <p>If you have any questions or suggestions, feel free to reach out:</p>
        <ul>
            <li><strong>Email:</strong> your_email@example.com</li>
            <li><strong>GitHub:</strong> <a href="https://github.com/avinashanalytics">@avinashanalytics</a></li>
        </ul>

        <footer>
            <p>Made with ❤️ by <a href="https://github.com/avinashanalytics">AvinashAnalytics</a></p>
        </footer>
    </div>

</body>
</html>
