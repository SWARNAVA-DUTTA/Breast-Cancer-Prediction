# Breast Cancer Prediction

According to the survey of in 2014, there are 232,670 females and 2,360 males having this type of new cases regarding the breast cancer. Among them 40,000 females and 430 males was death during the period this survey .These are the signs and symptoms for the early detection of the breast cancer. Machine Learning is a powerful tool and technique to handling this task. In data mining breast cancer research has been one of the important research topics in medical science during the recent years The classification of Breast Cancer data can be useful to predict the result of some diseases or discover the genetic behavior of tumors. There are many techniques to predict and classification breast cancer pattern. This paper empirically compares performance of different classification rules that are suitable for direct interpretability of their results.

 Even though it is evident that the use of ML methods can improve our understanding of cancer progression, an appropriate level of validation is needed in order for these methods to be considered in the everyday clinical practice. In this work, we present a review of recent ML approaches employed in the modeling of cancer progression.

We present a review of recent ML approaches employed in the modeling of cancer progression. Breast Cancer becomes dangerous disease in today’s era. The most common type of this type of breast cancer is ductal carcinoma, which begins in the lining of the milk ducts. It is nothing but only thin tubes that carry milk from the lobules of the breast to the little nipple. Another type of breast cancer is lobular carcinoma, which begins in the lobules of the breast. Invasive breast cancer is breast cancer that has spread from where it began in the breast ducts or lobules to surrounding normal tissue. Breast cancer occurs in both men and women, although male breast cancer is rare.

<br/>

<h3>OBJECTIVE</h3>

The objective of our project is to predict the occurrence of breast cancer with utmost accuracy possible using different classification techniques, feature selection methods, feature importance, hypothesis and heuristic test like chi squared test and genetic algorithm.

   The dataset we are using is UCI dataset which includes different physical features that is required to determine whether the person has a probability of breast cancer and how much accurate the result is (whether it is benign or malignant).
   
 <br/>
 
 <h3>Algorithms Used</h3>
 
      • Support Vector Machine (SVM)
      • Naïve Bayes
      • Logistic Regression
      • K Nearest Neighbor
      • Decision Tree
      • Random Forest Classifier
      
    For Feature Selection
      • Chi-squared Test
      • Genetic Algorithm

<h3>Implementation</h3>

<div float=left>
  <img src="https://user-images.githubusercontent.com/46235752/156233699-7aa7e1d8-904a-4d40-94a3-f996c417b5bd.png" width="400" height="200">
  <img src="https://user-images.githubusercontent.com/46235752/156233721-60321870-ed07-42c1-99d6-2ea534306923.png" width="400" height="200">
</div>

<br/><br/><br/>

<h2 align:centre>Results</h2>

<table>
  <tr>
    <th>With Normalisation</th>
    <th>Without Normalisation</th>
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/46235752/156234449-b758ffba-2005-4114-90aa-5883a9a13539.png" width="600" height="200"></td>
    <td><img src="https://user-images.githubusercontent.com/46235752/156234630-35efed18-0467-4d89-bbf7-5c3e1c391797.png" width="600" height="200"></td>
  </tr>
</table>


<h3>Features Used</h3>

<img src="https://user-images.githubusercontent.com/46235752/156235986-7bcb584d-59a7-464c-abf1-6d67bd1b65b6.png" width="600" height="700">


Final 15 features are selected after selecting common features for chi squared test. <br/>
The 15 features that are taken into account for their best score are: 

<img src="https://user-images.githubusercontent.com/46235752/156236461-748d55ca-5abc-42bc-80b3-159de02c035f.png" width="600" height="300">

<h3>After applying Chi Square Test</h3>

<img src="https://user-images.githubusercontent.com/46235752/156236690-41c010b8-411f-4484-90be-04375d4fde9d.png" width="600" height="200">


After selecting the best 9 features from the attributes table, Genetic Algorithm is used to get the accuracy.<br/>
The best 9 features are: 

<img src="https://user-images.githubusercontent.com/46235752/156237118-58ade3af-26ba-4eae-b5d8-c09e144578f9.png" width="600" height="300">

<h3>After applying Genetic Algorithm</h3>

<img src="https://user-images.githubusercontent.com/46235752/156237628-40bab0d1-d799-4214-8366-d8ac688798f6.png" width="600" height="200">

<h2>CONCLUSION</h2>

Our study reveals that--<br/>
• Support Vector Machine Classifier gives the maximum accuracy of 96.49%.<br/>
• Logistic Regression gives the lowest accuracy of 45.61% without using feature selection.<br/>
• After using CHI SQUARED TEST we get accuracy of 98.24% and 36.84% respectively.<br/>
• After using GENETIC ALGORITHM we get accuracy of 97.37% and 42.11% respectively. <br/>

This work can further be enhanced by identification of breast cancer, can be done in near future.


