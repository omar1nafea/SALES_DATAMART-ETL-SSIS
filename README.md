# SALES_DATAMART-ETL-SSIS
Create Sales_Datamart and Design  ETL pipeline using (SSIS) to extract data from AdventureworksDB 2019 then make some transformations on it and load it into the sales_datamart.

# STAR SCHEMA
create dimentional tables and fact table of sales_dm using creation dm SQL FILES.   
![](images%20of%20implementation/data%20mart%20diagram%20(star%20schema).PNG)

# CREATE PACKAGE FOR DIMENTION (DIM_PRODUCT) 
extract data of product_dimention  from   adventureworks_db and make some transformations and implement SLOWLY CHANGING DIMENTIONAL (scd) using SSIS wizard to control changes in the dimention.

![](images%20of%20implementation/dim_product%20package%201.PNG)
![](images%20of%20implementation/dim_product%20package%202.PNG)
# EXECUTION OF DIM_PRODUCT PACKAGE
dim_product package is sucessfully executed and load the data into sales_datamart.

![](images%20of%20implementation/dim_product%20package%20execute1.PNG)
![](images%20of%20implementation/dim_product%20package%20execute1.PNG)
![](images%20of%20implementation/dim_product%20package%20execute3.PNG)
![](images%20of%20implementation/dim_product%20package%20results.PNG)
# CREATE PACKAGE FOR DIMENTION (DIM_customer) 
extract data of product_dimention  from   adventureworks_db and make some transformations and implement SLOWLY CHANGING DIMENTIONAL (scd) using SSIS wizard to control changes in the dimention.

![](images%20of%20implementation/dim_customer%20package%201.PNG)
![](images%20of%20implementation/dim_customer%20package%202.PNG)

# EXECUTION OF DIM_customer PACKAGE
dim_customer package is sucessfully executed and load the data into sales_datamart.

![](images%20of%20implementation/dim_customer%20execute.PNG)
![](images%20of%20implementation/dim_customer%20execute%201.PNG)
![](images%20of%20implementation/dim_customer%20execute%202.PNG)
![](images%20of%20implementation/dim_customer%20package%20results.PNG)

# CREATE PACKAGE FOR DIMENTION (DIM_DATE) 
extract data of product_dimention  from   csv file and make some transformations then load it to sales_datamart.

![](images%20of%20implementation/dim_date%20package.PNG)

# EXECUTION OF DIM_customer PACKAGE
dim_customer package is sucessfully executed and load the data into sales_datamart.

![](images%20of%20implementation/dim_date%20package%20execution.PNG)
![](images%20of%20implementation/dim_date%20results.PNG)

# add a new table into datamart to modify country writting format

![](images%20of%20implementation/add%20new%20table%20to%20modifiy%20country%20in%20dim_territory.PNG)

# CREATE PACKAGE FOR DIMENTION (DIM_TERRITORY) 
extract data of territory_dimention  from   adventureworks_db and make some transformations and load it into data mart.

![](images%20of%20implementation/dim_territory%20package.PNG)

# EXECUTION OF DIM_customer PACKAGE
dim_territory package is sucessfully executed and load the data into sales_datamart.

![](images%20of%20implementation/dim_territory%20execute%201.PNG)
![](images%20of%20implementation/dim_territory%20execute%202.PNG)
![](images%20of%20implementation/dim_territory%20package%20results.PNG)

# CREATE PACKAGE FOR FACT TABLE (SALES_FACT) 

![](images%20of%20implementation/fact_sales%20package.PNG)

# EXECUTION OF FACT_SALES PACKAGE
FACT_SALES package is sucessfully executed and load the data into sales_datamart.

![](images%20of%20implementation/fact_sales%20package%20execution.PNG)
![](images%20of%20implementation/dim_territory%20execute%202.PNGfact_sales%20package%20results.PNG)


























