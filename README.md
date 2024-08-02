**Jamboree Business Case- Linear Regression**

From company’s perspective:
  - Jamboree is a renowned educational institution that has successfully assisted numerous students in gaining admission to top colleges abroad. With their proven problem-solving methods, they have helped students achieve exceptional scores on exams like GMAT, GRE, and SAT with minimal effort.
  - To further support students, Jamboree has recently introduced a new feature on their website. This feature enables students to assess their probability of admission to Ivy League colleges, considering the unique perspective of Indian applicants.
  - By conducting a thorough analysis, we can assist Jamboree in understanding the crucial factors impacting graduate admissions and their interrelationships. Additionally, we can provide predictive insights to determine an individual's admission chances based on various variables.

From learner’s perspective:
  - Solving this business case holds immense importance for aspiring data scientists and ML engineers.
  - Building predictive models using machine learning is widely popular among the data scientists/ML engineers. By working through this case study, individuals gain hands-on experience and practical skills in the field.
  - Additionally, it will enhance one's ability to communicate with the stakeholders involved in data-related projects and help the organization take better, data-driven decisions.

**Insights:**

I.Dataset feature properties and Relationship:

  - There are a total of 500 data points, meaning, 500 unique applicants in the Jamboree dataset.
  - The applicants have around 7 independent features like GRE Score, TOEFL Score, CGPA, Research flag, and one Target variable to determine what is the chance of Admit of the applicant into Ivy league school.
  - The Chance of Admit is linearly related to GRE Score, TOEFL Score and CGPA features.
  - The applicants who have good Research experience prior to applying have a good chance of getting Admission into the Ivy school.

II.Regression Model Features and results:

  - GRE Score, TOEFL Score and CGPA features have high coefficients in the model, proving that they are the most prominent and important features that affect the Chance of Admit the most.
  - Observing the results of the Regression analysis, CGPA feature is identified as the most influential feature in determing the Chance of Admission of an applicant into Ivy School.
  - The Letter of recommendation (LOR) is a Plus for applicants, which has a positive impact on increasing the Chance of Admission.
  - SOP and University Rating have the lowest impact on the target variable - Chance of Admit.

III.Model Performance:

  - From the Statsmodel Analysis, we see that the Model Adjusted R2 score is approximately 82%, which is a good model and captures 82% of the Variance in Chance of Admission.

IV.Linear Regression Assumptions Tests:

  - Variance Inflation factor (VIF) scores of all relevant features were lesser than 5, indicating that there is no Multicollinearity present between teh feature variables.
  - The mean of residuals was found out to be 0.002, which is very close to 0, which says that the model has predicted the "Line of Best Fit".
  - The features GRE Score, TOEFL Score, CGPA have prominent linear relationship with the target - Chance of Admit.
  - The graphical analysis of Residuals and the Target data and the Goldfeld Quandt test proved that there low or almost no Heteroscedascticity.
  - From the QQ plots and the Shapiro Wilk test, it is evident that the residuals do no follow Normal distribution
  - All the features have moderate to High Positive correlation with the target - Chance of Admit.

**Recommendations:**

  - Jamboree should ask the applicants to focus on increasing their CGPA since it is the most Crucial factor in increasing the chance of Ivy Admission.
  - Applicants should have their GRE score more than 330 and TOEFL Score more than 115 to obtain more than 85% chance of getting into desired good Ivy School.
  - SOP Feature data collection can be ignore since it has the least effect on the Target variable, that is determining the chance of Admission.
  - Applicants can addiitonally enrich their Research experince and get best letter of recommendations to increase their Chance of Admission.
