# QuickNotes

QuickNotes is a note-taking application that allows users to create, manage, and organize their notes efficiently. The app includes Firebase authentication, CRUD functionalities, and is built following the BLoC (Business Logic Component) state management pattern.

## Features

- **User Authentication**: Secure user login and registration using Firebase authentication.
- **CRUD Functionality**: Users can Create, Read, Update, and Delete notes.
- **State Management**: Built using the BLoC pattern to ensure scalable and maintainable code.
- **Responsive UI**: A user-friendly interface optimized for both mobile and web platforms.
- **Data Persistence**: Notes are stored securely in Firebase.

## Technology Stack

- **Frontend**: Flutter (for cross-platform mobile and web support)
- **Backend**: Firebase (for authentication and cloud storage)
- **State Management**: BLoC pattern for managing the application state.
  
## Screenshots

Add screenshots to showcase the main features and user interface of your app.

## Getting Started

### Prerequisites

- **Flutter** installed on your machine. If you don't have Flutter installed, follow the [Flutter installation guide](https://flutter.dev/docs/get-started/install).
- A **Firebase account** to set up authentication and cloud storage.

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/quicknotes.git
   cd quicknotes


2. **Install dependencies**:
   ```bash
   flutter pub get
   ```

3. **Set up Firebase**:
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).
   - Enable **Firebase Authentication** and **Firestore** for data storage.
   - Download the `google-services.json` file for Android and `GoogleService-Info.plist` for iOS and add them to the respective directories in your project (`android/app` for Android and `ios/Runner` for iOS).

4. **Run the app**:
   ```bash
   flutter run
   ```

## Usage

1. **User Authentication**: Users must log in or register with their email and password to access the app.
2. **Creating Notes**: Users can create new notes by clicking the 'Add Note' button and typing their content.
3. **Managing Notes**: Notes can be edited or deleted from the main dashboard.
4. **Data Persistence**: All notes are stored securely in Firebase and synced across sessions.

## LinkedIn Post

I shared details about the QuickNotes project and my experience working on it in a LinkedIn post. You can read the post here:

[LinkedIn Post - QuickNotes Project](https://www.linkedin.com/posts/md-hatif-farooque-35b55a229_flutterdevelopment-apparchitecture-softwaredevelopment-activity-7147248045745659905-Hnhl?utm_source=share&utm_medium=member_desktop)

## Project Structure

- **lib/**: Contains the main application code.
  - **bloc/**: BLoC pattern implementation for managing state.
  - **screens/**: UI screens for login, note listing, and note creation.
  - **models/**: Data models for representing user notes.
  - **services/**: Firebase service for handling authentication and CRUD operations.
- **android/**, **ios/**: Platform-specific code for Android and iOS.
- **assets/**: Contains app assets like images or fonts.

## Contributing

Feel free to open issues or submit pull requests if you'd like to contribute to this project.


## Contact

For any inquiries, you can reach out to me at:

- **Email**: mthraza72@gmail.com
- **LinkedIn**: [Md Hatif Farooque](https://www.linkedin.com/in/md-hatif-farooque-35b55a229)
```
