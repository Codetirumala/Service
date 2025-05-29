# 🎫 Service Desk Application

<div align="center">

![Service Desk](https://img.shields.io/badge/Service-Desk-blue)
![React](https://img.shields.io/badge/React-18.2.0-blue)
![Firebase](https://img.shields.io/badge/Firebase-9.22.0-orange)
![Material-UI](https://img.shields.io/badge/Material--UI-5.14.0-blue)

*A modern service desk application for efficient ticket management and support*

</div>

## ✨ Features

- 🔐 **Secure Authentication**
  - Google Sign-in integration
  - Role-based access control
  - Secure session management

- 🎯 **Ticket Management**
  - Create and track support tickets
  - Real-time status updates
  - Priority-based categorization
  - File attachment support

- 👥 **User Management**
  - User profiles and settings
  - Role-based permissions
  - Team collaboration tools

- 📊 **Dashboard Analytics**
  - Real-time ticket statistics
  - Performance metrics
  - Custom reports and insights

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Firebase account
- Google Cloud Platform account

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/service-desk.git
   cd service-desk
   ```

2. **Install dependencies**
   ```bash
   # Install server dependencies
   cd server
   npm install

   # Install client dependencies
   cd ../client
   npm install
   ```

3. **Configure environment variables**
   ```bash
   # In client directory
   cp .env.example .env
   ```
   Update the `.env` file with your Firebase configuration:
   ```
   REACT_APP_FIREBASE_API_KEY=your_api_key
   REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
   REACT_APP_FIREBASE_PROJECT_ID=your_project_id
   REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
   REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
   REACT_APP_FIREBASE_APP_ID=your_app_id
   REACT_APP_FIREBASE_MEASUREMENT_ID=your_measurement_id
   ```

4. **Start the development servers**
   ```bash
   # Start server (from server directory)
   npm run dev

   # Start client (from client directory)
   npm start
   ```

## 🛠️ Tech Stack

- **Frontend**
  - ⚛️ React.js
  - 🎨 Material-UI
  - 🔥 Firebase Authentication
  - 📦 Redux Toolkit
  - 🎭 Lottie Animations

- **Backend**
  - 🔥 Firebase Firestore
  - 🔒 Firebase Security Rules
  - 📊 Firebase Analytics

## 📱 Features in Detail

### Authentication System
- 🔐 Secure Google Sign-in
- 👤 User profile management
- 🔑 Role-based access control

### Ticket Management
- 📝 Create and edit tickets
- 📊 Track ticket status
- 📎 Attach files and documents
- 🔔 Real-time notifications

### Admin Dashboard
- 📈 Analytics and reporting
- 👥 User management
- ⚙️ System configuration
- 📊 Performance metrics

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- **Your Name** - *Initial work* - [YourGitHub](https://github.com/yourusername)

## 🙏 Acknowledgments

- Material-UI for the beautiful components
- Firebase for the robust backend services
- All contributors who have helped shape this project

---

<div align="center">

### 🌟 Star us on GitHub!

If you find this project helpful, please give it a ⭐️ on GitHub!

</div>

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