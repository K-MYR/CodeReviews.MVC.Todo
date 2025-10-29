# :clipboard: CodeReviews.MVC.Todo

**To-Do List Application (ASP.NET Core MVC)**  
3rd ASP.NET Core MVC project developed as part of the [C# Academy](https://www.thecsharpacademy.com/) curriculum.  
**Goal:** Build a full-stack MVC app with controllers and a simple, functional front-end using vanilla JavaScript and API calls.

---

## :clipboard: Requirements

:heavy_check_mark: This is an application where you should manage a todo list. \
:heavy_check_mark: Users should be able to Add, Delete, Update and Read from a database, using a SPA (single-page application). The user should never be redirected to a new page. \
:heavy_check_mark: You need to write a minimal API to connect the front-end and database.\
:heavy_check_mark: You need to use the JS Fetch API from your front-end to call your minimal API in the backend.\
:heavy_check_mark: You need to use Entity Framework, raw SQL isn't allowed.\
:heavy_check_mark: You don't need a navigation bar. No menu is necessary since you'll only have one page.\
:heavy_check_mark: Once you execute any operation, the todo-list needs to be automatically updated accordingly. \
:heavy_check_mark: Your data model is only one table with to-dos. You. might be tempted to create more complex data-models (categories of todos for example) but avoid that for now. We're focusing on the front-end. \
:heavy_check_mark: You need to add validation. For example, empty input shouldn't be allowed. Feel free to add more validations as you see fit. \

---

## :bookmark_tabs: Project Description

This project is a **functional To-Do List app** that lets users manage tasks efficiently.  

Key features include:

- Tasks displayed in a **simple pinboard-style layout**  
- Smooth, minimal animations for adding, editing, and deleting tasks  
- **Fetch API** for asynchronous updates via MVC controllers  
- Modals for CRUD operations without full page reloads  

The focus of this project was on **backend MVC logic** and **dynamic task handling**, with a simple but functional front-end.

---

## :gear: Technologies & Architecture

- **ASP.NET Core MVC (C#)** for controllers, routing, and backend logic  
- **Entity Framework Core** for database access  
- **SQL Server** for data storage  
- **Vanilla JavaScript** with **Fetch API** for asynchronous interactions  
- **Bootstrap / CSS** for simple layout, styling, and subtle animations  

---

## :rocket: Getting Started

### Installation Steps

1. Restore NuGet packages.  
2. Configure your SQL Server connection string in `appsettings.json`.  
3. Run the application.

:bulb: You can disable automatic migration and data seeding in `appsettings.json`.
