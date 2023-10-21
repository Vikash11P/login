# login

A new Flutter project.

## Getting Started
main.dart » This is the first function executed when you run your flutter app
wrapper.dart » This will handle to show the home page if a user is already authenticated or call handler.dart for an unauthenticated user.
handler.dart » This file contains a function that will handle if the user wants to show login or registration screen or UI.
firebaseuser.dart » This is a property that will be used on mapping Firebase User during authentication.
loginuser.dart » This model property is used to map record from the user credential in the login and registration form
login.dart » login UI or screens that will be shown on the user side
register.dart » register UI or screen that will be shown on the user side
home.dart » dummy page to show after successful authentication
auth.dart » contains Firebase Method for sign-in, sign-out, and registration. This is where all the firebase integration will be placed
This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
