Student Care App

The Student Care App is a mobile application designed to streamline and enhance student management for universities and educational institutions. It provides features for students to view their profile, check course details, monitor subject performance, and manage personal information in a user-friendly manner.

Features

Login System

Secure login functionality for students using a username and password.

Displays error messages for invalid credentials.

Profile Management

View and manage personal details, including:

Name

Age

Gender

Contact Information

Address

Blood Group

Course Overview

Display details of the enrolled course, including:

Course Name

Course Code

Department

Duration

Description

Subjects and Marks

View all subjects in the enrolled course.

Check marks for each subject.

Calculate and display average marks.

Navigation

Bottom Tab Navigator for seamless navigation between:

Profile

Courses

Subjects

Reusable Components

Logo Component: Displays the university logo.

Footer Component: Displays the app footer with copyright information.

BottomTabNavigator: Simplifies navigation across major sections of the app.

Tech Stack

Frontend: React Native

Navigation: React Navigation

UI Components: React Native Paper

Folder Structure

├── components
│   ├── Logo.js
│   ├── Footer.js
│   ├── BottomTabNavigator.js
├── screens
│   ├── Login.js
│   ├── Profile.js
│   ├── Courses.js
│   ├── Subjects.js
├── navigation
│   ├── index.js
├── assets
│   ├── data
│   │   ├── StudentsDb.js
│   ├── icons
│   ├── images

Installation

Clone the repository:

git clone https://github.com/PLChandrasekara/Assignment3-Reactnative.git.git
cd MymobileApp

Install dependencies:

npm install

Run the app:

npm start

Follow the instructions to run on an emulator or connected device.

Usage

Start the app and log in using valid student credentials.

Navigate through the Profile, Courses, and Subjects sections using the bottom navigation bar.

Explore detailed information about courses and monitor academic performance.

Output

https://github.com/user-attachments/assets/cfbea5ee-900d-46e1-99e1-2ad335de3310







