# Blazor-JWT-Windows-Auth

This repository demonstrates authentication and authorization in a Blazor WebAssembly application using a custom Authentication State Provider. It integrates both Windows Authentication and JWT (JSON Web Token) for secure and flexible user authentication.

## Features

- **Blazor WebAssembly**: Front-end application built with Blazor WebAssembly.
- **Custom AuthenticationStateProvider**: Manages authentication state across the app.
- **Windows Authentication**: Uses Windows Authentication for internal/extranet apps.
- **JWT Authentication**: Integrates JWT for APIs or services requiring token-based authentication.
- **Secure API Calls**: Authentication tokens are securely passed to the API endpoints.
- **Role-based Authorization**: Access is restricted based on user roles.

## Project Structure

- **Client**: Contains the Blazor WebAssembly front-end.
- **Server**: Provides API endpoints and handles JWT generation and validation.
- **Shared**: Common models and services used by both the client and server.

## Prerequisites

- [.NET 6 SDK](https://dotnet.microsoft.com/download/dotnet/6.0)
- Visual Studio 2022 or Visual Studio Code
- [SQL Server](https://www.microsoft.com/en-us/sql-server) (if applicable)

## Getting Started

1. **Clone the repository**:

   ```bash
   git clone https://github.com/MarvynHarry/Blazor-JWT-Windows-Auth.git
   cd Blazor-JWT-Windows-Auth

2. **Update AppSettings**:
  
     - Navigate to Server/appsettings.json.
     - Set the connection string for the database (if using a database) and configure JWT options.

 3. **Restore Dependencies**:

    ```bash
    dotnet restore
   
 4. **Run the Application**:
    
      ```bash
      dotnet run --project Server
      ```

 5. **Access the Application: Open a browser and navigate to https://localhost:5001.**

## Support My Work
If you enjoy my work or want to support what I do, feel free to [Buy Me a Coffee](https://buymeacoffee.com/marvynharry)!

## Contributing
Feel free to submit a pull request or report issues to help improve the project!

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
