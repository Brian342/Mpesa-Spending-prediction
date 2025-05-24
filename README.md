# M-Pesa Spending Prediction
![Screenshot 1](/Images/Finance.jpg)

M-Pesa is a mobile money service launched by Safaricom.
This project involves the extraction, cleaning, and analysis of M-Pesa transaction data to uncover personal spending patterns. Leveraging Python and Pandas for data preprocessing, the statements were converted from PDF to structured formats. Advanced analytics and forecasting models (e.g., Prophet) were applied to predict future expenses, visualize trends over time, and generate automated financial insights. 
<!--The project also features a Flask-powered interface for interactive dashboards and personalized financial alerts.-->

## Features
- **Data Collection**: Utilizes Python modules like
1. (pikepdf) 
2. (tabula.io - reading the pdf file)
3. (PyPDF2)
- **Data Anonymise**: Removes and anonymise the data
- **Data Cleaning**: Modifies the data, Removes Duplicates, change data types.
- **Data Connection**: Connects the cleaned data into database and saves it for future usage
- **Exploratory Data Analysis and Visualization**: Finding insight and correlation on dataset by answering the following question
- What day of the week do I spend the most money?
1. Spending Patterns
- Which transaction types (e.g., Buy Goods, PayBill, Withdraw) do I use most?

2. People or Places You Transact With
- Which parties do I send/receive money to/from the most?
  
3. Balance & Financial 
- Do larger transactions lead to lower account balances?
   
- **Data Modelling**: Entails 
1. looking for missing values,
2. check outliners(Uses Quantiles range),
3. filling values with median
4. Label Encoding
5. Scaling Values
6. Linear Regression
7. Random Forest Regressor
8. xgboost
9. Model evaluation using R2 score, Root Mean square Error, Mean Absolute Error
10. Future Prediction using Prophet to predict your spendings in the next 60 days or more
    
- **Visualization**: This Entails asking and answering some questions like



## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Brian342/Mpesa-Spending-prediction.git
   cd Mpesa-Spending-prediction
   ```

## Screenshots
Here are some visual representations of the project:

### Data Extraction
![Screenshot 1](/Images/Extracting_Data_pdf.png)

### Data Anonymising
![Screenshot 2](/Images/Anonymising.png)

### Data Connection Database
![Screenshot 3](/Images/ConnectingDatabase.png)

### Transaction During Weekday (Shows which day most Transaction occurs)
![Screenshot 3](/Images/TransactionWeekday.png)

### Transaction Used Most (which Transaction Party you use the most)
![Screenshot 3](/Images/TransactionUsedMost.png)

### Paid In vs Withdrawal (Shows which one affects your mpesa account Paid in or Withdrawal)
![Screenshot 3](/Images/PaidInvsWithdrawal.png)

### Transaction Impact on Balance (Shows the Impact of High Transaction on your Balance)
![Screenshot 3](/Images/TransactionImapactBalance.png)

### Checking Outliners using Boxplot
![Screenshot 3](/Images/CheckingOutliners.png)

### XgboostModel
![Screenshot 3](/Images/XgboostModel.png)

### Actual vs prediction xgboost
![Screenshot 3](/Images/Actual_vs_Prediction_Xgboost.png)

### Prophet prediction (shows your spending in the next 60 days)
![Screenshot 3](/Images/Prophet.png)

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

