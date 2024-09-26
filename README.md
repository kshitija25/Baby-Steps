# Baby-Steps
**BabySteps** is a comprehensive pregnancy and baby health app designed to assist expectant mothers in tracking health metrics, receiving personalized advice, and engaging with a supportive community. The app integrates various Android technologies to provide a seamless experience for users, with real-time health updates, secure data storage, and interactive features like a chatbot and forum.

## Features
- **Health Tracking**: Monitor pregnancy health metrics like weight, blood pressure, and glucose levels.
- **AI-Powered Chatbot**: Instant health tips and symptom analysis using Dialogflow.
- **Community Forum**: Engage in real-time discussions, share experiences, and seek advice from other mothers and healthcare professionals.
- **Firebase Integration**: Secure user authentication, cloud storage, and real-time database synchronization.
- **Customizable UI**: Modern and reactive UI built with Jetpack Compose for a smooth user experience.

## Technologies Used
- **Kotlin**: For app development and logic implementation.
- **MVVM Architecture**: For clean, maintainable, and scalable app design.
- **Retrofit**: For network operations and API integration.
- **Firebase**: Used for Authentication, Cloud Storage, Firestore (real-time database), and Cloud Messaging.
- **Jetpack Compose**: For modern UI development.
- **Kotlin Coroutines**: For asynchronous programming, ensuring smooth and responsive user interactions.
- **Dialogflow**: For AI-powered chatbot functionality.
- **Dagger-Hilt**: For dependency injection and modular design.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/applife2023/GoMommy.git
   ```
   
2. **Navigate to the project directory**:
   ```bash
   cd BabySteps
   ```

3. **Open the project in Android Studio**:
   - Open Android Studio.
   - Click **File > Open** and select the `BabySteps` folder.

4. **Sync Gradle**:
   - Android Studio will automatically detect the Gradle files and start syncing. If not, go to **File > Sync Project with Gradle Files**.

5. **Run the app**:
   - Connect your Android device or start an emulator.
   - Click **Run** or press **Shift + F10** to build and run the project.

## Usage

- Upon launching, the app will display a splash screen with the **BabySteps** logo.
- Afterward, you'll be guided to log in or sign up using Firebase Authentication.
- You can track your health metrics, interact with the AI chatbot for real-time health tips, and participate in the community forum.

## Project Structure

```
BabySteps/
│
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/babysteps/  // Main app code
│   │   │   ├── res/                 // Resources (layouts, drawables)
│   │   │   └── AndroidManifest.xml  // App manifest
│   └── build.gradle                 // App-level Gradle configuration
├── build.gradle                     // Project-level Gradle configuration
└── settings.gradle                  // Project settings
```

## Configuration

### Firebase Setup

To use Firebase features (Authentication, Firestore, Cloud Storage), you will need to:

1. Create a **Firebase Project** at [Firebase Console](https://console.firebase.google.com/).
2. Add the Android app to the project by registering the package name.
3. Download the `google-services.json` file and place it in the `app/` directory.
4. Add the necessary Firebase dependencies in the `build.gradle` files.
