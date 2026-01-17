📋 Task Management App (Flutter + Provider)
📌 Project Overview

This is a simple Task Management (To-Do) App built using Flutter and Provider for state management.
The purpose of this project is to understand how Provider can be used instead of setState() to manage application state in a clean and scalable way.

This project was developed as part of my internship learning tasks after learning the basics of Provider in Flutter.

🎯 Objectives

Learn and apply Provider for state management

Refactor a simple To-Do app from setState() to Provider

Manage tasks (add, delete, update) using a centralized state

Update UI automatically when state changes

Improve code structure and performance

🛠️ Technologies Used

Flutter

Dart

Provider Package

✨ Features

Add a new task

Mark task as completed

Delete a task

Real-time UI updates using Provider

Simple and clean user interface

📂 Project Structure
lib/
│── main.dart
│
├── models/
│   └── task.dart
│
├── provider/
│   └── taskprovider.dart
│
└── screens/
    └── homescreen.dart

🔄 State Management (Provider)

TaskProvider extends ChangeNotifier

All task operations are handled inside the provider

UI listens to state changes using Provider.of()

notifyListeners() updates the UI in real time

▶️ How the App Works

User enters a task in the text field

Presses the Add (+) button

Task is added using Provider

UI updates automatically

User can mark tasks as completed or delete them

🚀 How to Run the Project

Clone the repository

Run the following commands:

flutter pub get
flutter run


Select Chrome, Emulator, or Physical Device

📈 Performance & Optimization

Used Provider for efficient state management

Avoided unnecessary widget rebuilds

Separated UI and logic for better maintainability

📌 Learning Outcome

Through this project, I learned:

How Provider works in Flutter

Difference between setState() and Provider

How to manage app state in a clean way

How UI reacts to state changes automatically

🔮 Future Improvements

Save tasks using local storage

Improve UI design and animations

Add task categories

Implement dark mode

👨‍💻 Author

Hasnat
Flutter Intern / Learner
