# Cloud Chatter

## Overview

**Cloud Chatter** is a web-based application that allows users to type messages, which are then stored in a cloud database using Firebase. Users can send messages, which are displayed in real-time and stored in Firestore. This game serves as both a fun typing exercise and a demonstration of cloud database interaction.

## Features

- Users can type and send messages.
- Messages are stored in Firebase Firestore.
- Real-time updates to display all messages.
- User-friendly interface with a clean design.
- Hosted on Vercel for easy access.

## Technologies Used

- HTML
- CSS
- JavaScript
- Firebase (Firestore)
- Vercel (for hosting)

## How to Use

1. **Clone or Download** the repository.
2. Open the `index.html` file in a web browser.
3. Type your message in the input box.
4. Click the "Send Message" button to store and display your message.
5. All sent messages will appear in the messages area.

## Setup Instructions

### Step 1: Firebase Setup

1. **Create a Firebase Project**:
   - Go to the [Firebase Console](https://console.firebase.google.com/).
   - Click on "Add Project" and follow the prompts.

2. **Set Up Firestore**:
   - Navigate to the "Firestore Database" section.
   - Click on "Create Database" and choose "Start in Test Mode".

3. **Get Firebase Config**:
   - Go to "Project Settings" and register a web app to get your Firebase configuration.

### Step 2: Replace Firebase Config in Code

1. Open the `index.html` file.
2. Replace the `firebaseConfig` object values with your Firebase configuration values.

### Step 3: Hosting on Vercel

1. **Create a New Vercel Project**:
   - Go to [Vercel](https://vercel.com/).
   - Sign in or create a new account.
   - Click on "New Project".

2. **Import Your Code**:
   - Import from a GitHub repository or create a new repository and push your HTML file.

3. **Deploy**:
   - Follow the prompts to deploy your project on Vercel.
   - Access your game through the provided URL.

## Customization

- Modify the HTML and CSS for different designs and themes.
- Change the Firestore rules to suit your application needs (consider adding authentication for production).

## Acknowledgments

- Inspired by the need for simple cloud-based applications.
- Special thanks to Firebase and Vercel for their excellent services.
