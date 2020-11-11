# GRIP
The project files within this repository contain the jupyter notebooks done as part of my Graduate Rotational Internship Program (GRIP) for the month of November 2020 at the Sparks Foundation. All the datasets were provided by them for internship purposes.

## PROJECT 1 

* **Project level**:  Beginner

* **Data used**:      Student Marks

* **Ml model used**:  Simple Linear Regression

* **Aim**:            To establish the relationship between the variables and formulate a model to predict the student scores using hours of study/day.


The first project is to predict the marks of students using a supervised machine learning model. The data provided to us is an **open source data** of student scores, where we have two variables as given below in the description. 

### <center>Data Description</center>

<table>
    <tr>
        <td><b><center>Variable</center></b></td>
        <td><b><center>Definition</center></b></td>
    </tr>
    <tr>
        <td><center>Hours</center></td>
        <td>Number of hours the student studies (Independent variable - X)<td>
    </tr>
    <tr>
        <td><center>Scores</center></td>
        <td>The percentage of the student (Target variable - y)<td>
    </tr>
</table>

Since the dependent variable is **numeric** we are using the **Simple Linear Regression model** using the **scikit-learn** library. Added to testing the model on the validation dataset, we are asked to predict the **student marks** resulting from **9.25 hours of study per day**. We have also tried how much of an increase a 15 minutes more study would result in. 

### Table Of Contents:

* **A. Exploratory Data Analysis**
     1. Data Summary (EDD) & Inference
     2. Data Visualization: 
        _a. Distance plot & Inference_
        _b. Scatter plot & Inference_
        
        
* **B. Data Modelling**
     1. Data Splitting
     2. Model Creation & Interpretation
     3. Model Prediction & Prediction Comparison
     4. Score of student if study hours is 9.25/day
     
