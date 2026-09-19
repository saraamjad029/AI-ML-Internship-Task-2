<h1> AI/ML Internship - Machine Learning Model Comparison (Task 02) </h1>

<p>This repository contains the implementation and evaluation report for Task 02 of the AI/ML Internship at Devixo Solutions.</p>

<h2>Student Details</h2>
<p>Student Name: Sara Amjad Abbasi<br>
Internship Domain: AI/ML Internship<br>
Task Number: Task 02</p>

<h2>Objective and Problem Statement</h2>
<p>Objective: Develop multiple machine learning models for a real-world prediction problem, evaluate their performance using appropriate metrics, and learn the importance of model comparison and selection.</p>
<p>Problem Statement: This task addresses the challenge of accurately predicting student academic outcomes (such as passing or failing) using machine learning classification algorithms. By implementing and comparing multiple models—specifically Logistic Regression, Decision Tree, and Random Forest—the objective is to evaluate how effectively different algorithms handle feature patterns, determine which model provides the highest predictive accuracy and reliability, and understand the trade-offs between training time and performance for educational data analytics.</p>

<h2>Technologies Used</h2>
<p>Python<br>
Pandas<br>
Scikit-learn<br>
Matplotlib and Seaborn</p>

<h2>Implementation Steps</h2>
<p>1. Data Preprocessing: Generated a classification dataset, applied standard scaling (StandardScaler), and split the data into 80% training and 20% testing sets.<br>
2. Model Development: Trained three machine learning algorithms: Logistic Regression, Decision Tree Classifier, and Random Forest Classifier.<br>
3. Model Evaluation: Evaluated each model using Accuracy, Precision, Recall, and F1 Score.</p>

<h2>Model Comparison Results</h2>
<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>Model Name</th>
      <th>Training Time (s)</th>
      <th>Accuracy</th>
      <th>Precision</th>
      <th>Recall</th>
      <th>F1 Score</th>
      <th>Advantages</th>
      <th>Limitations</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Logistic Regression</td>
      <td>0.02</td>
      <td>0.773</td>
      <td>0.7737</td>
      <td>0.773</td>
      <td>0.7726</td>
      <td>Fast training, simple</td>
      <td>Lower accuracy on complex patterns</td>
    </tr>
    <tr>
      <td>Decision Tree</td>
      <td>0.10</td>
      <td>0.891</td>
      <td>0.8911</td>
      <td>0.891</td>
      <td>0.8910</td>
      <td>Easy to interpret</td>
      <td>Prone to overfitting</td>
    </tr>
    <tr>
      <td>Random Forest</td>
      <td>0.88</td>
      <td>0.958</td>
      <td>0.9583</td>
      <td>0.958</td>
      <td>0.9580</td>
      <td>Highest accuracy and stability</td>
      <td>Slightly slower training time</td>
    </tr>
  </tbody>
</table>

<h2>Conclusion</h2>
<p>Recommended Model: Random Forest Classifier</p>
<p>Why it performed better: Random Forest achieved the highest overall accuracy (0.958) and F1 Score (0.9580) because it uses an ensemble of multiple decision trees, reducing overfitting and capturing complex patterns much better than individual models.</p>

<h2>Source Code File</h2>
<p>Task-2-Source-Code.ipynb: Contains the complete, self-contained Python code used for data generation, preprocessing, model training, and performance evaluation.</p>
