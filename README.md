------------------------------------------------
Developer Notes:
 ------------------------------------------------
<br> *Limited experience with AWS/Python integration
<br> *Limited experience with Parquet 
 <br>*Was able to test with SQL server
<br> *Was not able to test functionality with AWS



------------------------------------------------
AWS S3 CONFIGURATION REQUIREMENTS
------------------------------------------------
<br>S3 Configuration:

<br>Bucket Name = "SpaceX_data"
<br>Region  = "US East"
<br>Access Key= "AKIAIOSFODNN7EXAMPLE"
<br>Secret Access Key = "wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY"


<br>Python Compatability Components: 
<br>boto3==1.18.59
<br>aiohttp==3.8.1

<br>Permissions: 
<br>s3:PutObject
<br>s3:GetObject
<br>s3:ListBucket

------------------------------------------------
MS SQL CONFIGURATION REQUIREMENTS
------------------------------------------------
<br>Min Compatibility: SQL Server 2022 (160)
<br>Allow Remote Connections -YES
<br>Max Query timeout

<br>Min Server: SQL 2022DEV 
<br>Server Name: BZPC\SQL2022DEV
<br>Database Name: SpaceX


<br>Authentication/SQL Account Configuration:
<br>SQL Server Authentication
<br>SQL Username: SQLUser_SpaceX
<br>SQL Password: SQLSpaceX

<br>Server Role: Public

<br>Mapping: 
<br>DB Name: Space X
<br>Role: db_owner
<br>Schema: dbo
<br>Default DB: Space X


<br>Python Compatability Components: 
<br>PyODBC

------------------------------------------------
Other Python Requirements
------------------------------------------------
<br> Python Version: 3.12.2
<br> Libraries:
<br> import os
<br> aiohttp
<br> pandas 
<br> parquet
<br> prefect
