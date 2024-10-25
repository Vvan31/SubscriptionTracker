# Subscription Tracker

## Overview
This is a subscription tracker web app built with Next.js and Firebase. The app allows users to track their subscriptions by adding them to the dashboard, filtering them by genre, and getting reminders to cancel them if needed.

## Features
- User Authentication (Sign up/Login)
- Add and filter subscriptions by genre
- View total monthly cost
- Expandable cards for each subscription to show detailed information
- Reminders to cancel subscriptions
- Fully responsive with an aesthetic UI using Tailwind CSS, MUI, and Magic UI

## Tech Stack
- Next.js
- TypeScript
- Firebase (Authentication, Firestore)
- Tailwind CSS
- MUI (Material UI)
- Magic UI (for animations)
- Context API for state management

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/subscriptiontracker.git
   cd subscriptiontracker
   
2. Install dependencies:
   ```bash
   npm init
   
3. Set up Firebase:
    - Create a Firebase project and enable Authentication and Firestore.
    - Update the Firebase config in firebaseConfig.ts.

4. Run the app:
   ```bash
   npm run dev
   
