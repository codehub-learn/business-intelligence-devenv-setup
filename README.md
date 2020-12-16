# Hardware and software requirements for Business Intelligence

Getting your PC ready 
## PC's specs
- 8 GB RAM
- 128 GB Storage (SSD would be preferrable)
- 4 Core CPU
- Windows 10, 64 bit

##Important notice
Mac or Linux users can install MS-SQL server using Docker. Instead of Management Studio, Azure Portal Application can be used but without the diagrammatic capabilities. Power BI is NOT supported. Windows in a virtual machine can be an option, or dual boot. 

## Required software 
You will need the MS-SQL Server database (RDBMS), the MS-SQL Server management interface and the Power BI desktop application.
In detail you have to download:

1.  [SQL Server Developer 2019 ](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
    - Download the Developer edition (SQL2019-SSEI-Dev.exe)
    - Execute the SQL2019-SSEI-Dev.exe,  choose Download Media at a specified location
	- Use ISO packaging, mount and install
	- After checking your computer, make full installation, select all oprions and proceed using default settings
	- Add current user in all cases
	- Choose mixed mode authentication using the password
        Password: `passw0rd`	

1.  [SQL Server Management Studio, SSMS 18.5.1](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver15) 
and install the SSMS-Setup-ENU.exe file.


3. Power BI

**[Download the Power BI, desktop](https://www.microsoft.com/en-us/download/details.aspx?id=58494)**
and install the PBIDesktopSetup_x64.exe.
