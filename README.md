# 🔐 Authentication API — ASP.NET Core .NET 8

A secure and scalable RESTful Authentication API built using **C# and ASP.NET Core .NET 8**.

This project provides user registration and login functionality with **Gmail email validation, password validation, BCrypt password hashing, JWT-based authentication, Entity Framework Core, and Microsoft SQL Server**.

---

## 🚀 Features

- 👤 User Registration
- 🔑 User Login
- 📧 Gmail Email Validation
- 📝 Name Validation
- 🔒 Password Validation
- 🔐 BCrypt Password Hashing
- 🎫 JWT Authentication
- 🗄️ Entity Framework Core
- 💾 Microsoft SQL Server
- 📚 Swagger / OpenAPI
- 🔄 Entity Framework Core Migrations
- 🕐 India Standard Time (IST) Support
- 🛡️ Secure API Authentication

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **C#** | Backend programming language |
| **ASP.NET Core .NET 8** | REST API framework |
| **Entity Framework Core** | ORM and database operations |
| **Microsoft SQL Server** | Relational database |
| **BCrypt** | Secure password hashing |
| **JWT** | Authentication and authorization |
| **Swagger / OpenAPI** | API documentation and testing |
| **Visual Studio** | Development environment |

---

## 📂 Project Structure

```text
Authentication/
│
├── Controllers/
│   └── AuthController.cs
│
├── Data/
│   └── AppDbContext.cs
│
├── DTOs/
│   ├── LoginDto.cs
│   └── RegisterDto.cs
│
├── Helpers/
│   └── IndiaTimeHelper.cs
│
├── Models/
│   └── User.cs
│
├── Program.cs
├── appsettings.json
└── Authentication.csproj
