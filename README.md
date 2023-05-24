# Travel-Insurance-ML

The aim of this project is to predict whether a person will buy a travel insurance or not based on factors such age,employment type, graduate, annual income, number of family members, chronic diseases, frequent flyer and ever travelled abroad. The study includes analysis of the variables, pre-processing of the data and also prediction based on SVM, KNN and Random Forest algorithms.\
\
Intuitively we predict that the factors like **annual income, frequent flyers, and employment type** will have high correlation with travel insurance purchase. For example, people with higher income will be more likely to buy travel insurance compared to people with lower income.

#### Data
Dataset that we use in this study is based on travel insurance data obtained from kaggle. The content of the dataset are as follows:\
**Age**- Age Of The Customer\
**Employment Type**- The Sector In Which Customer Is Employed\
**GraduateOrNot**- Whether The Customer Is College Graduate Or Not\
**AnnualIncome**- The Yearly Income Of The Customer\
**FamilyMembers**- Number Of Members In Customer's Family
\
**ChronicDisease**- Whether The Customer Suffers From Any Major Disease Or Conditions Like Diabetes/High BP or Asthama,etc.\
**FrequentFlyer**- Derived Data Based On Customer's History Of Booking Air Tickets On Atleast 4 Different Instances In The Last 2 Years[2017-2019]\
**EverTravelledAbroad**- Has The Customer Ever Travelled To A Foreign Country
\
**TravelInsurance**- Did The Customer Buy Travel Insurance Package During Introductory Offering Held In The Year 2019

#### Results
We compared KNN, SVM, Random Forest and logistic regression to classify customers behavior on a travel insurance dataset of 9 features and found KNN as the best with 81% precision and 98% recall on validation
