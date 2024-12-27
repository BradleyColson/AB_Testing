# AB_Testing!

AB Testing Synthetic Dataset

- [Overview](#overview)
- [Data_Description](#Data_Description)
- [Key_Insights](#Key_Insights)
- [Business_Suggestions](#Business_Suggestions)
- [Data_Limitations](#DataLimitations)
- [Technical_SQL_Details](#Technical_SQL_Details)

# Overview

Investigating an A/B Testing dataset. This is purely data driven as there are no images included. 

Is Group A or Group B getting more Conversions. Conversion is when a customer clicks to take an action.


# Data Description

Synthetic A/B testing data set. Comprised of 5,000 rows.

It's from Kaggle and didn't need cleaning. I would have removed duplicates, split columns, used =name(Proper) to standardize the headers.

Columns are user id, Group, Page Views, Time Spent, Conversion, Device, and Location

Conversion means the customer clicked an action.  Device is Mobile or Desktop. Location was UK based.


# Key_Insights

The Conversion for Group B rate for Yes is much higher than Group A.  B Yes was 0.02% A was 0.06%.

For No Conversion Group B was still better. Group B No was 0.42% and Group A 0.47%

Group B is Yes at a higher rate than A on both Mobile and Desktop devices.  No Conversion is also lower on Mobile devices.

Customer location, Time Spent, and Page Views had little to no impact on Conversion rate.

## PowerBI dashboard showing key metrics

![AB_Test](https://github.com/user-attachments/assets/a523996a-2ce9-42ef-b321-5982fbc66f13)

# Business_Suggestions

Focus marketing on Group B and try to improve No conversion on Desktop devices

# Data_Limitations

There was no data to clean.

There was no time frame to gauge by.  

EDA on this data set taught me a lot about A/B testing. 

# Technical_SQL_Details

[AB Testing MYSQL Queries.docx](https://github.com/user-attachments/files/18262635/AB.Testing.MYSQL.Queries.docx)

