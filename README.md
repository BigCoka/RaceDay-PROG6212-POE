RaceDay Event Management System

PROG6212 — POE Part 3

RaceDay is a web-based event management system developed using C# and ASP.NET Core. The application allows participants to discover racing events and organisers to manage their events.

Technologies Used

- C# and .NET 8
- ASP.NET Core MVC
- ASP.NET Core Web API
- Entity Framework Core
- Microsoft SQL Server
- Azure Blob Storage
- Visual Studio 2022

Main Features

Participant Features
- Register and log in to the application.
- Browse available racing events.
- Search for events by name or location.
- View event details and categories.
- Register for racing events.

### Organiser Features
- Log in as an organiser.
- Create and manage racing events.
- Manage event categories.
- Upload event images using Azure Blob Storage.

Project Structure
RaceDayAPI: Handles API requests, database operations and application logic.

RaceDayMVC: Provides the user interface for participants and organisers.

How to Run the Project

1. Download and extract the RaceDay solution.
2. Open the solution in Visual Studio 2022.
3. Restore the required NuGet packages.
4. Configure SQL Server and the database connection.
5. Configure the required Azure Blob Storage credentials securely.
6. Set RaceDayAPI and RaceDayMVC as multiple startup projects.
7. Run both projects using HTTPS.
8. Open the RaceDay website in your browser.

Testing

The application should be tested for participant login, event browsing, race registration, organiser functionality, API connectivity and database operations.

Academic Information

Module: PROG6212  
Assessment: Portfolio of Evidence — Part 3  
Project: RaceDay Event Management System

## Project Purpose

The purpose of RaceDay is to provide a convenient platform for participants to discover racing events while allowing organisers to manage their events efficiently.
