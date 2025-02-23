# Task Manager App with Local Storage & Notifications

This project focuses on developing a **Task Manager App** using **React Native**. The app will allow users to manage tasks—create, edit, delete, and mark them as completed. Tasks will be stored locally using **AsyncStorage** or **SQLite**, and users can set reminders with **local push notifications**. The app will feature a clean, user-friendly interface and retain tasks even after closing the app.

## Features
- **Task Management**: Create, edit, delete, and mark tasks as completed.
- **Persistent Storage**: Store tasks locally using AsyncStorage or SQLite.
- **Notifications**: Set local push notifications to remind users of tasks.
- **User-Friendly UI**: A clean, intuitive interface for easy task management.

## Task Input Fields
- **Task Title**: Required
- **Description**: Optional
- **Due Date & Time**: Required
- **Priority**: Low, Medium, High
- **Category**: Work, Personal, etc.
- **Reminder Notification**: Toggle switch to enable/disable.

---

## Steps to Set Up and Run the App

### Step 1: Install Dependencies
Run the following command to install the required packages:
```bash
npm install
```

### Step 2: Run the App in Debug Mode
Start the Metro Bundler:
```bash
npm start
```
or
```bash
npx react-native start
```

Run the app on an Android device/emulator:
```bash
npx react-native run-android
```

Run the app on an iOS simulator (macOS only):
```bash
npx react-native run-ios
```

### Step 3: Build the App in Release Mode (Android)
To generate a release APK, run:
```bash
cd android
./gradlew assembleRelease
```

---

## Conclusion
You have successfully set up and run your **Task Manager App** using React Native.

For more information, check out these resources:
- [React Native Documentation](https://reactnative.dev/docs/getting-started)
- [AsyncStorage Documentation](https://react-native-async-storage.github.io/async-storage/)
- [SQLite Documentation](https://www.sqlitetutorial.net/)
- [React Native Push Notifications](https://www.npmjs.com/package/react-native-push-notification)

