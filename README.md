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
  
</p>

<h3>Recommendation</h3>
<p>
  
</p>
