# Online-Food-Order-Prediction

## Introduction: 

###                           There has been a high demand for online food orders after the introduction of Swiggy and Zomato in the market. Food delivery companies use our buying habits to make the delivery process faster. The food order prediction system is one of the useful techniques these companies can use to make the entire delivery process fast. After implementing the complete online food delivery system, companies like Swiggy and Zomato will always try to improve them. The main objective of these companies toward their customers is to deliver the food at the right time. To deliver the food faster, these companies identify areas where the demand for online food orders is high and employ more delivery partners in those locations. It helps deliver food faster in areas with more orders.  
###                           These companies have so much data about their customers that they now know the food ordering habits of all customers. With this data, they can also predict whether or not a customer will order again from their app. It is a good technique for identifying areas, families and customer types with more business opportunities.
## So according to above problem statement, I have build the machine learning model which will predict the online food order from particular customers.

# Model:

### 1. Python Libraries used to build the model:
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Sklearn

### 2. First of all I have read the dataset using pandas library and dataset contains the information like:
- the age of the customer
- marital status of the customer
- occupation of the customer
- monthly income of the customer
- educational qualification of the customer
- family size of the customer
- latitude and longitude of the location of the customer
- pin code of the residence of the customer
- will the customer order again (Output)
- Feedback of the last order (Positive or Negative)

### 3. Exploratory Data Analysis

- The online food order decisions based on the Age of the Customer.
##### ![image](https://user-images.githubusercontent.com/104545490/172817504-d1fe0258-5817-400f-a07b-43c6a45c38e5.png)
###### Families with 2 and 3 members are ordering food often. These can be roommates, couples, or a family of three.

- Now, I have created a dataset of all the customers who ordered the food again:
#### ![image](https://user-images.githubusercontent.com/104545490/172819299-76e6f69f-11fe-433b-8d08-6cbd9bc9bb4c.png)

- I have looked up Gender column and analyzed who orders food more online
##### ![image](https://user-images.githubusercontent.com/104545490/172821391-6ff6903b-2a7b-4948-8c6f-24d350d38615.png)
##### According to the dataset, male customers are ordering more compared the females. 

- Now I have analyzed the marital status of the customers who ordered again:
##### ![image](https://user-images.githubusercontent.com/104545490/172821763-88757f29-4cc1-483f-8cb5-545487d71e68.png)
##### According to the above figure, 76.1% of the frequent customers are singles.

- I have analyzed what’s the income group of the customers who ordered the food again:
##### ![image](https://user-images.githubusercontent.com/104545490/172826946-de52f788-557f-47c7-a0e4-5fc6fab63e96.png)
##### According to the above figure, 54% of the customers don’t fall under any income group. They can be housewives or students.

### Dealing with categorical Features
#### The Categorical Features are :
- Gender
- Marital Status
- Occupation
- Educational Qualifications
- Monthly Income
- Feedback

#### Now I have prepared the data for the task of training a machine learning model. Here I have converted all the categorical features into numerical values:
##### ![image](https://user-images.githubusercontent.com/104545490/172827599-d5c89db4-e50b-40a7-903e-28fe8985a558.png)

## 4. Model Prediction:

### Now I have trained the machine learning model to predict whether a customer will order again or not. I have splitted the data into training and test sets:
#### I have used the 'Sklearn' library for training and testing the dataset.
#### Splitting the data for training and testing.
#### ![image](https://user-images.githubusercontent.com/104545490/172829187-c7400f60-f599-4338-87ef-ff7b8afc7ebb.png)

### Training of Machine Learning model
#### I have used the "RandomForestClassifier" for building the model
#### ![image](https://user-images.githubusercontent.com/104545490/172829801-b5054440-e6a1-43c4-859d-3d29f671a53d.png)
#### ![image](https://user-images.githubusercontent.com/104545490/172829857-32d5f385-8d88-4d0c-bd41-08e9b4f0539e.png)
#### Here from above model I got accuracy of 94.87 % that is our model predicts the output 94.87 % accurate. 

### Now I have prepared a form to input the data of the customer and predicted the customer will order the food again or not:
#### ![image](https://user-images.githubusercontent.com/104545490/172830775-64762eae-9f2d-4f7c-b3c0-a3e873e6fa6a.png)

### This is how I have trained a machine learning model to predict online food orders.

## Conclusion:
### So this is how I have predicted whether a customer will order food online again or not. The food order prediction system is one of the useful techniques food delivery companies can use to make the entire delivery process fast.


[Github](https://github.com/Shivmalge)

[Linkedin](https://www.linkedin.com/in/shivsharan-malage-99802a230/)






