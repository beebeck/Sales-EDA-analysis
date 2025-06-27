# Sales-EDA-analysis
The project aims at developing insights on Python environment regarding the progress of company based on their sales and trend over time. There are several different parameters where the analysis has been done to undergo Exploratory Data Analysis.

# Why this Project?
Data analysis based on the sales of particular company's data will direct the way analysis has to be done. No matter whether business firm is small or big, understanding data and their flow , is very important on how the business is performing. Keeping in mind the same sort of thing, I have undergone analysing sales data where I got many different insights based on used parameters and library implementations.

# Insights
 - Identified null columns.
   When I went throug the analysis portion of my data, I found out that there were columns with 0 values or records within it. I deal with those values and removed the existing null values by drop() function.
   ![DropNull](https://github.com/user-attachments/assets/46db9ae7-10da-4993-8910-b0adb33037b9)
- Row with null records
  Further analysing on my data, I found out that there were some fields inside row where values were missing. I kept on an intense analyse regarding their impact on the overall performance of report and found out that their dropping would not affect the data model or further analytical sides. Used functions:   isna() - to find the null values and dropna() - to remove null
  ![image](https://github.com/user-attachments/assets/791f68a0-f684-4ff7-9037-97509a2ebb33)
- Modified column name
  Analysing the data, I found the best way that the data in a table to be represented as. Which is why i Changed the column name Marital_status to weeding following up with rename() function.
  ![image](https://github.com/user-attachments/assets/13149466-740d-4900-8f66-e06f1784cb7f)
- Statistical analysis
  I undergone statistical analysis with describe() function to understand how data are arranged and their respective impact in the overall performance of existing datasets.
  ![image](https://github.com/user-attachments/assets/0b96aa7b-914a-44bf-bfcc-6e4ae441f412)
- Category standings
  Inside EDA, I analysed different column parameters with intense visualization in better understanding how they are standing in my report and in dataset too.
  ![image](https://github.com/user-attachments/assets/c4c71672-39b1-4a26-9c5d-22754e17c94b)
![image](https://github.com/user-attachments/assets/e7eea221-0a32-4f94-b48e-3329725f4e4a)
![image](https://github.com/user-attachments/assets/334f251e-234b-454d-81e8-764b6c469d64)
![image](https://github.com/user-attachments/assets/4af5ba7d-d6f4-4838-a718-e52bc83ed7f5)
- Top 10 most sold product
  ![image](https://github.com/user-attachments/assets/639cddd0-c069-46eb-9492-f48c18422448)

# Conclusion
On top of carrying out all those analysis, the conclusion has been outrageous as the product and different dimensions on the business have their impact on the overall performance of the existing business. For instance, female proportion has been more in the overall sales and age group 26-35 has been the biggest contributor in overall transactions. Uttar Pradesh is the main seller by region having non married as their major portion of audience. Occupation wise, IT sector and Healthcare has been outrageous since they both surpassed the 1400 count line. The product category which has got more impressions was Food and cloting stream.
