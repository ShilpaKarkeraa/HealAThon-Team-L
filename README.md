"# HealAThon-Team-L" 

# Diabetics prediction using logistic regression

Our idea is the prediction if the person has diabetics or not using logistic regression machine learning algorithm. We use Python programming language and several libraries, including pandas, numpy, matplotlib, seaborn, and scikit-learn. Dataset has 768 entries.


# Pairwise correlation matrix
we have used 8 features as shown in below matrix:
![image](https://user-images.githubusercontent.com/88760865/223826582-e6347f8a-90c2-4236-8285-22c66fac490a.png)

# Data Processing
We have divided the dataset(768 entries) into 90:10 training and testing respectively, and based on our attempts we found that random_state with value 16 presenting the maximum accuracy:

![image](https://user-images.githubusercontent.com/88760865/223831283-6da38baa-d076-4c1c-9379-eb464561f9de.png)
Accuracy :  0.8831168831168831

# Feature Importance
We have used coefficient function reg.coef_ in logistic regression to find the best parameters, and below is the result:

![image](https://user-images.githubusercontent.com/88760865/224021760-50a97011-461c-42ab-b2fa-50d08389ef42.png)

![image](https://user-images.githubusercontent.com/88760865/224022049-942038ec-64b2-4613-b752-b86b47764aad.png)

# The result after selecting the important features:


![image](https://user-images.githubusercontent.com/88760865/224022322-4e8f2653-d486-447f-a3c7-e8d201ad55b1.png)


Accuracy after using the importance features:  0.8961038961038961

# Conclusion
As we saw in above anaylyst, we were able to predict whether the person is having diabetics or not based on some parameters like (Pregnancies, Glucose, BloodPressure, BMI, DiabetesPedigreeFunction and Age) with accuracy around 90%.

# Usage
Clone the repo and run the HealAThon-Team-L.ipynb file using Python Jupyter Notebook along with dataset



