# Bank_loan_defaulter_analysis_python
Loan defaulter data analysis with the help of python.

# Download dataset from kaggle
https://www.kaggle.com/datasets/gauravduttakiit/loan-defaulter/data

# All the analysis

A significant portion of clientele has opted for cash advances.
Individuals who have availed themselves of cash loans exhibit a lower likelihood of defaulting.

# CODE_GENDER -
•	The majority of the loans have been acquired by females.

•	The default rate for females is approximately 7%, indicating a safer and lower rate compared to males.

NAME_TYPE_SUITE -
Individuals without companionship have secured the majority of the loans, and the default rate is around 8.5%, which remains acceptable.

NAME_INCOME_TYPE -
The most secure segments encompass those engaged in work, commercial associates, and pensioners.

NAME_EDUCATION_TYPE -
Opting for higher education proves to be the most secure choice for loan issuance, boasting a default rate of less than 5%.

NAME_FAMILY_STATUS -
Targeting married individuals is advisable, as the default rate stands at 8%.

NAME_HOUSING_TYPE -
Individuals with a house or apartment are a safe demographic for loan approval, exhibiting a default rate of approximately 8%.

OCCUPATION_TYPE -
•	High default rates are observed among Low-Skill Laborers and drivers.
•	On the contrary, accountants display a lower likelihood of defaulting.
Core staff, Managers, and Laborers are reliable targets, with a default rate ranging from <= 7.5 to 10%.

ORGANIZATION_TYPE -
•	Transport type 3 stands out as the highest defaulter.
•	Conversely, Others, Business Entity Type 3, and Self-Employed categories are favourable, boasting a default rate around 10%.

# =======univariate numeric variables analysis========
   	The majority of loans were approved for goods priced within the range of 0 to 1 million.
   	Predominantly, loans were granted for a credit amount falling between 0 to 1 million.
   	A significant portion of customers is making annuity payments in the range of 0 to 50,000.
   	Typically, customers report an income falling within the bracket of 0 to 1 million.


# ============Bivariate Analysis==================
   AMT_CREDIT and AMT_GOODS_PRICE: Show a linear correlation; as AMT_CREDIT increases, defaulters decrease.
   Income Analysis: Customers with income less than or equal to 1 million are more likely to take loans. However, those with income below 1 million and loan amounts exceeding 1.5 million may pose a higher default risk.
  Children Analysis: Individuals with 1 to less than 5 children appear to be safer candidates for loan approval.
 Annuity Payment Analysis: Customers capable of paying an annuity of 100,000 are more likely to secure loans, especially amounts below 2 million, indicating a safer segment.

# ============Analysis on Merged Data==============
    Loan Purpose Analysis: Loans sought for repairing purposes have the highest previous applications and also the highest number of cancellations.
    Previous Application Status: 80-90% of applications previously labelled as cancelled or refused are now re-payers in the current dataset.
    Unused Offers Analysis: Previously unused offers have the highest number of current defaulters, despite targeting high-income customers.

## Final Insights and Recommendations
   Target Customer Profile:
   Low Income: Below 1 million.
   
   Occupation: Others, Business Entity Type 3, or self-employed, focusing on roles like accountants, core staff, managers, and labourers.
   
   Family Status: Owns a house or apartment, married with up to five children.
   
   Education: Higher education background, preferably female.

# Preferred Characteristics:
   Unaccompanied individuals demonstrate a safer default rate, approximately 8.5%.

# Recommended Amount Segments:
  Credit Amount: Up to 1 million.
   Annuity Payments: Around 50,000 (subject to eligibility).
  Income Bracket: Below 1 million.

# Special Considerations:
Analyze and consider extending loans to the 80-90% of customers previously labelled as cancelled/refused who are now re-payers.

# Precautions:
  	Avoid organizations classified as Transport Type 3.
  	Exclude occupations like Low-Skill Laborers and drivers from the target demographic.
  	Approach offers to previously unused and high-income customers with caution.
  	Careful consideration is needed for applications with high income seeking repairing loans.
  	Caution is advised when dealing with previously unused offers, despite the applicants having a high-income band.
