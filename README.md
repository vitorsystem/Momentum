# Momentum - Financial Tools Web App

<p align="center">
  <img src="https://img.shields.io/badge/status-in%20development-orange?style=for-the-badge">
  <br>
  <a href="https://dotnet.microsoft.com/en-us/" target="_blank"><img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"></a>
  <a href="https://dotnet.microsoft.com/en-us/languages/csharp" target="_blank"><img src="https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white"></a>
  <a href="https://dotnet.microsoft.com/en-us/apps/aspnet/web-apps/blazor" target="_blank"><img src="https://img.shields.io/badge/blazor-%23512BD4.svg?style=for-the-badge&logo=blazor&logoColor=white"></a>
</p>

An interactive web application built with C# and Blazor Server to provide intuitive tools for financial simulation and long-term investment planning.

---

### Demo
![Momentum_MVP](https://github.com/user-attachments/assets/6be1ec21-76dd-4033-a191-dca5c59bfc01)

---

### 📖 About The Project

Momentum started as a project to deepen my understanding of the .NET ecosystem and build a practical, real-world application. The goal is to create a suite of clean, interactive, and useful tools that help visualize the power of long-term investing and other financial concepts.

The application is built using a modern .NET stack, focusing on a responsive user interface and solid back-end logic.

### ✨ Key Features

* **Real-time Compound Interest Calculator:**
    * Instantly see results update as you type.
    * Calculates projections based on initial amount, monthly contributions, annual interest rate, and time period.
    * Clear and formatted display of the final balance, total amount invested, and total interest earned.

### 🛠️ Tech Stack

* **.NET 9**
* **C#**
* **ASP.NET Core**
* **Blazor Server** (for the interactive UI and server-side rendering)
* **HTML5 / CSS3** (with Bootstrap for layout)
* **Git & GitHub** (for version control)

---

### 🚀 Getting Started

To run this project locally, follow these steps:

```bash
# 1. Clone the repository
git clone https://github.com/vitorsystem/Momentum.git
# 2. Navigate to the solution's root folder
cd Momentum

# 3. Run the web application
# The --project flag specifies which project to run within the solution
dotnet run --project Momentum.WebApp
```
The application will be available at `https://localhost:XXXX` or `http://localhost:YYYY` in your browser.

---

### 🗺️ Project Roadmap

This project is actively under development. Here are the next planned features:

- ✅ **MVP: Real-time Compound Interest Calculator** *(Done)*
- ➡️ **Detailed Month-by-Month Evolution Table** *(In Progress)*
- 🔲 **Interactive Growth Chart (using Chart.js)** *(Up Next)*
- 🔲 **Language/Currency Switcher (EN/US <-> PT/BR)** *(Future)*
- 🔲 **New Financial Tools** *(Future)*
- 🔲 **Deploy with Microsoft Azure** *(Future)*
