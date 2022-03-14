# Deploying an SQL Database Automatically using Azure DevOps CI/CD

This readme file explains all the processes I employed in automating a CI/CD  workflow using Azure DevOps CI/CD pipelines

<br/>


## Requirements

1. GIT
2. Visual Studio
3. Microsoft SQL Server Management studio
4. Azure DevOps account

## Process Flow Chat

1. Download a sample Adventure database from Microsoft website.
2. Restore database using Microsoft SQL server management studio.
3. Create dacpac file using the restored database
4. Create a new SQL project in Visual Studio and import the dacpac file.
5. Push the SQL project to azure DevOps repo.
6. Create an SQL database application on azure
7. Create a CI/CD pipeline from the recently pushed repo.
8. Create a release pipeline and add Azure SQL dacpac task to push the SQL database created to azure.
