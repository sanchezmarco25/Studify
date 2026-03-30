Studify
A sleek, modern student task manager web app designed to help students organize their tasks, deadlines, and priorities — all in one place.
Built with a glassmorphism UI inspired by tools like Linear and Notion, featuring dark/light mode, a smooth login system, and real-time data syncing powered by Firebase.

Features

Task Management — Create, update, and delete tasks with ease
Priority Levels — Mark tasks by urgency to stay on top of deadlines
Login System — Secure authentication with session persistence via localStorage
Dark / Light Mode — Toggle between themes based on your preference
Real-time Sync — Data is stored and synced using Firebase Firestore
Glassmorphism UI — Clean, modern interface inspired by Linear and Notion


Tech Stack
TechnologyPurposeHTML / CSS / JavaScriptFrontendFirebase HostingDeploymentFirebase Firestore REST APIDatabaselocalStorageSession persistence

Live Demo
🔗 https://studyflow-d645d.web.app

Getting Started
Prerequisites

A modern web browser (Chrome, Firefox, Edge)
No installations required — this is a hosted web app

Running Locally

Clone the repository:

bash   git clone https://github.com/your-username/studify.git

Navigate into the project folder:

bash   cd studify

Open index.html directly in your browser, or use a local server:

bash   # Using VS Code Live Server extension (recommended)
   # Right-click index.html → Open with Live Server

That's it — no build steps or dependencies needed.

Deploying to Firebase (optional)
If you want to deploy your own instance:

Install Firebase CLI:

bash   npm install -g firebase-tools

Login and initialize:

bash   firebase login
   firebase init

Deploy:

bash   firebase deploy

Project Structure
studify/
├── index.html       # Main entry point (includes CSS and JS)
└── README.md        # Project documentation

Author
Marco Sanchez — Personal Project
GitHub Profile
