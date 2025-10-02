# 🌟 Docleus - Revolutionizing Healthcare Management

<div align="center">

![Docleus Banner](https://img.shields.io/badge/Healthcare-Management-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

**Transforming Healthcare Through Technology**

[Live Demo](https://docleus-frontend.onrender.com/) • [Report Bug](https://github.com/sachin3059/docleus/issues) • [Request Feature](https://github.com/sachin3059/docleus/issues)

</div>

---

## 📖 About The Project

Docleus is a cutting-edge healthcare management platform that bridges the gap between patients and healthcare providers. Built with modern web technologies, it streamlines doctor appointments, promotes mental health awareness, and leverages AI-powered diagnostics to enhance patient care. Our mission is to make quality healthcare accessible, efficient, and patient-centric.

### ✨ Why Docleus?

- 🎯 **Patient-First Approach** - Intuitive interface designed with users in mind
- 🔒 **Secure & Compliant** - Industry-standard security practices for sensitive health data
- 🤖 **AI-Powered Insights** - Smart symptom analysis for preliminary health guidance
- 📱 **Responsive Design** - Seamless experience across all devices
- ⚡ **Real-Time Updates** - Instant appointment confirmations and notifications

---

## 🚀 Key Features

### 🩺 Core Functionality

- **Smart Appointment Booking**
  - Real-time doctor availability
  - Easy rescheduling and cancellation
  - Automated appointment reminders
  - Multi-specialty doctor search

- **Mental Health Assessment**
  - Confidential questionnaires
  - Progress tracking over time
  - Personalized recommendations
  - Anonymous support resources

- **AI Symptom Checker**
  - Intelligent symptom analysis
  - Preliminary health guidance
  - Urgency level assessment
  - Specialist recommendations

- **Secure Medical Records**
  - Cloudinary-powered image storage
  - Fast upload and retrieval
  - HIPAA-compliant security
  - Easy sharing with healthcare providers

- **Admin Dashboard**
  - User management system
  - Appointment oversight
  - Health event creation
  - Analytics and reporting

---

## 🛠️ Tech Stack

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### Backend
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)

### Database & Cloud
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)

---

## 📋 API Documentation

### Authentication Endpoints

| Method | Endpoint | Description | Auth Required |
|--------|----------|-------------|---------------|
| POST | `/api/auth/register` | Register a new user | ❌ |
| POST | `/api/auth/login` | User login | ❌ |
| GET | `/api/auth/profile` | Get user profile | ✅ |
| PUT | `/api/auth/update` | Update user information | ✅ |

### Appointment Endpoints

| Method | Endpoint | Description | Auth Required |
|--------|----------|-------------|---------------|
| GET | `/api/appointments` | Fetch all appointments | ✅ |
| POST | `/api/appointments` | Book a new appointment | ✅ |
| PUT | `/api/appointments/:id` | Update appointment | ✅ |
| DELETE | `/api/appointments/:id` | Cancel appointment | ✅ |

### Mental Health Endpoints

| Method | Endpoint | Description | Auth Required |
|--------|----------|-------------|---------------|
| POST | `/api/mental-health` | Submit assessment | ✅ |
| GET | `/api/mental-health` | Get user mental health history | ✅ |
| GET | `/api/mental-health/stats` | Get assessment statistics | ✅ |

### AI Symptom Checker

| Method | Endpoint | Description | Auth Required |
|--------|----------|-------------|---------------|
| POST | `/api/symptoms/check` | Analyze symptoms | ✅ |
| GET | `/api/symptoms/history` | Get symptom check history | ✅ |

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB (v4.4 or higher)
- npm or yarn package manager
- Cloudinary account
- OpenAI API key (for AI features)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/sachin3059/docleus.git
   cd docleus
   ```

2. **Install backend dependencies**
   ```bash
   cd backend
   npm install
   ```

3. **Install frontend dependencies**
   ```bash
   cd ../frontend
   npm install
   ```

4. **Configure environment variables**
   
   Create `.env` file in the backend directory:
   ```env
   PORT=5000
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   CLOUDINARY_CLOUD_NAME=your_cloudinary_name
   CLOUDINARY_API_KEY=your_cloudinary_key
   CLOUDINARY_API_SECRET=your_cloudinary_secret
   OPENAI_API_KEY=your_openai_key
   ```

   Create `.env` file in the frontend directory:
   ```env
   REACT_APP_API_URL=http://localhost:5000
   ```

5. **Start the development servers**
   
   Backend:
   ```bash
   cd backend
   npm run dev
   ```
   
   Frontend (in a new terminal):
   ```bash
   cd frontend
   npm start
   ```

6. **Access the application**
   
   Open your browser and navigate to `http://localhost:3000`

---

## 🌐 Live Demo

**Experience Docleus in action:** [https://docleus-frontend.onrender.com/](https://docleus-frontend.onrender.com/)

### Demo Credentials
```
Email: demo@docleus.com
Password: Demo@123
```
*Note: Demo account has limited permissions*

---

## 📸 Screenshots

<div align="center">

### Dashboard
![Dashboard](https://via.placeholder.com/800x400?text=Dashboard+Screenshot)

### Appointment Booking
![Appointments](https://via.placeholder.com/800x400?text=Appointment+Booking)

### AI Symptom Checker
![AI Checker](https://via.placeholder.com/800x400?text=AI+Symptom+Checker)

</div>

---

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request**

### Contribution Guidelines

- Follow the existing code style and conventions
- Write clear, descriptive commit messages
- Add tests for new features
- Update documentation as needed
- Ensure all tests pass before submitting PR

---

## 🗺️ Roadmap

- [x] User authentication and authorization
- [x] Doctor appointment booking
- [x] Mental health assessment tool
- [x] AI-powered symptom checker
- [ ] Telemedicine video consultations
- [ ] Prescription management system
- [ ] Mobile application (iOS & Android)
- [ ] Multi-language support
- [ ] Integration with wearable devices
- [ ] Patient community forums

See the [open issues](https://github.com/sachin3059/docleus/issues) for a full list of proposed features and known issues.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 📧 Contact

**Sachin Kumar**

- 📧 Email: Mahindra8252@gmail.com
- 💼 GitHub: [@mahindra8252](https://github.com/Mahindra8252)
- 🔗 LinkedIn: [Connect with me](https://linkedin.com/in/mahindra8252)
- 🌐 Portfolio: [MahindraPortfo](https://mahindra8252.github.io/Portfolio/)

**Project Link:** [https://github.com/Mahindra8252/BookMyDoctor](https://github.com/Mahindra8252/BookMyDoctor)

---

## 🏅 Acknowledgements

- [Cloudinary](https://cloudinary.com/) - Seamless image uploads and management
- [MongoDB](https://www.mongodb.com/) - Robust database management
- [OpenAI](https://openai.com/) - Powering the AI symptom checker
- [React Icons](https://react-icons.github.io/react-icons/) - Beautiful icon library
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [Express.js](https://expressjs.com/) - Fast, minimalist web framework

---

## ⭐ Show Your Support

If you find Docleus helpful, please consider giving it a star! Your support motivates us to keep improving.

<div align="center">

**Made with ❤️ by Mahindra Kumar**
</div>
