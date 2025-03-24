<!DOCTYPE html>
<html lang="en">
<head>
   
</head>
<body>
    <h1>🏦 Loan Status Prediction</h1>
    <p>A Machine Learning model to predict loan approval based on applicant details.</p>
    <h2>📌 Project Overview</h2>
    <ul>
        <li>Predicts whether a loan will be approved or not.</li>
        <li>Uses Machine Learning to analyze applicant data.</li>
        <li>Provides instant results based on input features.</li>
    </ul>
    <h2>🚀 Technologies Used</h2>
    <ul>
        <li><b>Programming:</b> Python 🐍</li>
        <li><b>Libraries:</b> NumPy, Pandas, Scikit-Learn</li>
        <li><b>Framework:</b> Flask (For deployment)</li>
    </ul>
    <h2>📊 Model Workflow</h2>
    <ul>
        <li>Data Preprocessing: Cleaning and encoding applicant data.</li>
        <li>Feature Engineering: Selecting key attributes.</li>
        <li>Model Training: Using classifiers like Decision Tree, Random Forest, and Logistic Regression.</li>
        <li>Evaluation: Measuring accuracy using precision, recall, and F1-score.</li>
    </ul>
    <h2>🔧 How to Use</h2>
    <ol>
        <li>Clone the Repository:</li>
        <pre><code>git clone https://github.com/RishabhSharma0/Loan-Prediction.git</code></pre>
        <li>Navigate to the Project Directory:</li>
        <pre><code>cd Loan-Prediction</code></pre>
        <li>Install Dependencies:</li>
        <pre><code>pip install -r requirements.txt</code></pre>
        <li>Run the Prediction Script:</li>
        <pre><code>python main.py</code></pre>
        <li>Start the Web App:</li>
        <pre><code>python app.py</code></pre>
        <li>Enter Applicant Data and get the prediction instantly!</li>
    </ol>
    <h2>📸 Example Prediction Output</h2>
    <pre>
    <code>
input_data = (1,1,0,1,1,3000,0,66,360,1,2)
input_data_as_numpy_array = np.asarray(input_data)
input_data_reshape = input_data_as_numpy_array.reshape(1,-1)
prediction = classifier.predict(input_data_reshape)

if prediction[0] == 1:
    print('Loan Approved ✅')
else:
    print('Loan Not Approved ❌')
    </code>
    </pre>
    <h2>📬 Connect with Me</h2>
    <p>For any queries or suggestions, feel free to reach out.</p>
    <a class="btn" href="https://github.com/rishabh301" target="_blank">GitHub Profile</a>
</body>
</html>
