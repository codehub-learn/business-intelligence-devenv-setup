# Demo databases for Business Intelligence

## AdventureWorks download links 

[OLTP version of AdventureWorks](https://github-production-release-asset-2e65be.s3.amazonaws.com/53698446/08c81528-c32c-11e7-8043-34d39e9c1506?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWNJYAX4CSVEH53A%2F20200507%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20200507T103956Z&X-Amz-Expires=300&X-Amz-Signature=620eee576bdd7b33ecbed6ed373e600d22b2bcbe3d9ac36ef9381857f910579a&X-Amz-SignedHeaders=host&actor_id=26898518&repo_id=53698446&response-content-disposition=attachment%3B%20filename%3DAdventureWorks2012.bak&response-content-type=application%2Foctet-stream)

[DW version of AdventureWorks](https://github-production-release-asset-2e65be.s3.amazonaws.com/53698446/6cc5eb50-c32b-11e7-95a9-900b660b537e?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWNJYAX4CSVEH53A%2F20200507%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20200507T104021Z&X-Amz-Expires=300&X-Amz-Signature=dd24d1cd6cf19069f5d1742a05a2667e94eb4390b484234a3dcfd7fe9489bb99&X-Amz-SignedHeaders=host&actor_id=26898518&repo_id=53698446&response-content-disposition=attachment%3B%20filename%3DAdventureWorksDW2012.bak&response-content-type=application%2Foctet-stream)

## Restore instructions
Follow the below steps to restore a backup of your database using SQL Server Management Studio.

1. Open SQL Server Management Studio and connect to the target SQL Server instance.
1. Right-click on the Databases node, and select Restore Database.
1. Select Device and click the ellipses (...)
1. In the dialog Select backup devices, click Add, navigate to the database backup in the filesystem of the server, and select the backup. Click OK.
1. If needed, change the target location for the data and log files, in the Files pane. Note that it is best practice to place data and log files on different drives.
1. Click OK. This will initiate the database restore. After it completes, you will have the AdventureWorks database installed on your SQL Server instance.
