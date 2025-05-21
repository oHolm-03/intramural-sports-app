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

## Getting Started

To get started with the Intramural Sports Application, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the `backend` directory and restore the dependencies using your preferred method.
3. Run the backend application.
4. Navigate to the `frontend` directory and install the dependencies using `npm install`.
5. Start the frontend application using `npm start`.

## Contributing

Contributions are welcome! If you would like to contribute to the project, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgments

Thank you for your interest in the Intramural Sports Application! We hope you find it useful and enjoyable.