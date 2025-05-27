Service Desk Application
A modern service desk application built with React and Firebase, allowing users to create and manage support tickets.

Features
Google Authentication using Firebase
Create and manage support tickets
Track ticket status and updates
Add comments to tickets
Responsive design for all devices
Real-time updates
Prerequisites
Node.js (v14 or higher)
npm or yarn
Firebase account
Setup
Clone the repository:
git clone <repository-url>
Install dependencies:
cd client
npm install
Configure Firebase:

Create a new Firebase project at https://console.firebase.google.com/
Enable Google Authentication in the Firebase Console
Copy your Firebase configuration from Project Settings
Replace the Firebase config in client/src/firebase.js with your configuration
Start the development server:

npm start
The application will be available at http://localhost:3000

Project Structure
client/
  ├── src/
  │   ├── components/
  │   │   ├── Dashboard.js
  │   │   ├── Login.js
  │   │   ├── Navbar.js
  │   │   ├── CreateTicket.js
  │   │   ├── TicketList.js
  │   │   └── TicketDetails.js
  │   ├── App.js
  │   ├── firebase.js
  │   └── index.js
  └── package.json
Technologies Used
React
Material-UI
Firebase Authentication
React Router
React Firebase Hooks
Contributing
Fork the repository
Create your feature branch (git checkout -b feature/amazing-feature)
Commit your changes (git commit -m 'Add some amazing feature')
Push to the branch (git push origin feature/amazing-feature)
Open a Pull Request
License
This project is licensed under the MIT License.

Step 1: Admin Setup

Create admin collection in Firestore
Add admin role to user profiles
Create admin authentication check
Step 2: Admin Routes & Navigation

Create AdminDashboard component
Add admin routes in App.js
Add admin navigation items
Step 3: Admin Features

User Management

View all users
Edit user roles
Disable/enable users
Ticket Management

View all tickets
Assign tickets
Update ticket status
Add comments/responses
Analytics

Ticket statistics
User statistics
Response time metrics