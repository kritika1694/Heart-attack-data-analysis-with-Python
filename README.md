Heart Attack Data Analysis using Python 

Skills : Python, Pandas, Matplotlib, Seaborn, Plotty Express

The project is about:

Data cleaning, exploratory data analysis and visualisations of heart attack data matrices, using Python- Pandas, Seaborn, and Plotty express.

Dataset Information:

- Gender: Categorical variable with two unique values: 'Male' and 'Female'.
- Age: Numerical variable with unique values ranging from 30 to 89. 
- Blood Pressure (mmHg): Numerical variable with a wide range of unique values.
-  Cholesterol (mg/dL): Numerical variable with unique values .
- Has Diabetes: Categorical variable with two unique values: 'No' and 'Yes'.
- Smoking Status: Categorical variable with three unique values: 'Never', 'Current', and 'Former'.
- Chest Pain Type: Categorical variable with four unique values: 'Typical Angina', 'Atypical Angina', 'Non-anginal Pain', and 'Asymptomatic'.
- Treatment: Categorical variable with four unique values: 'Lifestyle Changes', 'Angioplasty', 'Coronary Artery Bypass Graft (CABG)', and 'Medication'.

Summary of Data Analysis:

- Importing packages in Python, reading .csv file in pandas, Data cleaning: removing duplicates, unique column values, checking null values etc.
 
- Exploratory data analysis: finding count and frequency of categorical variables and max, min, average etc of numerical variables.
  
- Visualizations: Correlation matrix of numerical variables: age, blood pressure and cholesterol; histogram distribution of : age, blood pressure and cholesterol;
                  Bar representation of univariate analysis for categorical variables- Gender, Has Diabetes, Smoking Status, Chest Pain Type, Treatment.

Insights from the data analysis:

- The numerical variables show the following:
  
     - Age: Ranges from a minimum of 30 years to maximum of 89 years, averaging at 60.33 years. Majorly older adults to senior citizens dominate the data.
        
     - Blood Pressure : Ranges from a minimum of 90 mmHg to maximum of 199 mmHg, averaging at 145.44 mmHg.
    
     - Cholesterol: Ranges from a minimum of 150 mg/dL to maximum of 299 mg/dL, averaging at 223.78mg/dL. Hence majority have a higher lipid profile more than 200
        
- The histogram analysis shows count of numeric variables.
  
- The Correlation analysis shows:
  ![3](https://github.com/user-attachments/assets/ff7a267e-40f6-4026-a0b2-512328e6a8b2)

     - Age and blood pressure shows slightly negative correlation: data suggests negligible relationship between them.
        
     -  Blood Pressure and Cholesterol shows a slight positive correlation of 0.044, indicating some relationship.
        
     - Again age and cholesterol shows very weak positive correlation as per the data.

- Univariate Analysis: The categorical variables are visualised as per their frequency, as shown in diagrams: 
  ![a1](https://github.com/user-attachments/assets/1c677b2c-f717-4cca-9572-fe6d6433aa61)
  ![a2](https://github.com/user-attachments/assets/241a012f-c421-401d-b860-9e90fdadde5b)
                    ![a3](https://github.com/user-attachments/assets/3b082d95-d7d9-4627-93dc-db630004f590)

     - Gender: Female number is higher(510) vs Males(490)
        
     - Has diabetes: Majority of the people have diabetes(517/1000).
        
     - Smoking status: Who smoked currently and former are significantly higher than ones who never smoked.
        
     - Chest pain type: Most commonly Non anginal pain among the four types.
  
     - Treatment: Best treatment response came from Lifestyle changes.
 
  Implications of this Project:

   - The insights derived from this dataset can inform public health initiatives aimed at reducing the burden of cardiovascular diseases through detection of risk factors.
   
   - By analyzing these variables, the dataset can provide information that is useful for clinical decision-making, patient education, and public health planning.
