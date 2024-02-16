###################################################
Developer Notes:
 *Limited experience with AWS/Python integration
 *Limited experience with Parquet 
 *Was able to test with SQL server
 *Was not able to test functionality with AWS
####################################################


------------------------------------------------
AWS S3 CONFIGURATION REQUIREMENTS
------------------------------------------------
S3 Configuration:

Bucket Name = "SpaceX_data"
Region  = "US East"
Access Key= "AKIAIOSFODNN7EXAMPLE"
Secret Access Key = "wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY"


Python Compatability Components: 
boto3==1.18.59
aiohttp==3.8.1

Permissions: 
s3:PutObject
s3:GetObject
s3:ListBucket

------------------------------------------------
MS SQL CONFIGURATION REQUIREMENTS
------------------------------------------------
Min Compatibility: SQL Server 2022 (160)
Allow Remote Connections -YES
Max Query timeout

Min Server: SQL 2022DEV 
Server Name: BZPC\SQL2022DEV
Database Name: SpaceX


Authentication/SQL Account Configuration:
SQL Server Authentication
SQL Username: SQLUser_SpaceX
SQL Password: SQLSpaceX

Server Role: Public

Mapping: 
DB Name: Space X
Role: db_owner
Schema: dbo
Default DB: Space X

