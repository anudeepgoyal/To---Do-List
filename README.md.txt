# To-Do List Application

## Project Overview
The To-Do List application is a mobile app designed to help users manage their daily tasks efficiently. It allows users to add, edit, delete, and prioritize tasks. The app provides an intuitive interface using RecyclerView and CardView, enabling users to interact with their task list seamlessly. Developed using Android Studio, the app features a real-time SQLite database for secure and fast task storage.

## Features
- **Effortless Task Management**: Users can create, edit, and delete tasks with a few taps.
- **Real-time Database**: SQLite is used for real-time task updates and secure data storage.
- **Interactive Interface**: Task listing with RecyclerView and CardView for organized and user-friendly interaction.
- **Task Prioritization**: Users can prioritize tasks based on their importance or deadlines.
- **Floating Action Button**: Quick task creation with a simple and accessible floating action button.
- **Swipe Gestures**: Swipe left to edit or right to delete tasks with intuitive gestures.

## Technologies Used
- **Frontend**: Java, XML
- **Backend**: SQLite
- **Development Environment**: Android Studio

## Future Enhancements
- Task categorization
- Due date reminders
- Cross-device synchronization through cloud storage
- Task sharing and collaboration

## How to Run
1. Clone the repository and open it in Android Studio.
2. Build the project and install the app on your Android device or emulator.
3. Start managing your tasks with the intuitive UI.

## Project Structure
- **MainActivity.java**: Handles the main functionality and UI interactions of the app.
- **DataBaseHelper.java**: Manages all the database operations such as adding, updating, and deleting tasks.
- **ToDoAdapter.java**: Binds data to the RecyclerView for task display.
- **AddNewTask.java**: Bottom sheet for adding or editing tasks.
- **SplashActivity.java**: Displays the splash screen on app startup.

## Authors
- **Anudeep Goyal**  
  B.Tech CE, SVKM’s NMIMS Deemed to be University, Navi Mumbai

## Acknowledgements
- Special thanks to Dr. Preeti Gupta, Associate Professor at STME, NMIMS Navi Mumbai, for her guidance and support throughout the project.
