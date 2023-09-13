# Bento Barber Booking App Documentation

Welcome to the documentation for the Bento Barber Booking App. Bento is a mobile application designed to streamline the barber booking process, making it easier for both barbers and students to manage their appointments. This document provides an overview of the app and describes the three main repositories associated with its development: the Bento Barber App, the Student App, and the Firebase Cloud Function. Additionally, it provides instructions for installation.

## App Overview

The Bento Barber Booking App is built using React Native and Firebase, offering a cross-platform solution for both Android and iOS users. It simplifies the barber booking process, allowing students to easily find and book appointments with their preferred barbers, and barbers to manage their schedules efficiently.

**Key Features:**
- **User Authentication:** Users can sign up, log in, and manage their profiles.
- **Barber Listings:** Students can browse barber profiles, view services, and book appointments.
- **Booking Management:** Barbers can accept or reject appointment requests and manage their schedules.
- **Notifications:** Users receive real-time notifications about appointment updates.
- **Reviews and Ratings:** Students can leave reviews and ratings for barbers.

## Repositories

1. **Bento Barber App Repository**

   - **Repository Link:** [Bento for Barber App](https://github.com/Bento-One-stop-for-students/bento-business)
   - **Description:** This repository contains the source code for the Bento Barber App. It is the main application used by barbers to manage their profiles, schedules, and accept/reject appointment requests from students.

2. **Student App Repository**

   - **Repository Link:** [Bento for Student App](https://github.com/Bento-One-stop-for-students/bento)
   - **Description:** The Student App repository houses the code for the Bento Student App. Students use this app to search for barbers, view their profiles, and book appointments.

3. **Firebase Cloud Function Repository**

   - **Repository Link:** [Firebase Cloud Function](https://github.com/Bento-One-stop-for-students/bento_firebase_cloudFunction)
   - **Description:** This repository contains the Firebase Cloud Function code. It is responsible for handling various backend functionalities such as sending notifications, updating database records, and managing user authentication.

## Installation

To set up the Bento Barber Booking App locally, follow these steps:

### Prerequisites

- Node.js and npm must be installed on your machine.
- Expo CLI should be installed globally (`npm install -g expo-cli`).

### Clone Repositories

1. Clone the Bento Barber App repository:

   ```bash
   git clone https://github.com/yourusername/bento-barber-app.git

2. Clone the Student App repository:
   ```bash
   git clone https://github.com/yourusername/student-app.git

3. Clone the Firebase Cloud Function repository:
   ```bash
   git clone https://github.com/yourusername/firebase-cloud-function.git

4. Set Up Firebase

- Create a Firebase project on the Firebase Console.

- Set up Firebase Authentication and Firestore for your project.

- Configure Firebase credentials in the Bento Barber App and Student App by following the Firebase documentation.

## Install Dependencies
- Navigate to each cloned repository and install the project dependencies:

   ```bash
   cd bento-barber-app
   npm install
   ```

   ```bash
   cd student-app
   npm install

- Start the Apps
- Start the Bento Barber App and Student App using Expo:

   ```bash
   cd bento-barber-app
   npm start
   ```

   ```bash
   cd student-app
   npm start
   ```
- Follow the instructions provided by Expo to run the apps on an emulator or physical device.

## Deploy Firebase Cloud Function
- Deploy the Firebase Cloud Function to handle backend tasks. Refer to the repository's README for deployment instructions.

That's it! You've successfully set up the Bento Barber Booking App and its associated repositories. Feel free to explore and customize the app to fit your specific needs. If you encounter any issues or have questions, please refer to the repository READMEs for further guidance.
