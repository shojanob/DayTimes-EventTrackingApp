# DayTimes-EventTrackingApp

Event-Tracking App — README Update
Project Summary

The Event-Tracking App was developed to help users create, manage, and receive reminders for upcoming events. The main goal was to design an application that provides a simple and intuitive way for users to organize their schedules while offering optional SMS notifications on the day of an event. This app addresses the user’s need for reliability, privacy, and convenience by storing all data locally in a SQLite database and allowing offline operation without requiring internet access.

User Interface Design and Features

The app includes several user-centered screens:

Login Screen: Allows users to create an account or log in securely.

Event List Screen: Displays all events in a structured grid layout with options to add, edit, or delete events.

Event Detail Screen: Enables users to enter event titles, dates, and descriptions.

Notification Screen: Handles SMS permissions and lets users enable or disable reminders.

Each screen was designed following Material Design principles: clean layouts, clear visual hierarchy, and minimal navigation friction. Buttons, input fields, and labels were positioned logically to match natural user flow. These designs were successful because they prioritized accessibility and ease of use, making the app intuitive even for first-time users.

Coding Approach

I approached the coding process methodically, focusing on modularity and clarity. I used Java and SQLiteOpenHelper to manage persistent data and followed standard CRUD (Create, Read, Update, Delete) functionality. I implemented clean class structures, in-line comments, and consistent naming conventions for readability. The app was developed incrementally—testing after each feature was added to minimize bugs and maintain stability. This iterative, test-driven approach will be useful in future projects because it ensures scalability and makes debugging significantly easier.

Testing and Validation

Testing was performed using the Android Emulator and multiple API levels (24–34) to confirm compatibility. Each feature—login, CRUD operations, and SMS permissions—was tested individually. I verified database persistence, user authentication, and reminder scheduling through both automated and manual testing. This process was essential to ensure reliability and revealed small logic issues early, such as permission handling and data refresh timing, which were corrected before finalization.

Challenges and Innovation

One key challenge was implementing SMS functionality while maintaining full app usability for users who deny permissions. I solved this by building a conditional logic path that allows the core app to function even without SMS access. This ensured compliance with Android privacy standards while maintaining user trust. Another area of innovation was integrating alarms using AlarmManager.setExactAndAllowWhileIdle() to ensure day-of reminders worked reliably despite Doze mode restrictions.

Demonstration of Skills

I was particularly successful in demonstrating my skills in UI/UX design and database integration. Combining Material Design layouts with functional database-driven screens showed my ability to merge front-end design with back-end logic effectively. The finished application demonstrates a complete understanding of mobile development best practices, from user authentication and data persistence to permission management and launch planning.
