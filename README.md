# Quiz App

A Flutter-based Quiz App that allows users to answer multiple-choice questions, highlights correct and incorrect answers, and calculates their score.

---

## Features
1. **Multiple-choice questions**:
   - Each question has four options to choose from.
   - Correct answers are highlighted in **green**.
   - Incorrect answers are highlighted in **red**.

2. **Score tracking**:
   - The app keeps track of the user's score.

3. **Progressive navigation**:
   - Users can move to the next question after answering the current one.
   - At the end of the quiz, the final score is displayed.

4. **Restart functionality**:
   - After completing the quiz, users can restart to try again.

---

## Steps to Create the Project
1. **Initialize the Flutter project**:
   Run the following command to create a new Flutter project:
   ```bash
   flutter create my_app
   ```

   This command will create the basic structure and necessary files for the Flutter project in the `my_app` directory.

2. **Navigate to the project directory**:
   ```bash
   cd my_app
   ```

3. **Replace the auto-generated files**:
   Replace the content of the auto-generated `lib/main.dart` with the provided Quiz App code.

---

## Project File Structure

Here’s an overview of the project structure with paths to the relevant files:

```
my_app/
├── lib/
│   └── main.dart                # Contains the main code for the Quiz App
├── pubspec.yaml                 # Defines dependencies and project settings
├── android/                     # Android-specific configuration and code
├── ios/                         # iOS-specific configuration and code
├── web/                         # Web-specific configuration (optional)
├── test/                        # Unit testing files
└── README.md                    # Project documentation (this file)
```

---

## Instructions to Run the App

1. **Install Flutter**:
   Ensure you have Flutter installed. Follow the instructions on the official [Flutter installation guide](https://flutter.dev/docs/get-started/install).

2. **Install dependencies**:
   Run the following command in the project directory to install the required dependencies:
   ```bash
   flutter pub get
   ```

3. **Run the app**:
   Use the following command to run the app on an emulator or connected device:
   ```bash
   flutter run
   ```

---

## File Details

1. **`lib/main.dart`**:
   - This file contains the entire logic and UI for the Quiz App.

2. **`pubspec.yaml`**:
   - Contains the necessary dependencies:
     - `flutter` for core Flutter libraries.
---

## Dependencies
- **Flutter SDK**: Ensure that your system supports the required Flutter SDK version mentioned in the `pubspec.yaml` file.
