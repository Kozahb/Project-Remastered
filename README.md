<h1 align="center">🧩 MVC Project in .NET 8 and Entity Framework</h1>
<p align="center">
  Development of a complete web system following the MVC architecture, using .NET 8.0 and Entity Framework Core for data persistence.
</p>

---

## ✨ About the Project

This project aims to demonstrate the development of a full-featured web system using **.NET 8**, **ASP.NET Core MVC**, and **Entity Framework Core**. It includes key features such as:

- ✅ Authentication system (Login & Register)
- 🧩 CRUD operations for data entities
- 💾 Data management via **Entity Framework Core**
- 🚀 Git for version control
- 🛠️ Clean and scalable MVC structure

---

## ⚙️ Technologies Used

- **Language:** C#
- **Framework:** .NET 8.0 / ASP.NET Core MVC
- **ORM:** Entity Framework Core
- **Database:** SQL Server
- **Authentication:** ASP.NET Identity
- **IDE:** Visual Studio 2022
- **Version Control:** Git + GitHub

---

## 📁 Project Structure

/Controllers └── AuthController.cs └── UsuarioController.cs /Models └── Usuario.cs /Views └── Shared └── Auth └── Usuario /Data └── ApplicationDbContext.cs

---

## 🔐 Authentication

The project includes a basic authentication system using **ASP.NET Core Identity**, allowing users to register, log in, and manage sessions securely.

---

## 🔄 CRUD Operations

Fully implemented Create, Read, Update, and Delete operations for user management or other entities, with validation and feedback to the user.

---

## 🚧 CI/CD Pipeline (Planned)

Plans for CI/CD using **GitHub Actions**:
- ✅ Build and test automation
- 🔄 Continuous integration with pull requests

---

## 🚀 Running the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Kozahb/Project-Remastered.git
   cd Project-Remastered
Set up your connection string in appsettings.json.

Run database migration:

dotnet ef database update
Start the project:

dotnet run

👨‍💻 Author
 by Thaleson Eduardo 👽

<p align="center"> <a href="https://github.com/Kozahb" target="_blank"> <img src="https://img.shields.io/github/followers/Kozahb?label=Follow&style=social" alt="GitHub Followers"> </a> </p> ```
