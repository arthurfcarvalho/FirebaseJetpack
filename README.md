# FirebaseJetpack

FirebaseJetpack is a mobile application developed as part of an academic project for the 6th semester of the **ADS (Analysis and Systems Development)** course. The app demonstrates the implementation of a user authentication system using **Firebase Authentication** and features a modern, responsive interface built with **Jetpack Compose**.

## Features

- **User Registration:** Users can sign up with their email and password.
- **Login:** Existing users can log in with their credentials.
- **Welcome Screen:** Displays a personalized welcome message with the user's email.
- **Logout Functionality:** Users can log out and return to the login screen.

## Technologies Used

- **Kotlin:** Programming language for Android development.
- **Jetpack Compose:** Modern declarative UI toolkit for building native interfaces.
- **Firebase Authentication:** Secure and efficient user management.
- **Android Studio:** IDE for Android application development.

## Screenshots

### Authentication Screen

- Fields for email and password input.
- Buttons for "Login" and "Register."

### Welcome Screen

- Displays the user's email.
- Includes a "Logout" button.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/arthurfcarvalho/firebasejetpack.git
2. Open the project in Android Studio.
3. Ensure you have the required SDKs and tools installed:
    Compile SDK: 35
    Min SDK: 21
4. Configure Firebase:
    Add your google-services.json file to the app/ directory.
    Enable Email/Password Authentication in the Firebase Console.
5. Build and run the application on an emulator or physical device.

## How It Works

1. **User Authentication:**
   - Users register or log in with their email and password.
   - Firebase Authentication securely manages user accounts.

2. **Welcome Screen:**
   - Upon successful login, users are redirected to a welcome screen displaying their email.

3. **Logout:**
   - Users can log out, returning to the login screen.

## Academic Context

This project was developed for the **6th semester of the Analysis and Systems Development (ADS)** course. It showcases practical knowledge of Android development, Firebase integration, and Jetpack Compose.
