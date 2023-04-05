# SSIS_DataWarehouse_PKG

# Tools Used:
1. SQL Server Management Studio 2022
2. Visual Studio 2019
3. MS SQL Server Integration Service
4. MS Excel

-> First the data is collected from the github repository of Microsoft named "AdventureWorksDW2019.bak" file and restored as database in one server.
-> After that, in another server the database named Vedang is created.
-> In Visual Studio 2019, from the Microsoft SSIS Package, the Integration Service Project is created.
-> In this project, By the means of ETL (Extract, Transform, Load) process, the data is extracted from AdventureWorksDW2019 databse and then transform some tables
and then loaded into the Vedang database.
-> Now, after this; some of the tables are extracted from the Vedang database from SQL Server Management Studio and the transorm them into .txt file and these .txt
file is again imported and transformed in the Excel file using Power Query and then load the formatted required data.

