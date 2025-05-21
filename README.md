# Intramural Sports Application

Welcome to the Intramural Sports Application project! This application is designed to facilitate intramural sports activities, allowing users to create, manage, and participate in various sports events.

## Project Structure

The project is divided into two main parts: the backend and the frontend.

### Backend

The backend is built using C# and ASP.NET Core. It handles the business logic, data management, and API endpoints for the application.

- **IntramuralSportsApi.sln**: Solution file that organizes the backend project and its dependencies.
- **Controllers**: Contains controller classes that manage incoming HTTP requests and responses.
- **Models**: Contains model classes that represent the data structures used in the application.
- **Services**: Contains service classes that encapsulate the business logic of the application.
- **Program.cs**: Entry point of the application, configuring and running the web host.
- **Startup.cs**: Configures services and the app's request pipeline.
- **appsettings.json**: Configuration settings for the application, including connection strings.

### Frontend

The frontend is built using React, HTML, CSS, and JavaScript. It provides a user-friendly interface for interacting with the backend.

- **public/index.html**: Main HTML file serving as the entry point for the React application.
- **src/components**: Contains reusable React components.
- **src/pages**: Contains React components representing different pages of the application.
- **src/App.js**: Main component that sets up routing and renders the application structure.
- **src/index.js**: Entry point for the React application, rendering the App component into the DOM.
- **src/firebase.js**: Initializes and configures Firebase for authentication and database services.
- **src/styles/App.css**: CSS styles for the React application.
- **package.json**: Configuration file for npm, listing dependencies and scripts.
