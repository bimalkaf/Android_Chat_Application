# Firebase Chat App

Welcome to the Firebase Chat App repository! This app enables real-time chat functionality using Firebase as the backend. Below is a list of key files and their functionalities:

## Activity Files

- `ChatActivity.java`: The main activity for individual chat conversations.
- `LoginOtpActivity.java`: Handles user authentication using OTP.
- `LoginPhoneNumberActivity.java`: Manages phone number-based user login.
- `LoginUsernameActivity.java`: Controls user login using a username.
- `MainActivity.java`: The app's entry point and primary navigation hub.
- `SearchUserActivity.java`: Allows users to search for other users to initiate chats.
- `SplashActivity.java`: Displays a splash screen while the app initializes.

## Fragment Files

- `ChatFragment.java`: Manages chat UI and logic within the chat activity.
- `ProfileFragment.java`: Handles user profile display and editing.
- `SearchUserFragment.java`: Displays user search results and options for starting a chat.

## Service File

- `FCMNotificationService.java`: Integrates Firebase Cloud Messaging for push notifications.

Feel free to explore these files to understand the structure of the app and how different components interact. The app leverages Firebase Authentication, Realtime Database, and Firebase Cloud Messaging to provide seamless chat functionality.

## Getting Started

To use this app:

1. Clone or download the repository.
2. Set up your Firebase project and update the `google-services.json` file.
3. Build and run the app on your Android device or emulator.

## Notes

- This repository provides a basic structure for a Firebase-based chat app. You can extend and customize it as per your requirements.
- Make sure to handle security and privacy aspects when implementing user authentication and chat features.

For more details about Firebase services and Android app development, refer to the official [Firebase Documentation](https://firebase.google.com/docs) and [Android Documentation](https://developer.android.com/docs).

Happy coding!
