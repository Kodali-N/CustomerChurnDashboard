
# Telecom Customer Churn Dashboard(PowerBI)

### Overview:
Using Telecom customer churn data,
 I created a dashboard which gives a visual 
 insight about the churners' profile. The dashboard provides information about how tenure, Internet services opted
 by the customers, the contract type and other such factors are linked to Churn

### Data Cleaning:
By reading the dataset into dataframe
using pandas, I removed the records with 
missing values, which addded upto only 0.15%
of the total data. I further removed columns
such as Customer ID and tenure. Before removing
the tenure column, new colum:'Tenure Bins' was 
created to group customers based on their tenure period.

### Data Exploration:
- Performed both, Univariate and Bivariate analysis.
- Converted 'Churn' to a binary numeric varaible, and all the 
    categorical variables into dummy varaibles.
- Upon plotting the relation between Monthly charges, Total charges,and tenure, with Churn, we could observe that: 
    Low tenure, High monthly charges, and low Total charges are linked
    to High Churn.
<img src="https://user-images.githubusercontent.com/86663030/212529266-68900f29-203c-4cbf-82f2-3ca68e3d6101.png" width="450" height="350">
<img src="https://user-images.githubusercontent.com/86663030/212529262-0e9dfc8d-4530-42ba-a0e0-96017b2c4872.png" width="450" height="350">
<img src="https://user-images.githubusercontent.com/86663030/212529447-9319ae72-4638-4bf9-a789-c432192371fe.jpeg" width="450" height="350">

- When a correlation was built between all the predictors
    with churn, we could observe that High churn was observed in case of
    monthly contracts, those who avail no tech support, in the first year
    of subscription and those who opted for Fibre Optic internet.
- Low churn was observed in case of long term contracts, 
    those customers who are engaged with the service for more than 5 years.
- Factors like gender, availability of phone services, and 
    number of multiple line had nearly 0 impact on the churn.

### Dasboard:
- tool used: Power BI
- This dashboard helps one analyze
    the profile of the churner in comparision
    to total customers.
![Dashboard](https://user-images.githubusercontent.com/86663030/210976187-aff5fab3-d026-404d-a4e9-c6a7e56f1390.png)
