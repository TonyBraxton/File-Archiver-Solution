# File Archiver Solution
 A solution for automated file movement and archiving that enhances management
# Project Name

## Description
This project automates file archiving for clientT and clientB using C# and SSIS. It contains two packages with one script per package.
It involves:
- Moving and archiving files from D:\Incoming_Files\Archive to a Network Drive
- Dynamically creating date-based folders
- Move the files from source to destination folder
- Deleting processed files from the D drive(source folder)
- Zipping dateBased folders to save space
- Parameterizing the network drive path in SSIS
- Deploying the SSIS package on SQL Server
- Integrating it into the clientB and clientT daily job workflow

## Technologies Used
- C#
- SSIS
- SQL Server

## Pupose:
It was deployed on an SQL server.
A job agent was created on the SQL server and the jobs set to run on the scheduled routine to manage incoming files from the clients introduced above.
