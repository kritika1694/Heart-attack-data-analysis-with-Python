Heart Attack Data Analysis using Python 

Skills : Python, Pandas, Matplotlib, Seaborn, Plotty Express

Project is about: Data cleaning, exploratory data analysis and visualisations of heart attack data matrices, using Python- Pandas, Seaborn, and Plotly express.

Dataset Information: Gender, Age, Blood Pressure (mmHg), Cholesterol (mg/dL), Has Diabetes, Smoking Status, Chest Pain Type, Treatment

Summary of Data Analysis:

- Importing packages, reading .csv file in pandas, Data cleaning: removing duplicates, unique column values,checking null values.
- EDA: finding count and frequency of categorical variables and descriptive statistical analysis of numerical variables.
- Visualizations: Correlation matrix and histogram distribution of numerical variables; Bar representation of univariate analysis for categorical variables

Insights from the data analysis:

-The histogram analysis shows count of age, blood pressure and cholesterol:
  ![P](https://github.com/user-attachments/assets/e703d188-c1f6-4338-9129-1d8a2631b5a1)

- The numerical variables show the following:
  
     - Age: Ranges from  30 to 89 years, averaging at 60.33 years. Majorly older adults to senior citizens dominate the data.
     - Blood Pressure : Ranges from a 90 mmHg to 199 mmHg, averaging at 145.44 mmHg.
     - Cholesterol: Ranges from a 150 mg/dL to 299 mg/dL, averaging at 223.78mg/dL. Majority have a higher lipid profile more than 200.
        

- The Correlation analysis shows:
  ![3](https://github.com/user-attachments/assets/ff7a267e-40f6-4026-a0b2-512328e6a8b2)

     - Age and blood pressure shows slightly negative correlation: data suggests negligible relationship between them.
     -  Blood Pressure and Cholesterol shows a slight positive correlation of 0.044, indicating some relationship.
     -  Again age and cholesterol shows very weak positive correlation as per the data.

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
