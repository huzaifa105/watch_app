# Watch App

A Flutter-based mobile application that demonstrates a modern watch app with features to explore and manage watch collections. This project showcases the use of Flutter's capabilities for designing a sleek and user-friendly interface.

## Features

- **User Authentication**: Supports login and registration using Firebase Authentication.
- **Watch Management**: Add, view, and manage watch details.
- **Cloud Integration**: Data stored securely using Firebase Firestore.
- **Responsive UI**: Optimized for different screen sizes.

## Prerequisites

To run this project, ensure you have the following installed:

- [Flutter SDK](https://docs.flutter.dev/get-started/install)
- [Android Studio](https://developer.android.com/studio) or [Visual Studio Code](https://code.visualstudio.com/)
- Git
- A Firebase project configured with Authentication and Firestore

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/huzaifa105/watch_app.git
   cd watch_app
   ```

2. Install dependencies:
   ```bash
   flutter pub get
   ```

3. Set up Firebase:
   - Add the `google-services.json` file (for Android) to `android/app/`.
   - Add the `GoogleService-Info.plist` file (for iOS) to `ios/Runner/`.

4. Run the app:
   ```bash
   flutter run
   ```

## Building the APK

To generate an APK file:

1. Run the following command:
   ```bash
   flutter build apk --release
   ```

2. The APK file will be generated at `build/app/outputs/flutter-apk/app-release.apk`.

## Folder Structure

```
watch_app/
|-- android/        # Android platform-specific files
|-- ios/            # iOS platform-specific files
|-- lib/            # Dart code for the application
|   |-- main.dart   # Entry point of the app
|-- test/           # Unit tests
|-- pubspec.yaml    # Project dependencies
```

## Dependencies

Below are the key dependencies used in this project:

- `firebase_auth`: Authentication services
- `cloud_firestore`: Firestore database
- `audioplayers`: Audio playback
- `path_provider`: Accessing device storage

For a complete list, refer to `pubspec.yaml`.

## Screenshots

![WhatsApp Image 2024-12-20 at 15 59 57_67f91abd](https://github.com/user-attachments/assets/34192070-ed50-427b-8592-0e0ba5646ac1)


## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push the branch.
4. Submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

### Author

[Huzaifa105](https://github.com/huzaifa105)
