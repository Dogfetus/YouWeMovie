# YouWeMovie Project

## Overview

This repository contains the codebase and related documentation for the **YouWeMovie** project, developed as part of the **IKT201 - Internet Services** course. The primary goal of this project is to create a user-friendly platform for reviewing and exploring movies and series. Inspired by platforms like IMDb and Rotten Tomatoes, YouWeMovie is designed to enhance user interaction and simplify the review process while providing a personalized user experience.

---

## Features

The platform offers the following features:

- **User Registration and Authentication**: Users can register, log in, and manage their accounts.
- **Movie and Series Reviews**: Users can write reviews, rate movies/series, and explore reviews by others.
- **Personalized Lists**: Registered users can create and manage personalized lists of their favorite movies and series.
- **Search and Filter**: A powerful search bar and filtering options to explore content easily.
- **Responsive Design**: Designed to work seamlessly on various screen sizes and devices.
- **Secure Data Management**: Ensures secure handling of user data, including password hashing.

---

## Technical Details

- **Framework**: The platform is built using **ASP.NET Core 7.0** with a focus on modular design.
- **Languages**: Primarily developed in C#, HTML, CSS, and JavaScript.
- **Database**: Uses MySQL for managing user data and reviews.
- **Architecture**: Follows the Model-View-Controller (MVC) pattern for scalability and maintainability.
- **Version Control**: Managed with Git and hosted on Bitbucket for team collaboration.

---

## Repository Structure

The repository is organized as follows:

```
├── frontend               # Frontend codebase for the platform
├── backend                # Backend logic and API handling
├── database               # Database schemas and related files
├── docs                   # Project documentation
├── tests                  # Testing scripts and resources
├── LICENSE                # License information
└── README.md              # Project overview
```

---

## Getting Started

### Prerequisites
- .NET Core SDK
- MySQL Server
- Git for version control

### Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/Dogfetus/YouWeMovie.git
   ```
2. Set up the database:
   - Import the provided schema from the `database` folder.
3. Configure the application:
   - Update the connection string in the `appsettings.json` file to match your database setup.
4. Build and run the application:
   ```bash
   dotnet build
   dotnet run
   ```

---

## Contributors

This project was developed by Group 1 for the IKT201 course at the **University of Agder**:

- Linor Ujkani
- Sander Wesstøl
- Habteab Teame
- Luka Vulovic
- Erlend Tregde

---

## Acknowledgments

Special thanks to **Christian Auby**, our course instructor, for guidance throughout the project.
# YouWeMovie
