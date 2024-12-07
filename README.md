# Prediction-of-Wine-Quality-using-Machine-Learning
This repository contains all the files for our course project "Predicting Wine Quality using Machine Learning". Feel free to explore and help us with your constructive feedbacks.
### Dataset
<ul>
  <li><b>Source: </b><a href="https://github.com/nikunj-indoriya/Prediction-of-Wine-Quality-using-Machine-Learning">Wine Quality Dataset</a></li>
  <li><b>Details: </b>This dataset contains physicochemical (input) and quality (output) variables for different wines.
  <ul>
    <li><b>Features: </b>11 input features which is <code>fixed acidity</code>,<code>volatile acidity</code>,<code>citric acid</code>,<code>residual sugar</code>,<code>chlorides</code>,<code>free sulfur dioxide</code>,<code>total sulfur dioxide</code>,<code>density</code>,<code>pH</code>,<code>sulphates</code>,<code>alcohol</code></li>
    <li><b>Target: </b><code>quality</code>(ranges between 3 to 8)</li>
  </ul>
  </li>
</ul>

### Objectives
<ul>
  <li>Preprocess the dataset for missing values, outliers, and normalization.</li>
  <li>Visualizing data to gain better insights into its patterns and distribution.</li>
  <li>Build and evaluate machine learning models to predict wine quality.</li>
  <li>Perform feature importance analysis to understand key predictors of quality.</li>
</ul>

### Machine Learning Models
<ul>
  <li>Logistic Regression</li>
  <li>Decision Tree</li>
  <li>K-Nearest Neighbour</li>
  <li>Naive Bayes</li>
  <li>Random Forest</li>
  <li>Linear Regression</li>
</ul>

### Project Structure
```bash 
Prediction-of-Wine-Quality-using-Machine-Learning/  
│  
├── data/  
│   ├── X_train.csv        # Training features  
│   ├── y_train.csv        # Training labels  
│   ├── X_test.csv         # Test features  
│  
├── Prediction_(1).ipynb   # Jupyter Notebook with full code: data upload to model results  
├── DSP_Project_Report.pdf # Comprehensive project report  
├── README.md              
```
### How to use
<ol>
  <li>Clone the Repository:</li>
  <pre><code>git clone https://github.com/nikunj-indoriya/Prediction-of-Wine-Quality-using-Machine-Learning.git
cd Prediction-of-Wine-Quality-using-Machine-Learning
  </code></pre>
  <li>Open <code>Prediction_(1).ipynb</code> in Jupyter Notebook to explore and execute the full workflow.</li>
</ol>

### Results
<ul>
  <li>Achieved <b>accuracy of 79.30%</b> using the Random Forest.</li>
  <li>Other metrics are <b>Precision: </b>80.08%, <b>recall: </b>78.21% and the confusion matrix shows <b>205 true negatives</b> and <b>201 true positives</b> with an <b>RMSE</b> of <b>0.46</b>.</li>
</ul>

### Contributing
Feel free to submit pull requests or raise issues for improvements. Contributions are welcome!
