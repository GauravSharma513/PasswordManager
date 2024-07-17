# Password Manager Application

## Setup:

1. **Clone the Repository:**
   - Open Android Studio.
   - Go to File > New > Project from Version Control.
   - Enter the repository URL: https://github.com/GauravSharma513/PasswordManager
   - Choose your directory and click Clone.

2. **Development Environment:**
   - Ensure you have:
     - Android Studio 4.2+ with Kotlin support.
     - Android SDK with API level 32+.
     - Android Build Tools version 30.0.3+.
     - Latest Kotlin plugin.

3. **Open Project:**
   - If the project doesn't open automatically after cloning, open it via File > Open and select the project directory.
   - Let Android Studio load and index the project.

4. **Sync and Build:**
   - Android Studio will sync the project with Gradle.
   - Wait for the sync to complete to compile the project and generate build artifacts.

## Running the App:

1. **Connect Device or Emulator:**
   - Connect an Android device via USB or start an emulator in Android Studio.
   - Ensure the device/emulator runs Android API level 30+.

2. **Build and Run:**
   - Click the green play button or select Run > Run 'app'.
   - Choose the target device/emulator.
   - Android Studio will install and launch the app.

## Features:

- **Add Passwords:**
  - Tap the "+" button.
  - Enter account type, username/email, and password.
  - Tap "Add New Account" to save.

- **View/Edit Passwords:**
  - Select a password from the home screen.
  - Tap "Edit" to update details, then "Confirm" to save.

- **Delete Passwords:**
  - Select a password from the home screen.
  - Tap "Delete" to remove it.

- **Password Strength Meter:**
  - Provides feedback on password strength based on length and complexity.

- **Generate Password:**
  - Tap "Generate Password" for a strong, random password.
  - Customize length and character types as needed.

- **Encryption and Security:**
  - Passwords are encrypted using AES.
  - Stored locally in a secure Room database.

- **Intuitive UI:**
  - Clean, minimalist design for easy navigation and use.

- **Tech Stack:**
  - Kotlin, Jetpack Compose, Room Database, AES Encryption, Android Architecture Components, Material Design.

## Screenshots:
<div style="display: flex; flex-wrap: wrap;">
    <img src="https://github.com/GauravSharma513/PasswordManager/blob/main/Snapshots/1.jpg" alt="Screenshot 1" width="300" style="margin: 10px;" />
    <img src="https://github.com/GauravSharma513/PasswordManager/blob/main/Snapshots/2.jpg" alt="Screenshot 2" width="300" style="margin: 10px;" />
    <img src="https://github.com/GauravSharma513/PasswordManager/blob/main/Snapshots/3.jpg" alt="Screenshot 3" width="300" style="margin: 10px;" />
    <img src="https://github.com/GauravSharma513/PasswordManager/blob/main/Snapshots/4.jpg" alt="Screenshot 4" width="300" style="margin: 10px;" />
    <img src="https://github.com/GauravSharma513/PasswordManager/blob/main/Snapshots/5.jpg" alt="Screenshot 5" width="300" style="margin: 10px;" />
</div>

## Notes:

- **Backup:** Implement a backup feature for encrypted password backups.
- **Security Best Practices:** Use strong, unique master passwords and don't share them.
- **User Guidance:** Provide clear in-app instructions for users.

