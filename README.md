Sure, here is a sample README file for your ASP.NET Core MVC Frontend and .NET API projects:

---

# Project Title

The Are 2 resipitory:

1. [Frontend MVC](https://github.com/tumi94/Front_End)
2. [Backend API](https://github.com/tumi94/Back_End)

## Getting Started

These instructions will help you set up the project on your local machine for development and testing purposes.

### Prerequisites

- .NET 7 SDK
- Visual Studio 2022
- SQL Server Management Studio (SSMS)

### Installation

1. **Clone the repositories**

Clone both the repositories to your local machine using the following commands:

```bash
git clone https://github.com/tumi94/Front_End.git
git clone https://github.com/tumi94/Back_End.git
```

2. **Open the projects in Visual Studio**

Open both solutions in Visual Studio 2022.

3. **Restore NuGet Packages**

In Visual Studio, right-click on the solution and select "Restore NuGet Packages".

4. **Update the Database Connection String**

In the `appsettings.json` file of the backend project, update the connection string to point to your local SQL Server instance.

5. **Create the Database**

Open SQL Server Management Studio (SSMS) and load the `Task.mdf` database located in the backend project or Open Package Manager Console.

Run the following commands:
Update-Database
This will apply the migrations and create the database.

6. **Run the Projects**

In Visual Studio, press `F5` or click on the `IIS Express` button to run the projects.

The frontend project should now be running on `https://localhost:7099/` and the backend API should be running on `https://localhost:7215/api/tasks`.

