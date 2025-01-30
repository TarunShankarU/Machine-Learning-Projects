# **Advertisement Click Prediction**  

## 🎯 Objective  
The aim of this project is to predict whether a user will click on an advertisement based on multiple user attributes and dataset features. By analyzing these inputs, the goal is to develop a predictive model that accurately forecasts user engagement with advertisements.  

---

## 🧵 Dataset  
You can access the dataset used for this project here: [Kaggle Dataset](https://www.kaggle.com/jahnveenarang/cvdcvd-vd).  

---

## 🧾 Project Overview  
This project begins by performing **Exploratory Data Analysis (EDA)** and data visualizations to understand patterns in user behavior. Following the data analysis, we apply different machine learning algorithms to predict whether an advertisement will be clicked. Model performance metrics are compared to determine the most accurate algorithm.  

---

## 🧮 Steps Performed  
- Loaded essential libraries for data handling and machine learning tasks.  
- Conducted EDA to extract insights from the dataset.  
- Visualized key trends and meaningful patterns in user data.  
- Examined feature correlations to identify dependencies.  
- Mapped categorical features to numerical values for better model performance.  
- Split the dataset into training and testing sets and applied feature scaling.  
- Built and trained four machine learning models: XGBoost, Random Forest, Gradient Boosting, and Multi-Layer Perceptron (MLP).  
- Evaluated models using confusion matrices and compared accuracy scores to select the top performer.  

---

## 🚀 Models Implemented  
Here are the models tested and their roles in this project:  
- **XGBoost Classifier:** Exceptional at handling complex patterns and delivering top performance on large datasets.  
- **Random Forest Classifier:** Effective in minimizing overfitting and offering feature importance insights.  
- **Gradient Boosting:** Useful for capturing complex relationships in data through iterative boosting.  
- **Multi-Layer Perceptron (MLP):** Deep learning architecture capable of learning non-linear relationships.  

---

## 📚 Technology Stack  
- **Programming Language:** Python  
- **Libraries:** Pandas, Numpy, Seaborn, Matplotlib  

    
### 📊 **Exploratory Data Analysis Results**
<table>
    <tr>
        <td><img src="https://github.com/snega16/ML-Crate/blob/snega16/Advertisement%20Click%20Prediction/Images/gender.png"></td>
        <td><img src="https://github.com/snega16/ML-Crate/blob/snega16/Advertisement%20Click%20Prediction/Images/purchased.png"></td>
    </tr>
    <tr>
        <td><img src="https://github.com/snega16/ML-Crate/blob/snega16/Advertisement%20Click%20Prediction/Images/age-purchased.png"></td>
        <td><img src="https://github.com/snega16/ML-Crate/blob/snega16/Advertisement%20Click%20Prediction/Images/salary-purchased.png"></td>
    </tr>
    <tr>
        <td><img src="https://github.com/snega16/ML-Crate/blob/snega16/Advertisement%20Click%20Prediction/Images/box-purchased-salary.png"></td>
        <td><img src="https://github.com/snega16/ML-Crate/blob/snega16/Advertisement%20Click%20Prediction/Images/box-purchased-age.png"></td>
    </tr>
    <tr>
        <td><img src="https://github.com/snega16/ML-Crate/blob/snega16/Advertisement%20Click%20Prediction/Images/purchased-gender.png"></td>
        <td><img width=70% src='https://github.com/snega16/ML-Crate/blob/snega16/Advertisement%20Click%20Prediction/Images/correlation.png'></td>
    </tr>
</table>

### 📈 **Performance of the Models based on the Accuracy Scores**
<table>
    <tr>
        <td style="padding-right: 20px; vertical-align: top;">
            <ul style="list-style-type: disc; margin: 0;">
                <li>XGBoost Classifier - 92%</li>
                <li>RandomForest - 90%</li>
                <li>Gradient Boosting - 90%</li>
                <li>Multi-Layer Perceptron - 87%</li>
            </ul>
        </td>
        <td style="vertical-align: top;">
            <img src="https://github.com/snega16/ML-Crate/blob/snega16/Advertisement%20Click%20Prediction/Images/accuracy.png" alt="Description of image" style="max-width: 200px; max-height: 200px;">
        </td>
    </tr>
</table>


### 📢 **Conclusion**
Among all the models tested, the **XGBoost Classifier** achieved the highest accuracy, approximately **92%**, making it the best-performing model for predicting advertisement clicks. This demonstrates its effectiveness in handling the dataset and providing reliable predictions.


Created by [Tarun Shankar U](https://github.com/TarunShankarU). 
