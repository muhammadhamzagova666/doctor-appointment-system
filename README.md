# Doctor Appointment System 🏥
> A comprehensive web application for streamlining doctor appointments and medical practice management

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

## 🌟 Overview

Doctor Appointment System is a modern, full-stack web application that simplifies the process of scheduling and managing doctor appointments. Built using the MERN stack (MongoDB, Express.js, React, Node.js), it provides a robust platform for patients, doctors, and administrators.

### Key Features
- 🔐 Secure user authentication and authorization
- 📅 Real-time appointment scheduling
- 👨‍⚕️ Doctor profile management
- 📱 Responsive design for all devices
- 📨 Notification system for appointments
- 👥 Role-based access control (Admin/Doctor/Patient)

## 🛠️ Technology Stack

### Frontend
- React.js 18.x
- React Router v6
- Redux Toolkit
- Ant Design UI Library
- Axios

### Backend
- Node.js 16.x
- Express.js 4.x
- MongoDB
- JWT Authentication
- Morgan (for logging)

## ⚙️ Installation & Setup

### Prerequisites
- Node.js 16.x or higher
- MongoDB
- npm/yarn

### Steps

1. Clone the repository
```bash
git clone https://github.com/muhammadhamzagova666/doctor-appointment-system.git
cd doctor-appointment-system
```

2. Install dependencies for both frontend and backend
```bash
# Install backend dependencies
npm install

# Install frontend dependencies
cd client
npm install
```

3. Configure environment variables
Create a `.env` file in the root directory:
```env
MONGODB_URL=your_mongodb_url
JWT_SECRET=your_jwt_secret
PORT=4001
```

4. Start the development server
```bash
# Start backend server
npm start

# Start frontend server (in a new terminal)
cd client
npm start
```

## 📖 Usage Guide

### User Types
1. **Patient**
   - Register/Login
   - Book appointments
   - View appointment history
   - Update profile

2. **Doctor**
   - Manage appointments
   - Update availability
   - View patient history

3. **Admin**
   - Manage all users
   - Approve/reject doctor applications
   - Monitor system activities

## 📁 Project Structure
```
doctor-appointment-system/
├── client/                 # Frontend React application
│   ├── public/
│   ├── src/
│   └── package.json
├── config/                 # Configuration files
├── controllers/           # Request handlers
├── middlewares/          # Custom middleware
├── models/               # MongoDB models
├── routes/               # API routes
├── index.js             # Entry point
└── package.json
```

## 🔒 Security

- JWT for authentication
- Bcrypt for password hashing
- Input validation
- XSS protection
- Rate limiting

## 🚀 Deployment

The application can be deployed using:
- Vercel (Frontend)
- Heroku/Railway (Backend)
- MongoDB Atlas (Database)

## 🧪 Testing

```bash
# Run backend tests
npm test

# Run frontend tests
cd client
npm test
```

## 🛣️ Roadmap

- [ ] Implement video consultations
- [ ] Add payment integration
- [ ] Enable multiple language support
- [ ] Add chat functionality

## 👥 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📝 Documentation

Detailed documentation is available.

## ❓ FAQ

**Q: Is this project free to use?**
A: Yes, this project is open-source.

**Q: Can I use this for commercial purposes?**
A: Yes.

## 🙏 Acknowledgments

- Special thanks to [Techinfo YT](https://www.youtube.com/@TechinfoYT) for the inspiration and guidance
- Built following the [Doctor Appointment Mern Stack App](https://youtube.com/playlist?list=PLuHGmgpyHfRw0wBGN8knxsJsMi74r34zw) tutorial series

## 📞 Contact

Muhammad Hamza - [GitHub](https://github.com/muhammadhamzagova666)
