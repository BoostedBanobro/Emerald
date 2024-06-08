# Chat Application

This project is a simple chat application built using Kotlin, Google Firebase Firestore, and Firebase Authentication. The application allows users to send and receive messages in real-time, with messages stored in Firestore under user-specific chat rooms.

## Features

- **User Authentication**: Users can sign up and log in using Firebase Authentication.
- **Real-time Messaging**: Messages are sent and received in real-time using Firebase Firestore.
- **User-specific Chat Rooms**: Messages are stored in chat rooms specific to the users involved in the conversation.

## Screenshot

Here's what the chat application looks like:

![image](https://github.com/BoostedBanobro/Emerald/assets/72575802/c2286c6b-5f65-4bec-b9a4-57e6a11cf66f)

## Technologies Used

- **Kotlin**: The primary programming language used for developing the application.
- **Firebase Firestore**: A NoSQL cloud database to store and sync data in real-time.
- **Firebase Authentication**: Provides backend services for easy use of authentication via email and password.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/chat-application.git
    cd chat-application
    ```

2. **Open the project in Android Studio**.

3. **Set up Firebase**:
    - Go to the [Firebase Console](https://console.firebase.google.com/).
    - Create a new project or use an existing one.
    - Add an Android app to your Firebase project.
    - Follow the instructions to download the `google-services.json` file.
    - Place the `google-services.json` file in the `app` directory of your project.
    - Add Firebase SDK dependencies to your `build.gradle` files as instructed.

4. **Sync the project** with Gradle files.

## Usage

1. **Run the application** on an Android device or emulator.

2. **Sign Up/Login**: Use Firebase Authentication to create a new account or log in with an existing one.

3. **Start Chatting**: Users can start sending and receiving messages in real-time.




