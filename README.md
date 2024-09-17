# NIT3213-Assessment_2
                   README.md
      NIT3213 Final Assignment               ____Nobir Hossain/s4684083___

Project Overview:
This Android application demonstrates proficiency in API integration, user interface design, and Android development best practices. The app consists of three screens: Login, Dashboard, and Details. It interacts with the 'vu-nit3213-api' to authenticate users and retrieve data for display.
Requirements:

1. Login Screen: Allows users to log in using their first name as the username and student ID (s12345678 format) as the password.

2. Dashboard Screen: Displays a list of entities retrieved from the API using a RecyclerView.

3. Details Screen: Shows detailed information about the selected entity.

Installation:

1. Clone the repository:

    git clone <repository-link>

2. Open the project in Android Studio.

3. Sync Gradle to download dependencies.

4. Run the project on an emulator or physical device.

API Integration:

This application interacts with the 'vu-nit3213-api' to authenticate users and fetch data for the dashboard. The API endpoints used are:

1. **Login Endpoint:** Authenticates users based on their location (Foostcray, Sydney, or ORT).

2. **Dashboard Endpoint:** Retrieves a list of entities based on the user's login response (keypass).


Technical Details:

- **Dependency Injection:** Implemented using Hilt or Koin.

- **Unit Tests:** Unit tests are written for ViewModel components to ensure business logic correctness.

- **RecyclerView:** Used to display a list of entities in the Dashboard screen.

How to Run Tests:

To run unit tests:
1. Open Android Studio.

2. Navigate to the test package.

3. Right-click and select 'Run Tests'.

Project Structure:

- **Login Screen:** Handles user authentication.

- **Dashboard Screen:** Displays a list of entities from the API.

- **Details Screen:** Shows detailed information about the selected entity.

Git Usage:

- Commit your changes regularly with meaningful messages.

- Use branching to work on new features or bug fixes.

License:
This project is non-licensed 
