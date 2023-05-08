# Big-Data-ETL

Overview

Transforming an Amazon customer review data set into a DataFrame and analyzed with PySpark and then uploaded the data into an RDS Instance.

____

Process

First I installed Spark and Java on the Google Colab Notebook.
Next, I initiated the Spark session and got the postgresql package.

![Screenshot 2023-05-07 at 8 34 08 PM](https://user-images.githubusercontent.com/108643565/236728123-2a72bc6b-cdc8-4d2b-a272-4a0bb746d184.png)

Now I used Spark to create a dataframe from the Amazon review data.

![Screenshot 2023-05-07 at 8 36 33 PM](https://user-images.githubusercontent.com/108643565/236728418-cb0c4930-fae2-4cae-a30c-1480c26c6b21.png)

Next, I transformed the data by creating separate tables.
I created a review ID table, a products table, a customers table and a vine table.

![Screenshot 2023-05-07 at 8 40 32 PM](https://user-images.githubusercontent.com/108643565/236728710-d65d7403-7cb0-4055-b7a7-98582ada573d.png)
![Screenshot 2023-05-07 at 8 41 38 PM](https://user-images.githubusercontent.com/108643565/236728831-c7fdaf4b-913d-47b0-b524-b9d7e5ef717f.png)

Finally, I loaded the tables into RDS (Amazon Relational Database Service).

![Screenshot 2023-05-07 at 8 43 07 PM](https://user-images.githubusercontent.com/108643565/236728963-19790433-0870-472f-b830-7059d03bf0b2.png)
