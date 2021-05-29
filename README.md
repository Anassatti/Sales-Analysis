# Sales-Analysis
Analysis of 12 months sales data, so I can answer business questions

I follow below planning to produce meaningful dashboards:

# 1.Project Planning
     Analysis of 12 months sales data, so I can answer business questions

# 2.Data Collection:
     Sales data for 12 months are available.
# 3. Data Cleaning
   I did below steps:
     1. Merge all 12 months sales data into single files
     2. Drop all NAN rows from the data.
     3. Convert the date to datetime.
     4. Remove'Or' from dataframe.


# 4. Expoloray Data Analysis(EDA)
       Here there are questions need to be answered:
  ## 1.What was the best month for sales?How much was earned that month?
            To asnwer this question, I did:
              1. Add and separate month column since it part of the sales date(04/19/2020).
              2. Add new column called sales, which is quanity*price for each month
              3. Convert existed columns to their right type, for instance price was string, it should integer
              4. Group By every month by sum. Here we answer the question, below graph show that:

![image](https://user-images.githubusercontent.com/73906550/120063977-9eebf280-c072-11eb-8e5e-f82f8c799bd8.png)



              
              
 ## 2. What city had the highest number of sales
           To answer this question, I did:
             1. Add city column.
             2. Separate city for the purchase address column, which include full address and the city withing that.
             3. There are duplicate in cities, that is mean alot of clients from the same city, but they different in their own address, so here I dded city code.
             4. Group by cities by sales, revealed which cities have the highest sales.Below dashboard show that:
            ![image](https://user-images.githubusercontent.com/73906550/120062791-94c6f580-c06c-11eb-9733-f8cd02b633eb.png)
   ## 3.What the time we should increase advertistments to maximaize the products?
      1. Covert order date to date time.
      2. Add two column for the order time(Hours, Minutes). Below graph show that
         ![image](https://user-images.githubusercontent.com/73906550/120062915-26366780-c06d-11eb-8e4a-0ed85e4350bf.png)
  ## 4.what product sold the most?Why do you think it sold the most?     
    ![image](https://user-images.githubusercontent.com/73906550/120063550-54697680-c070-11eb-8a60-33aa2f651d3c.png)

# 5. Model Building
  I built model to predict product prices. 

Next Step: I will build Power BI dashboard to have new insight.
