# **Analyze Retail Banking Demo Data Using Tableau**

#### In this report, We will explain some analysis and predictions on Retail Banking Demo Data.

![1](https://user-images.githubusercontent.com/65326291/134653940-49ed7c58-be86-4050-9a4f-8ea7324efbca.png)

###### [Retail Banking Demo Data Dashboard](https://public.tableau.com/app/profile/amaal.ahmed/viz/Banking_16305113038900/Dashboard1?publish=yes)

## **Description:**

Retail Banking Demo Data is a datasets was stitched together from real-world data sources, CRM and core banking. Built off of that 1999 data. It is not for commerical use.
This data is related to a fake bank:Eagle National Bank.

## **Summary:**

- Completed Files - core banking system. accounts linked by identifiers. FULLY TRANSLATED and further modified and augmented data built off the real 1999 Czech banking dataset posted by Liz Petrocelli.
- Geospatial data is only accurate at a zip code and area code of phone number level for MA and NY records.
- Addresses are not real, but MA and NY zip codes are, other zip codes are random numbers from 40000-60000.
- CRM Datasets - Frankenstein data. try parsing the text in the CRM events for sentiment analysis. These were built off of financial institution complaints database so everyone is most likely very upset.
- Some phone calls from call center match to CRM event records.
- Some phone calls from call center are from known client numbers so we can infer who called.
- Some phone calls for certain clients are from alternative phone numbers so we can figure out a back up phone number for them.

## **Methodology:**

The dataset was cleaned, explored and specific it to the small target to analyse. Starting with some important analytic numbers that show Retail Banking for a fake bank (Eagle National Bank):

1. Total Numbers of Loans.
2. Average Amount of Loans.
3. Average Duration of Loans.
4. Number of Accounts.

### **Amount of Loans per City:**

![2](https://user-images.githubusercontent.com/65326291/134653951-fafc6308-3dfe-479f-9fe8-01e4d8b7151a.png)

### **Number of Loans per State:**

![per state](https://user-images.githubusercontent.com/65326291/134655879-c03f583a-7062-4ed7-a107-73929627a65a.png)

Number of Loans per State is highiest on New York.

### **Percentage of Purpose of Loans:**

![percentage](https://user-images.githubusercontent.com/65326291/134655889-82bcb91b-1441-4e9d-b3a1-dfd562eeb6dd.png)

This chart shows the largest number of loans was for home purpose with 78.55%, unlike loans for cars was 4.44%.

### **Amount of Paid Loans over Time:**

![over time](https://user-images.githubusercontent.com/65326291/134655868-97c663dc-a8b9-4d66-bab5-702cce4e3923.png)

This shows that the payments are not stable.
By 2017, The largest payments was occured.
After that on 2018, It return to decrease.

## **Resources:**

[Retail Banking Demo Data](https://data.world/lpetrocelli/retail-banking-demo-data)
