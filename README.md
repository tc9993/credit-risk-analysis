<h1>Credit Risk Analysis</h1>

<h2>Overview of Loan Prediction Analysis</h2>

<h3>Purpose</h3>
<p>
  The purpose of this analysis was to provide insights on which, if any, of the various offerings from the imbalanced-learn and scikit-learn libraries provided a reliable model for evaluating credit risk.  The 6 different models are listed below:<br>
  <ul>
    <li>RandomOverSampler</li>
    <li>SMOTE</li>
    <li>ClusterCentroids</li>
    <li>SMOTEENN</li>
    <li>BalancedRandomForestClassifier</li>
    <li>EasyEnsembleClassifier</li>
    </ul>
</p>

<h2>Results</h2>

<h3>RandomOverSampler</h3>
<p align='center'>
  <img src='https://github.com/tc9993/credit-risk-analysis/blob/main/Resources/RandomOverSampler.PNG?raw=true' alt='RandomOverSampler Results Output' width=75% height=75%><br>
  <b>Figure 1.1:</b> RandomOverSampler Results Output
</p>
<ul>
  <li><b>Balanced Accuracy Score:</b> 64.7%</li>
  <li><b>High-Risk Precision:</b> 1%</li>
  <li><b>Low-Risk Precision:</b> 100%</li>
  <li><b>High-Risk Recall Score:</b> 69%</li>
  <li><b>Low-Risk Recall Score:</b> 60%</li>
</ul>

<h3>SMOTE</h3>
<p align='center'>
  <img src='https://github.com/tc9993/credit-risk-analysis/blob/main/Resources/SMOTE.PNG?raw=true' alt='SMOTE Results Output' width=75% height=75%><br>
  <b>Figure 1.2:</b> SMOTE Results Output
</p>
<ul>
  <li><b>Balanced Accuracy Score:</b> 66.2%</li>
  <li><b>High-Risk Precision:</b> 1%</li>
  <li><b>Low-Risk Precision:</b> 100%</li>
  <li><b>High-Risk Recall Score:</b> 63%</li>
  <li><b>Low-Risk Recall Score:</b> 69%</li>
</ul>

<h3>ClusterCentroids</h3>
<p align='center'>
  <img src='https://github.com/tc9993/credit-risk-analysis/blob/main/Resources/ClusterCentroids.PNG?raw=true' alt='ClusterCentroids Results Output' width=75% height=75%><br>
  <b>Figure 1.3:</b> ClusterCentroidsResults Output
</p>
<ul>
  <li><b>Balanced Accuracy Score:</b> 54.5%</li>
  <li><b>High-Risk Precision:</b> 1%</li>
  <li><b>Low-Risk Precision:</b> 100%</li>
  <li><b>High-Risk Recall Score:</b> 69%</li>
  <li><b>Low-Risk Recall Score:</b> 40%</li>
</ul>

<h3>SMOTEENN</h3>
<p align='center'>
  <img src='https://github.com/tc9993/credit-risk-analysis/blob/main/Resources/SMOTEENN.PNG?raw=true' alt='SMOTEENN Results Output' width=75% height=75%><br>
  <b>Figure 1.4:</b> SMOTEENN Results Output
</p>
<ul>
  <li><b>Balanced Accuracy Score:</b> 64.6%</li>
  <li><b>High-Risk Precision:</b> 1%</li>
  <li><b>Low-Risk Precision:</b> 100%</li>
  <li><b>High-Risk Recall Score:</b> 71%</li>
  <li><b>Low-Risk Recall Score:</b> 58%</li>
</ul>

<h3>BalancedRandomForestClassifier</h3>
<p align='center'>
  <img src='https://github.com/tc9993/credit-risk-analysis/blob/main/Resources/BalancedRandomForestClassifier.PNG?raw=true' alt='BalancedRandomForestClassifier Results Output' width=75% height=75%><br>
  <b>Figure 1.5:</b> BalancedRandomForestClassifier Results Output
</p>
<ul>
  <li><b>Balanced Accuracy Score:</b> 78.9%</li>
  <li><b>High-Risk Precision:</b> 3%</li>
  <li><b>Low-Risk Precision:</b> 100%</li>
  <li><b>High-Risk Recall Score:</b> 70%</li>
  <li><b>Low-Risk Recall Score:</b> 87%</li>
</ul>

<h3>EasyEnsembleClassifier</h3>
<p align='center'>
  <img src='https://github.com/tc9993/credit-risk-analysis/blob/main/Resources/EasyEnsembleClassifier.PNG?raw=true' alt='EasyEnsembleClassifier Results Output' width=75% height=75%><br>
  <b>Figure 1.6:</b> EasyEnsembleClassifier Results Output
</p>
<ul>
  <li><b>Balanced Accuracy Score:</b> 93.1%</li>
  <li><b>High-Risk Precision:</b> 9%</li>
  <li><b>Low-Risk Precision:</b> 100%</li>
  <li><b>High-Risk Recall Score:</b> 92%</li>
  <li><b>Low-Risk Recall Score:</b> 94%</li>
</ul>

<h2>Summary</h2>

<h3>Summary of Results</h3>
<p>
After reviewing the data, below is a summary of the top 3 <i>balanced accuracy scores</i>:
<ol>
  <li>EasyEnsembleClassifier: 93.1%</li>
  <li>BalancedRandomForestClassifier: 78.9%</li>
  <li>SMOTE: 66.2%</li>
</ol>
Below is a summary of the top 3 <i>high-risk recall rates</i>:
<ol>
  <li>EasyEnsembleClassifier: 92%</li>
  <li>SMOTEENN: 71%</li>
  <li>BalancedRandomForestClassifier: 70%</li>
</ol>
Finally, below is a summary of the top 3 <i>low-risk recall rates</i>:
<ol>
  <li>EasyEnsembleClassifier: 94%</li>
  <li>BalancedRandomForestClassifier: 87%</li>
  <li>SMOTE: 69%</li>
</ol>
</p>

<h3>Recommendation</h3>
<p>
Given the imbalanced nature of high- and low-risk loans, whereby there are far fewer high-risk in the population, it is important to ensure that high-risk loans are accurately identified as such.  The high-risk recall rate is the statistic to best assist in identifying a model to use, and the EasyEnsembleClassifier model showed that it most accurately identifies high-risk loans as such, 92% of the time.
</p>
<p>
While it is acceptable for some low-risk loans to be marked as high-risk, which can then be sorted out via a further investigation, it is ideal to correctly label high- and low-risk loans appropriately via the machine learning model.  The low-risk recall rate will tell us how often a low-risk loan was identified as such.  Once again, the EasyEnsembleClassifier model proved to be best in this category with a 94% low-risk recall rate.
</p>
<p>
Overall, the EasyEnsembleClassifier would be my recommendation to identify high- and low- risk loans as it most accurately predicted the loan risk.  To round out the analysis, EasyEnsembleClassifier also finished at the top of the accuracy score with a 93.1% score.  While this is not always the best indicator of performance, given the EasyEnsembleClassifier's performance in low-risk recall and high-risk recall, it is the most accurate of the 6 tested.
</p>
