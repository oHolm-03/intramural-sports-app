# Intramural Sports API

This is the backend portion of the Intramural Sports application, built using C#. The backend is responsible for handling data management, business logic, and serving API endpoints for the frontend application.

## Project Structure

- **IntramuralSportsApi.sln**: Solution file that organizes the project and its dependencies.
- **Controllers/**: Contains controller classes that handle incoming HTTP requests and return responses.
- **Models/**: Contains model classes that represent the data structures used in the application.
- **Services/**: Contains service classes that encapsulate the business logic of the application.
- **Program.cs**: Entry point of the C# application. Configures and runs the web host.
- **Startup.cs**: Configures services and the app's request pipeline.
- **appsettings.json**: Contains configuration settings for the application, such as connection strings and application settings.

## Getting Started

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the backend directory:
   ```
   cd intramural-sports-app/backend
   ```

3. Restore the dependencies:
   ```
   dotnet restore
   ```

4. Run the application:
   ```
   dotnet run
   ```

## API Endpoints

Documentation for the available API endpoints will be provided in the respective controller files.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.

## License

This project is licensed under the MIT License - see the LICENSE file for details.