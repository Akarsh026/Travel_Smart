## 🚀 TRAVEL SMART

**TRAVEL SMART** is a modern, mobile-first application that allows travelers to seamlessly book flight and train tickets and manage their bookings. In line with the trend of increasing traveler independence, this app offers a simple, easy-to-use platform for planning and executing entire trips directly from a mobile device.

### ✨ Key Features

* **Online Ticket Booking:** Users can search and book both **plane** and **train** tickets based on availability.
* **User Authentication:** Secure **Sign-up** and **Login** functionality using **Firebase Authentication**.
* **Booking Management:** Ability to view and track all past and current booking details.
* **User Profile:** View personal profile details within the application.
* **Simple UI:** Designed with a simple and intuitive user interface for easy navigation.
* **Mobile-First Design:** Optimized for a smooth experience on mobile devices, catering to the over 50% of travelers who use their phone for trip planning.

---

## 🛠️ Technology Stack

The application is built upon a robust and modern technology stack for Android development.

| Category | Technology | Description |
| :--- | :--- | :--- |
| **Mobile Development** | **Android Studio** | The official Integrated Development Environment (IDE) for Android development. |
| **Programming Language** | **Java** | High-level, object-oriented language used for the core application logic. |
| **Backend/Database** | **Firebase** | Used as a Backend-as-a-Service (BaaS) providing real-time database and authentication services. |
| **Database Type** | **Firebase Realtime Database** | Scalable NoSQL cloud database for storing and syncing application data. |
| **Authentication Service** | **Firebase Authentication** | Provides an end-to-end identity solution for secure user sign-in. |

---

## 📋 System Requirements

To set up and run the project locally, ensure you meet the following hardware and software requirements.

### Hardware Requirements

| Component | Minimum Specification |
| :--- | :--- |
| **Processor** | Intel Core i5 @ 1.80GHz or above |
| **RAM** | 2 GB or above |
| **Screen Resolution** | 1280 x 800 (minimum) |

### Software Requirements

| Component | Requirement |
| :--- | :--- |
| **Operating System** | Windows, macOS, or LINUX (any that supports Android Studio) |
| **IDE** | Android Studio |
| **SDK** | Android SDK |

---

## ⚙️ Setup and Installation

Follow these steps to get a local copy of the project up and running:

### 1. Clone the Repository

```bash
git clone [https://github.com/YourUsername/TRAVEL_SMART.git](https://github.com/YourUsername/TRAVEL_SMART.git)
cd TRAVEL_SMART
```

(Note: Replace YourUsername/TRAVEL_SMART.git with your actual repository URL.)

### 2. Open in Android Studio
Launch Android Studio.

Select "Open an existing Android Studio project" and navigate to the cloned TRAVEL_SMART directory.

Allow Gradle to sync the project dependencies. This may take a few moments.

### 3. Firebase Configuration (Crucial Step)
The application relies heavily on Firebase for authentication and data storage.

Create a Firebase Project: Go to the Firebase Console and create a new project.

Register the Android App: Follow the instructions in the Firebase Console to register your Android app (using the correct package name, e.g., com.example.travels).

Download google-services.json: Download the configuration file provided by Firebase.

Add to Project: Place the downloaded google-services.json file into the app/ module directory of your Android Studio project.

Enable Services:

In the Firebase Console, go to Authentication and enable the Email/Password sign-in method.

Go to Realtime Database and create a database instance.

### 4. Run the Application
Select your desired device/emulator from the toolbar (using the AVD Manager if needed).

Click the "Run 'app'" button (the green triangle) in the Android Studio toolbar.

## 📈 Project Flow
The core process of the application is visualized below:

Start: Splash Screen.

User Flow: New users go to the Registration Page; existing users go to the Login Page.

Home Screen: After successful login, the user lands on the Home Page.

Booking: User selects Airplane or Train booking.

Search & Select: The app displays available lists; the user selects an option.

Ticket Management: If seats are available, the user proceeds to payment and details confirmation, updating the Firebase Realtime Database.

Tracking: The user can view booked tickets via the My Booking section.

Logout: Returns to the Login Page.

## 👥 Authors and Acknowledgements
This project was a collaborative effort by the following students:

AKARSH C SHETTY (4SF19CS015)  
SANJAY SHETTY (4SF19CS141)

Special Thanks
We are immensely grateful for the guidance and support provided by:
Ms. Supriya B Rao, Assistant Professor, Department of Computer Science (Project Guide)
Dr. Pushpalatha K, Head of the Department, Computer Science and Engineering
Dr. Rajesha S, Principal, for his encouragement.
This project was developed at the Department of Computer Science & Engineering, SCEM, Mangaluru.
