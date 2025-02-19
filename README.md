# Library App

## Description

Library App is a console application designed to manage a library system. It allows users to manage patrons, books, and loans, providing functionalities such as searching for patrons, extending loans, and returning books.

## Project Structure

- AccelerateDevGitHubCopilot.sln
- README.md
- src/
  - Library.ApplicationCore/
    - Entities/
    - Enums/
    - Interfaces/
    - Library.ApplicationCore.csproj
    - Services/
  - Library.Console/
    - appSettings.json
    - CommonActions.cs
    - ConsoleApp.cs
    - ConsoleState.cs
    - Json/
    - Library.Console.csproj
    - Program.cs
  - Library.Infrastructure/
    - Data/
    - Library.Infrastructure.csproj
- tests/
  - UnitTests/
    - ApplicationCore/
    - UnitTests.csproj

## Key Classes and Interfaces

- **Library.ApplicationCore**

  - **Entities**
    - Contains the core entities such as `Book`, `Patron`, and `Loan`.
  - **Enums**
    - Defines various enums used across the application.
  - **Interfaces**
    - Contains interfaces for repository and service abstractions.
  - **Services**
    - Implements the business logic for managing library operations.

- **Library.Console**

  - **ConsoleApp**
    - The main class that handles user interactions and application flow.
  - **CommonActions**
    - Defines common actions that users can perform in the console application.
  - **ConsoleState**
    - Manages the state transitions within the console application.

- **Library.Infrastructure**
  - **Data**
    - Implements data access logic and repository patterns.

## Usage

1. Clone the repository.
2. Open the solution file `AccelerateDevGitHubCopilot.sln` in Visual Studio.
3. Build the solution to restore dependencies and compile the code.
4. Run the `Library.Console` project to start the console application.
5. Follow the on-screen instructions to interact with the library system.

## License

This project is licensed under the MIT License.
