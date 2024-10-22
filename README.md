# Loan-prediction

**Summary**

A loan prediction model is constructed and assessed in this Jupyter notebook. Data preparation, visualization, model training, and assessment are all covered. Based on application data, the model is intended to forecast if a loan will be authorized.

**The dataset**

The dataset included in this investigation includes a number of characteristics pertaining to loan applicants, such as:

Loan_ID: The loan's unique identification number.
Gender: The applicant's gender.
Married: The applicant's marital status.
The quantity of dependents.
Education: The applicant's degree of education (graduate or non-graduate).
Self_Employed: Status of self-employment.
ApplicantIncome: The applicant's income.
CoapplicantIncome: The co-applicant's income.
LoanAmount: The total loan amount.
Loan_Amount_Term: The loan's duration expressed in months.
Credit_History: The applicant's credit history.
Property_Area: The location of the property (Urban, Rural, or Semiurban).
Target variable Loan_Status: Indicates if a loan has been granted (1 for approved, 0 for rejected).

**Dependencies**

Make sure to install the following dependencies:

  **pip install pandas numpy matplotlib seaborn scikit-learn**

**Procedures**

**1. Preprocessing of Data**

-Use the median or most frequent values for different columns to handle missing data.
-Use encoding techniques to translate category information into numerical representations.

**2. Analysis of Exploratory Data (EDA)**

The notebook uses matplotlib and seaborn to illustrate a number of characteristics, including income distributions, loan amounts, and status.
Features' correlation is assessed.

**3. Engineering Features**

developed new features including pwage, which may be a measure of per capita income based on the incomes of applicants and coapplicants.

**4. Model Construction**

-Based on characteristics, machine learning models are developed to forecast loan status (probably with scikit-learn).
-Several measures are used to assess the model's performance (accuracy, precision, recall, etc.).

**5. Preserving Processed Information**

  Selected_loan_data1.csv contains a subset of the cleaned and chosen data.

**Use**

To operate the notebook:

-Install the necessary prerequisites.
-The Jupyter notebook should open.
-To preprocess the data, visualize characteristics, train the model, and assess the outcomes, follow the cells one by one.

**In conclusion**

The notebook offers a comprehensive procedure for forecasting loan approvals based on application data, including data cleansing and model validation.

