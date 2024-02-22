# Expense-Tracker

Expense-Tracker is a project consisting of a Flutter mobile app for tracking expenses and a Dart backend server for managing data.

## Prerequisites

- Flutter SDK: Make sure you have Flutter installed. If not, you can install it from the [official website](https://flutter.dev/docs/get-started/install).
- Dart SDK: Make sure you have Dart installed. If not, you can install it from the [official website](https://dart.dev/get-dart).
- IDE: Any text editor or IDE of your choice (e.g., Visual Studio Code, Android Studio).

## Running the Project

### Flutter Mobile App

1. Clone this repository:
```bash
git clone https://github.com/Krutik30/Expense-Tracker-F.git
```

2. Navigate to the `flutter_app` directory:
```bash
cd flutter_app
```

3. Install dependencies:
```bash
flutter pub get
```

4. Run the app:
```bash
flutter run -d 'your_phone_id(mine was krutik-phone)'
```

### Dart Backend Server

1. Navigate to the `backend_server` directory:
```bash
cd backend_server
```

2. Install dependencies:
```bash
pub get
```

3. Run the server:
```bash
dart server.dart
```

## Additional Notes

- Make sure your Flutter mobile app is configured to communicate with the backend server's API endpoints.
- Update the API endpoint URLs in the Flutter app if necessary.
- Ensure that your device or emulator is properly configured for running Flutter apps.