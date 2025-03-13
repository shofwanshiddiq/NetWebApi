# ASP.NET WEB API for User login and Employees Data Management
This is a .NET Web Application projects using .NET 8 features user data login management with bearer token authentication & authorization using Entity Frameworks Core Identity and CRUD operation for employees data management. Utilizing .NET Entity Frameworks for integration with Microsoft SQL Server. Utilize Swagger for web api deployment.

### Features
* Register & Login with Bearer Token Authentication
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
* Visual Studio 2022
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


# Getting Started

Follow these steps to set up the project:

### 1. Download Repositories
* Navigate to Directory
```bash
cd /path/to/your/directory
```
* Clone Repositories
```bash
git clone https://github.com/shofwanshiddiq/NetWebApi
```

### 2. Open the Project in Visual Studio
* Select NetWebApi.sln > Open

### 3. Set Up Connection
* Go to file Web.config > Find tag <connectionString> > change all the data-source in every item to your local server

### 4. Run the Project
* Click on NewWebApi in Solution Explorer > Rebuild
* Start the Project on IIS Express(Google Chrome)

# Gallery

<img src="https://github.com/user-attachments/assets/4fcafea1-264d-43c7-ac02-feca386e700a" alt="Image 1" style="width: 400px;">
<img src="https://github.com/user-attachments/assets/5cfdd030-e07e-4ada-ae9b-d98a33c97956" alt="Image 2" style="width: 400px;">
<img src="https://github.com/user-attachments/assets/6a3dc477-c1ab-446a-b846-164cfd72550e" alt="Image 3" style="width: 400px;">
<img src="https://github.com/user-attachments/assets/ea3842f5-714c-4eba-83d3-7610975fbbc8" alt="Image 4" style="width: 400px;">
<img src="https://github.com/user-attachments/assets/9512f98f-5e49-412d-84a8-92e5009035d4" alt="Image 5" style="width: 400px;">



