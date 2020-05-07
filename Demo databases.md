# Demo databases for Business Intelligence

## AdventureWorks download links 

[OLTP version of AdventureWorks](https://github.com/Microsoft/sql-server-samples/releases/download/adventureworks/AdventureWorks2012.bak)

[DW version of AdventureWorks](https://github.com/Microsoft/sql-server-samples/releases/download/adventureworks/AdventureWorksDW2012.bak)

## Restore instructions
Follow the below steps to restore a backup of your database using SQL Server Management Studio.

1. Open SQL Server Management Studio and connect to the target SQL Server instance.
1. Right-click on the Databases node, and select Restore Database.
1. Select Device and click the ellipses (...)
1. In the dialog Select backup devices, click Add, navigate to the database backup in the filesystem of the server, and select the backup. Click OK.
1. If needed, change the target location for the data and log files, in the Files pane. Note that it is best practice to place data and log files on different drives.
1. Click OK. This will initiate the database restore. After it completes, you will have the AdventureWorks database installed on your SQL Server instance.
