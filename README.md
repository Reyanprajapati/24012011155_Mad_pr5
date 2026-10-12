Practical 5 – Login and Registration App
Submitted By: Reyan Prajapati
Enrollment Number: 24012011155
Subject: Mobile Application Development (MAD)
Aim
Create an Android application with Login and Registration screens using Jetpack Compose.
Overview
This practical demonstrates building a simple login and registration interface in an Android application using Kotlin and Jetpack Compose. The screens use Material 3 components and Jetpack Navigation to move between Login and Registration.
Features
- Login screen with email and password fields.
- Password masking using PasswordVisualTransformation.
- Forgot Password message using a Toast notification.
- Registration screen with name, phone number, city, email, password, and confirm-password fields.
- Email format validation on the registration screen.
- Validation that all registration fields are filled in.
- Password and confirm-password matching check.
- Navigation between Login and Registration screens.
- GUNI logo displayed on both screens.
- Material 3 UI components, rounded cards, buttons, and text fields.
Project Structure
File	Description
MainActivity.kt	Sets up the Compose content and app theme.
LoginPage.kt	Displays the login form and handles basic login-field validation.
RegisterPage.kt	Displays the registration form and validates the entered details.
AppNavigation.kt	Defines navigation routes for Login and Registration.
ui/theme/	Contains the app theme and colors, including GuniPink.
res/drawable/guni_pink_logo	Logo image used on both screens.


Technologies Used
- Kotlin
- Android Studio
- Jetpack Compose
- Material 3
- Jetpack Navigation Compose
Validation Behaviour
Login Screen
- If email or password is empty, the app displays “Please fill all fields”.
- If both fields are entered, the app displays “Login Successful”.
- Selecting SIGN UP navigates to the Registration screen.
Registration Screen
- All fields are required.
- The email address is checked using Android's Patterns.EMAIL_ADDRESS matcher.
- The password and confirm-password values must match.
- A successful validation displays “Registration Successful”.
- Selecting LOGIN returns to the Login screen.
Note: The code provided for this practical demonstrates interface and input validation. It does not implement actual account authentication, remote storage, or saving registered users to a database.

How to Run
1. Open the project in Android Studio.
2. Ensure the project has the required Jetpack Compose, Material 3, and Navigation Compose dependencies.
3. Confirm that the guni_pink_logo drawable resource exists in res/drawable.
4. Sync the project with Gradle.
5. Run the app on an Android emulator or connected device.
6. Test the Login and Registration screens and their validation messages.
Author
Reyan Prajapati
Enrollment Number: 24012011155
