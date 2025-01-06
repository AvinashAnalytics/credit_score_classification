<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Credit Score Classification</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f7fc;
            margin: 0;
            padding: 20px;
            color: #333;
        }

        h1 {
            color: #4CAF50;
        }

        h2 {
            color: #333;
            margin-top: 30px;
        }

        h3 {
            color: #555;
        }

        p {
            font-size: 16px;
            line-height: 1.6;
        }

        ul {
            list-style-type: square;
            margin-left: 20px;
        }

        .content-container {
            max-width: 900px;
            margin: auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }

        code {
            background-color: #f4f4f4;
            padding: 2px 6px;
            border-radius: 4px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }

        th, td {
            padding: 12px;
            text-align: center;
            border: 1px solid #ddd;
        }

        th {
            background-color: #4CAF50;
            color: white;
        }

        footer {
            text-align: center;
            font-size: 14px;
            margin-top: 40px;
            color: #777;
        }

        .important {
            font-weight: bold;
            color: #e74c3c;
        }
    </style>
</head>

<body>

    <div class="content-container">
        <h1>Credit Score Classification using Machine Learning</h1>
        <p><em>"In God we trust, all others bring data." – W. Edwards Deming</em></p>

        <h2>📊 Project Overview</h2>
        <p>This project aims to build a machine learning model to predict and classify credit scores based on various financial features. By classifying customers based on their credit score brackets, this solution can help financial institutions optimize lending strategies and minimize risk.</p>

        <h2>📋 Dataset Information</h2>
        <p>The dataset contains <strong>1 Lakh records</strong> with <strong>28 features</strong> that include various customer details and their financial history. Key features include:</p>
        <ul>
            <li><strong>Customer Information:</strong> Age, Occupation, Annual Income</li>
            <li><strong>Credit Information:</strong> Number of Loans, Credit Cards, Outstanding Debt</li>
            <li><strong>Credit Utilization:</strong> Credit Score, Credit History, Payment Behavior</li>
        </ul>

        <h2>📂 Project Structure</h2>
        <p>The project is structured as follows:</p>
        <pre>
├── data/                         # Dataset folder
├── notebooks/                     # Jupyter notebooks for exploration
├── src/                           # Source code for preprocessing & model training
│   ├── data_preprocessing.py
│   ├── model_training.py
│   └── model_evaluation.py
├── requirements.txt               # Required dependencies
├── LICENSE                        # License file
└── README.md                      # Project Readme file
        </pre>

        <h2>🔧 Installation</h2>
        <p>Follow the steps below to get the project up and running:</p>

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
        <p>Once you've set up the environment, you can run the project by following these steps:</p>
        <ul>
            <li>Preprocess the data: <code>python src/data_preprocessing.py</code></li>
            <li>Train models: <code>python src/model_training.py</code></li>
            <li>Evaluate the models: <code>python src/model_evaluation.py</code></li>
            <li>Interactive work through Jupyter Notebook: Open <code>notebooks/credit_score_classification.ipynb</code></li>
        </ul>

        <h2>🔍 Model Evaluation</h2>
        <p>Below is a table summarizing the performance of different models:</p>

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

        <h2>📝 Contributing</h2>
        <p>If you wish to contribute to this project, feel free to fork the repository and create a pull request:</p>
        <ul>
            <li>Fork the repository.</li>
            <li>Create a new branch: <code>git checkout -b feature-branch</code></li>
            <li>Commit your changes: <code>git commit -am 'Add new feature'</code></li>
            <li>Push to your branch: <code>git push origin feature-branch</code></li>
            <li>Open a pull request to merge into the main branch.</li>
        </ul>

        <h2>📜 License</h2>
        <p>This project is licensed under the <a href="LICENSE">MIT License</a>.</p>

        <h2>📞 Contact</h2>
        <p>If you have any questions, feel free to contact me:</p>
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
