# Notification App

The Notification App is an Android application that allows you to send notifications to the app from a server or directly from the app itself. It provides a simple and straightforward way to deliver important messages, updates, or alerts to the users.

## Features

- Receive Notifications: The app can receive notifications sent from a server or triggered within the app itself.

- Display Notifications: When a notification is received, the app displays it in the system tray, showing the title, message, and an optional icon.

- Click Handling: Users can interact with the notifications by tapping on them, which can open a specific activity within the app or perform a custom action.

- Customize Notifications: The app allows you to customize the notification appearance, including the title, message, icon, and other attributes.

## Getting Started

1. Clone the repository:

2. Open the project in Android Studio.
  
3. Open the project in Android Studio.

4. Build and run the application on an Android device or emulator.

## Usage

To send notifications to the app:

1. Set up a server or backend service that can send push notifications to Android devices. You can use Firebase Cloud Messaging (FCM) or other push notification services.

2. Obtain the necessary credentials or server keys from your push notification service provider.

3. Implement the server-side logic to send notifications to the app using the obtained credentials or server keys.

4. Use the appropriate APIs or SDKs provided by your chosen push notification service to send notifications to the devices where the app is installed.

5. Customize the notification payload with the desired title, message, icon, and other attributes.

## Dependencies

The project utilizes the following dependencies:

- Firebase Cloud Messaging (FCM): Service for sending push notifications.
- oneSignal 
- AndroidX libraries: Support libraries provided by Android.

Check the `build.gradle` file for a complete list of dependencies.

## Contributing



