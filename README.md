# 🎬 MoviesWEBAPP

A simple **ASP.NET Core MVC / Web App** built in .NET  for managing movies. The application follows a typical Model‑View‑Controller structure and demonstrates basic CRUD operations on movie-related data.

## Description

This project is a .NET-based **movie management web application**. It allows users to view, add, edit, and delete movies. Built using **ASP.NET Core MVC**, it follows the standard .NET project layout and utilizes Razor views for rendering the UI. Typical components include:

- **Controllers** – handle incoming requests and interactions.  
- **Models** – define movie and related domain entities.  
- **Views** – present HTML UI pages for listing movies and movie details.  
- **Data Access** – implemented with **Entity Framework Core**.  
- **Static Assets** – CSS/JS in `wwwroot/` for styling and client-side interactivity.  

## Features

- Browse a list of movies  
- View details for a specific movie  
- Create a new movie entry  
- Edit an existing movie  
- Delete a movie  
- Typical CRUD functionality implemented in .NET MVC  
- Razor pages for UI views  

## Tech Stack

- **ASP.NET Core** (MVC pattern)  
- **C#**  
- **Entity Framework Core** (for data persistence)  
- **Razor Views** for server-side HTML templates  
- **SQL Database** (likely SQL Server via EF migrations)  
- **Static assets** in `wwwroot/` for front-end resources  

## Project Setup

1. **Clone the repo:**
   ```bash
   git clone https://github.com/emnagrajaa/Movies.git
2. **Restore dependencies::**
   ```bash
   dotnet restore
3. **Create/update the database (if migrations exist):**
   ```bash
   dotnet ef database update
4. **Run the app:**
   ```bash
   dotnet run



