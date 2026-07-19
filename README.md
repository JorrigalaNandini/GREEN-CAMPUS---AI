# 🌱 Green Campus AI

An AI-powered smart campus sustainability platform that helps students report environmental issues and enables administrators to monitor, analyze, and resolve campus cleanliness problems efficiently.

## 🚀 Overview

Green Campus AI uses artificial intelligence and web technologies to create a cleaner and greener campus environment. Students can report issues such as plastic waste, dustbin overflow, water leakage, broken street lights, and other environmental problems. The system analyzes reports, provides recommendations, tracks resolution status, and rewards eco-friendly participation.

## ✨ Features

### 👨‍🎓 Student Module
- Secure student login
- Report campus environmental issues
- Upload images of issues
- Provide location details
- AI-based waste classification
- AI-generated disposal recommendations
- Duplicate issue detection
- Track submitted issues
- Earn eco points and badges

### 🛠 Admin Module
- Admin dashboard
- View all reported issues
- Search and filter issues
- Monitor issue status
- Mark issues as resolved
- View analytics and charts
- Identify common waste categories
- Analyze high-priority problems

### 🤖 AI Capabilities
- Smart disposal recommendations
- Issue analysis support
- Priority management system

## 🏗 Tech Stack

### Frontend
- React.js
- Tailwind CSS
- React Router
- Axios
- Chart.js

### Backend
- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- JWT Authentication
- Multer

### AI Logic
- AI-based waste classification
- Recommendation generation

## 📂 Project Structure

```
GreenCampus-AI/
│
├── frontend/                         # React.js Frontend
│   │
│   ├── src/
│   │   ├── components/               # Reusable UI components
│   │   │   ├── Navbar.jsx
│   │   │   └── ProtectedRoute.jsx
│   │   │
│   │   ├── pages/                    # Application pages
│   │   │   ├── Login.jsx
│   │   │   ├── Home.jsx
│   │   │   ├── ReportIssue.jsx
│   │   │   ├── IssueDetails.jsx
│   │   │   ├── AdminDashboard.jsx
│   │   │   ├── Profile.jsx
│   │   │   └── Analytics.jsx
│   │   │
│   │   ├── layouts/
│   │   │   └── MainLayout.jsx
│   │   │
│   │   ├── services/                 # API connections
│   │   │   └── api.js
│   │   │
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   └── index.css
│   │
│   └── package.json
│
├── backend/                          # Node.js + Express Backend
│   │
│   ├── config/                       # Database configuration
│   │   └── db.js
│   │
│   ├── controllers/                  # Business logic
│   │   ├── authController.js
│   │   └── issueController.js
│   │
│   ├── models/                       # MongoDB schemas
│   │   ├── User.js
│   │   └── Issue.js
│   │
│   ├── routes/                       # API routes
│   │   ├── authRoutes.js
│   │   └── issueRoutes.js
│   │
│   ├── middleware/                   # Authentication & uploads
│   │   ├── authMiddleware.js
│   │   └── uploadMiddleware.js
│   │
│   ├── services/                     # AI logic
│   │   └── aiService.js
│   │
│   ├── uploads/                      # Uploaded images
│   │
│   ├── server.js                     # Backend entry point
│   └── package.json
│
├── .gitignore
├── README.md
└── LICENSE
```
## 🔄 Workflow

1. Student logs into the platform
2. Student reports an environmental issue
3. AI analyzes the issue and provides recommendations
4. Issue is stored and displayed on the dashboard
5. Admin reviews and resolves the issue
6. Student earns eco points for participation

## 🌍 Impact

Green Campus AI helps institutions:
- Improve campus cleanliness
- Reduce environmental waste
- Encourage student participation
- Enable data-driven sustainability decisions

## 🔮 Future Enhancements

- Real-time AI image detection using computer vision
- Live campus pollution mapping
- Automated complaint generation
- IoT-based smart dustbin integration
- Advanced predictive analytics

## 👩‍💻 Developed For

Clean & Green Technology Innovation Challenge

## 📄 License

This project is developed for educational and innovation purposes.

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
