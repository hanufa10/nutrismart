# NutriSmart: Intelligent Nutrition Planner

**NutriSmart** is a cross-platform mobile application built with Flutter that serves as a personalized smart nutrition and health companion. Developed as a final project for a Mobile Development course, NutriSmart empowers users to seamlessly track their daily dietary intake, monitor physical metrics, and establish sustainable health habits.

<table align="center">
  <tr>
    <td width="25%" align="center" style="padding: 5px; vertical-align: top;">
    <img width="624" height="853" alt="image" src="https://github.com/user-attachments/assets/34bf5e14-06b8-41cf-ad24-3667adc87ab0" />
    </td>
    <td width="25%" align="center" style="padding: 5px; vertical-align: top;">
      <img width="626" height="852" alt="image" src="https://github.com/user-attachments/assets/52d0207b-6a77-4583-92cd-97cfc99efbd0" />
     </td>
    <td width="25%" align="center" style="padding: 5px; vertical-align: top;">
       <img width="623" height="854" alt="image" src="https://github.com/user-attachments/assets/0074eda2-ea47-42e2-a86e-ea1d796bf9d9" />
    </td>
  </tr>
  <tr>
    <td width="25%" align="center" style="padding: 5px; vertical-align: top;">
       <img width="623" height="848" alt="image" src="https://github.com/user-attachments/assets/48cbdd87-d9d9-47cf-81aa-db672562d240" />
    </td>
    <td width="25%" align="center" style="padding: 5px; vertical-align: top;">
       <img width="619" height="860" alt="image" src="https://github.com/user-attachments/assets/d56a144b-a488-4ca0-a411-3593b832ec9e" />
    </td>
    <td width="25%" align="center" style="padding: 5px; vertical-align: top;">
       <img width="625" height="853" alt="image" src="https://github.com/user-attachments/assets/a6b3b056-4236-414b-a8ee-b9b76590cfc0" />
   </td>  
  </tr>
</table>

---

## Table of Contents
- [Introduction](#introduction)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Database Architecture](#database-architecture)
- [Setup & Installation](#setup-installation)
- [Authors](#authors)

---

<a name="introduction"></a>
## Introduction

Tracking nutrition often feels overwhelming and tedious. **NutriSmart** streamlines this experience by offering a dynamic, personalized dashboard where users can set fitness goals, manage meals, and visualize their daily macro-nutrient progress. It transforms standard health logging into an intuitive and visually engaging daily habit.

---

<a name="key-features"></a>
## Key Features

### Intelligent Tracking & Visualization
- **Personalized Dashboard**: Visualizes daily intake and macro-nutrients dynamically.
- **Weekly Insights Matrix**: See your nutritional patterns over the week using integrated charts.
- **Goal Setting**: Set and manage goals for your physical metrics (weight, height, age) and daily caloric targets.

### Seamless Meal Management
- **Add & Remove Meals**: Quickly log breakfast, lunch, dinner, or snacks, instantly updating your daily dashboard.
- **Data Persistence**: Offline-first local caching paired with real-time cloud synchronization.

### Secure & Frictionless Access
- **Firebase Authentication**: Robust, secure sign-up, login, and user session management.
- **Dynamic Onboarding Form**: Rigorous form validation for personalized user physical metrics during onboarding.

---

<a name="technology-stack"></a>
## Technology Stack

- **Frontend Framework**: [Flutter](https://flutter.dev/) (Dart)
- **State Management**: Provider
- **Local Storage**: Hive & Shared Preferences for offline-first capabilities
- **UI Components & Charts**: `fl_chart` for dynamic visualizations, `google_fonts` for typography, `cupertino_icons`
- **Backend & Authentication**: Firebase Auth
- **Real-time Database**: Cloud Firestore

---

<a name="database-architecture"></a>
## Database Architecture

NutriSmart uses a hybrid architecture for maximum performance and reliability:

- **Local Storage (Hive & Shared Preferences)**: Used for rapid access to user preferences and offline-caching of daily logs.
- **Cloud Firestore**: Real-time synchronization of user profiles, daily nutrition logs, and weekly goals across multiple devices.
- **Firebase Auth**: Securely stores identity and session tokens.

---

<a name="setup-installation"></a>
## Setup & Installation

To run this project locally, ensure you have the Flutter SDK installed on your machine.

1. **Clone the repository**:
   ```bash
   git clone <your-repo-url>
   cd nutrismart
   ```

2. **Install dependencies**:
   ```bash
   flutter pub get
   ```

3. **Firebase Configuration**:
   - For Android: Ensure `google-services.json` is placed in `android/app/`.
   - For iOS: Ensure `GoogleService-Info.plist` is placed in `ios/Runner/`.

4. **Run the application**:
   ```bash
   flutter run
   ```

---

<a name="authors"></a>
## Authors

This final project was developed by the following team for our Mobile Development course:

*   **Eden Awoke** - UGR/2222/15
*   **Hana Hilekiros** - UGR/5655/15
*   **Hanan Abdulshikur** - UGR/6257/15
*   **Hanan Fatih** - UGR/6009/15
