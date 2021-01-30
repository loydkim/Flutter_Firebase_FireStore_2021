# Firebase Cloud Firestore

<img src="https://github.com/loydkim/Flutter_Firebase_FireStore_2021/blob/main/FirebaseFirestore_short.gif" width="300" height="520">

The code is not using Authentication. so you have to change the rule in firebase console

Go to Firebase Console -> "CloudFireStore" -> "Rules" on the top and change like this


rules_version = '2';
service cloud.firestore {
  match /databases/{database}/documents {
    match /{document=**} {
      allow read, write
    }
  }
}



* Develop Environment.

- Flutter SDK Version: 1.25.0-5.0
- Flutter: 52.1.1
- Dart: 201.9245
- Xcode Version: 12.2
- Android Studio: 4.1.1
- OS Version: MacOS Big Sur 11.1

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
