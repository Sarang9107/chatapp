Flutter Chat App with Firebase Authentication & SQLite
The Flutter Chat App is a real-time messaging application built using Flutter, Firebase Authentication, and SQLite for local data storage. It provides a smooth and interactive chatting experience with essential authentication and messaging features.

Key Features:
User Authentication (Firebase Auth):
Users can sign up and log in using their email and password.
Firebase Authentication ensures secure login and account management.

Email Verification:
A verification email is sent to users upon registration.
Users must confirm their email before accessing the chat.

One-to-One Chat System:
Users can send and receive real-time messages.
Chats are stored locally using SQLite for quick access and offline support.

Logout and Session Management:
Users can securely log out, and session data is managed via Firebase Auth.
SQLite helps retain user sessions for quick logins.

Message Storage with SQLite:
Messages are cached locally in SQLite for offline access.
Sent messages sync automatically when the internet is available.
User Profile Management:

Offline Mode Support:
Users can view past conversations without an internet connection.
Messages sent offline are queued and sent when online.

Tech Stack Used:
Frontend: Flutter (Dart)
Authentication: Firebase Authentication
Database: SQLite (Local Storage), Firestore (Cloud Storage for User Data)
Local Storage: SharedPreferences (For storing login state)








