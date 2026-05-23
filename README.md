# EduAssist-Learing-Management-System
EduAssist - Mobile LMS with Student and Lecturer Portals EduAssist is a cross- plaform learning management system enabling students to access courses,view materials, track attendance and join live lectureres. Lectureres can uplad resources, manage courses, schedule online sessions and monitor attendance - all in one app efficiently. 
# EduAssist Mobile Application

## Overview

EduAssist is an Android-based educational mobile application developed using Java in Android Studio. The application is designed to support communication and interaction between students and lecturers by providing course management, attendance tracking, learning material sharing, and online learning functionalities.

The system helps improve educational management and allows users to access academic resources efficiently.

---

## Features

### Student Features
- Student registration and login
- Profile management
- View enrolled courses
- View course details
- Access uploaded learning materials
- Join online lectures

### Lecturer Features
- Lecturer registration and login
- Manage courses
- Upload learning materials
- Conduct attendance tracking
- View student records

### Attendance System
- Attendance scanning functionality
- Attendance record management

### Additional Features
- Splash screen animation
- Role selection interface
- Online lecture support
- File upload management

---

## Technologies Used

- Android Studio
- Java
- Firebase Authentication
- Firebase Realtime Database
- CameraX
- XML
- Material Design Components

---

## Development Environment

- IDE: Android Studio
- Programming Language: Java
- Minimum SDK: 24
- Target SDK: 35
- Java Version: 11

---

## Libraries Used

dependencies:

- AndroidX AppCompat
- Material Design
- ConstraintLayout
- CameraX
- Firebase Authentication
- Firebase Realtime Database
- Google Credential Services

---

## Project Structure

```text

app
├── java/com/example/eduassist
│ ├── Student Module
│ ├── Lecturer Module
│ ├── Attendance Module
│ └── Utility Components
│
├── res
│ ├── layout
│ ├── drawable
│ ├── values
│ └── anim

EduAssist/
│
├── app/
│   ├── build.gradle.kts
│   ├── google-services.json
│   ├── proguard-rules.pro
│   │
│   └── src/
│       ├── androidTest/
│       │   └── java/com/example/eduassist/
│       │       └── ExampleInstrumentedTest.java
│       │
│       ├── main/
│       │   ├── AndroidManifest.xml
│       │   │
│       │   ├── java/com/example/eduassist/
│       │   │
│       │   │── SplashActivity.java
│       │   │── RoleSectionActivity.java
│       │   │
│       │   │── StudentLoginActivity.java
│       │   │── StudentSignUpActivity.java
│       │   │── StudentDashboardActivity.java
│       │   │── StudentProfileActivity.java
│       │   │── EditStudentProfileActivity.java
│       │   │── StudentCoursesActivity.java
│       │   │── StudentCourseDetailActivity.java
│       │   │
│       │   │── LecturerLoginActivity.java
│       │   │── LecturerSignUpActivity.java
│       │   │── LecturerDashboardActivity.java
│       │   │── MyCoursesActivity.java
│       │   │── CourseDetailActivity.java
│       │   │
│       │   │── AttendanceScannerActivity.java
│       │   │── AttendanceRecord.java
│       │   │
│       │   │── OnlineLectureActivity.java
│       │   │── UploadMaterialsActivity.java
│       │   │── UploadedFilesAdapter.java
│       │
│       │   ├── res/
│       │   │   ├── layout/
│       │   │   │
│       │   │   │── activity_splash.xml
│       │   │   │── activity_student_login.xml
│       │   │   │── activity_student_dashboard.xml
│       │   │   │── activity_student_profile.xml
│       │   │   │── activity_student_courses.xml
│       │   │   │── activity_lecturer_dashboard.xml
│       │   │   │── activity_attendance_scanner.xml
│       │   │   │── activity_upload_materials.xml
│       │   │   │── item_uploaded_file.xml
│       │   │
│       │   │── drawable/
│       │   │── anim/
│       │   │── values/
│       │
│       └── test/
│
├── gradle/
├── build.gradle.kts
├── settings.gradle.kts
└── gradlew
