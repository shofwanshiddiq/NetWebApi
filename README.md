# ASP.NET WEB API for User login and Employees Data Management
This is a .NET Web Application projects features user data login management with bearer token authentication & authorization using Entity Frameworks Core Identity and CRUD operation for employees data management. Utilizing .NET Entity Frameworks for integration with Microsoft SQL Server. Utilize Swagger for web api deployment.

### Features
* Register & Login with JWT Token
* User Email Confirmation
* Forgot & Reset Password
* Confirm & Resend Confirmation Email
* Create, Update, Get, & Delete Employee Data

### Technologies
![.NET Web API](https://img.shields.io/badge/.NET_Web_API-%230078D4.svg?style=for-the-badge&logo=.net&logoColor=white)  ![REST API](https://img.shields.io/badge/REST_API-%23000000.svg?style=for-the-badge&logo=swagger&logoColor=white)  ![SQL Server](https://img.shields.io/badge/SQL_Server-%23007A92.svg?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)  ![Swagger](https://img.shields.io/badge/Swagger-%2385EA2D.svg?style=for-the-badge&logo=swagger&logoColor=black)  

### Version
* .NET 8
* Entity Frameworks 6
* Entity Framework Core Identity 8.0.4
* Entity Framework Core Tools 9.0.3
* Visual Studio 2019
* Microsoft SQL Server 2019

## API Endpoints Documentation

| Method     | API Endpoint               | Description                                      |
|------------|----------------------------|--------------------------------------------------|
| **POST**   | `/register`            | Create a new user                                |
| **POST**   | `/login`            | Login user                              |
| **POST**   | `/refresh`            | Refresh token                              |
| **GET**   | `/confirmEmail`            | Email confirmation                             |
| **POST**   | `/resendConfirmationEmail`            | Resend email confirmation                             |
| **POST**   | `/forgotPassword`            | Request reset password because forgot password                            |
| **POST**   | `/resetPassword`            | Reset password                           |
| **GET**   | `/api/Employees`            | Get all employees data                           |
| **POST**   | `/api/Employees`            | Add employee data                           |
| **GET**   | `/api/Employees/{id}`            | Get specific employee using ID                        |
| **PUT**   | `/api/Employees/{id}`            | Update specific employee data using ID                        |
| **DELETE**   | `/api/Employees/{id}`            | Delete specific employee data using ID                        |
