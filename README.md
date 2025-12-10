# PRODIGY_DS_02
# Prodigy InfoTech Data Science Internship Task 2:
<br>
<img width="1160" height="646" alt="task2" src="https://github.com/user-attachments/assets/3b051350-416d-45c7-bf9c-38ea2aeb0fa2" />



Welcome to my submission for Task 2 of the Data Science Internship at `Prodigy Infotech`. In this task, I have performed Exploratory Data Analysis (EDA) on a dataset provided, focusing on creating a visualization to represent the distribution of a categorical or continuous variable.

## Dataset

The dataset used for this task is 
<a href="https://github.com/Prodigy-InfoTech/data-science-datasets/tree/main/Task%202">
Titanic - Machine Learning from Disaster
</a>.
 

## Tools and Libraries used

- Kaggle notebook
- Pandas
- Numpy
- Matplotlip 
- Seaborn for visualization



## Exploratory Data Analysis (EDA)

The analysis primarily focused on preparing the train.csv data and then exploring the relationship between various features and the target variable, 'Survived'. The initial preprocessing and cleaning phase involved loading the dataset, followed by feature dropping, where the Cabin, Ticket, and PassengerId columns were removed as they were deemed less relevant for initial modeling or contained too many unique or missing values. Missing value handling was then performed on key features: the missing values in the Age column were imputed (filled) with the median age, and the missing values in the Embarked column were filled with the mode (most frequent port of embarkation). With the data cleaned, the feature analysis proceeded using visualizations. A series of count plots and bar plots were generated to assess the impact of categorical features on survival, specifically visualizing the raw numbers and the mean survival rate segmented by Gender ('Sex') and Passenger Class ('Pclass'). Finally, the distribution of the numerical Age feature against survival status was explored using a combined histogram and Kernel Density Estimate (KDE) plot to understand age-based survival differences.


## Conclusion

 The exploratory data analysis strongly suggests that certain factors were critical predictors of survival. The key findings drawn from this typical Titanic EDA are:

Gender is the strongest predictor: Females had a significantly higher survival rate than males, supporting the "women and children first" protocol.

Passenger Class is a major factor: Passengers in First Class (Pclass=1) had the highest survival rate, while those in Third Class (Pclass=3) had the lowest, indicating a correlation between socio-economic status/location on the ship and survival.

Age plays a role: The distribution plots usually reveal that children (younger ages) had a higher chance of survival, and a large number of fatalities were among young to middle-aged adults.

Thank you for reviewing my submission!

## 📬 Contact

For any inquiries or feedback regarding this project, please contact:
- Email: 23bt04064@gsfcuniversity.ac.in
