# MBC_TEST
MCB Assessment Steps for Data Migration:
1.	Execute the file “DB_Prequisite.sql” which will enable you to create the table “XXBCM_ORDER_MGT” and inserts all the data.
2.	Execute the file “DB_Tables” which will create the tables below : 
•	XXBCM_ORDER_MGT_CLR : Copy of table “XXBCM_ORDER_MGT” with all cleaned data
•	XXBCM_SUPPLIER : Table contain all data about supplier 
•	XXBCM_TRANSACTION : Table contain all data about transactions
3.	Compile the package PCG_XXBCM_ORDER from the file PCG_XXBCM_ORDER.sql
4.	Execute the file “DB_All_Data.sql” which will insert all data in the three table created in step 2
5.	Execute the file “DB_Views” which will create the views for task 4 , 5 and 6

TASK 4: execute the file “DB_SUMMARY.sql”
TASK 5: execute the file “DB_THIRD_HIGHEST.sql”
TASK 6: execute the file “DB_SUPPLIER_LIST.sql”

