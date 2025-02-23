Digital Time Capsule

The application is hosted on Firebase Hosting and can be accessed at https://digital-time-capsule2.web.app/ 


A web application that allows users to create and store digital time capsules with text and images that can only be opened at a specified future date and time.

Features

- User authentication (sign up/sign in) using Firebase Authentication
- Create time capsules with title, message, and optional image
- Set specific date and time for capsule unlocking
- Image hosting via Imgur API
- Real-time updates and data storage using Firebase Firestore
- Responsive design for all devices

Tech Stack

- HTML/CSS/JavaScript
- Firebase (Authentication, Firestore)
- Imgur API for image hosting

Setup

1. Create a Firebase project:
   - Go to Firebase Console (https://console.firebase.google.com/)
   - Create a new project
   - Enable Authentication (Email/Password)
   - Create a Firestore database

2. Configure Firebase:
   - Replace the `firebaseConfig` object in `index.html` with your own Firebase configuration
   - The config can be found in your Firebase project settings

3. Set up Imgur:
   - Register for an Imgur API key at https://api.imgur.com/oauth2/addclient
   - Replace `IMGUR_CLIENT_ID` in the code with your API key

4. Deploy to Firebase:
   bash
   npm install -g firebase-tools
   firebase login
   firebase init
   firebase deploy

Usage

1. Users can create an account or sign in with existing credentials
2. Create a new time capsule by providing:
   - Title
   - Message
   - Optional image
   - Unlock date and time
3. View all created capsules
4. Capsule content is only revealed after the specified unlock time

Live Demo

The application is hosted on Firebase Hosting and can be accessed at https://digital-time-capsule2.web.app/ 
