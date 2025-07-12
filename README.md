# AI Learning Management System

A comprehensive AI-powered learning management system built with Next.js, React, and MongoDB. This platform provides curriculum generation, interactive chat, file management, and collaborative features for educational purposes.

## 🚀 Features

- **AI-Powered Curriculum Generation**: Generate personalized learning tracks using LangChain and Groq AI
- **Interactive Chat System**: Real-time chat with Socket.IO integration
- **File Management**: Upload and manage educational materials
- **User Authentication**: Secure authentication with NextAuth.js
- **Responsive Dashboard**: Modern UI with Tailwind CSS
- **Calendar Integration**: Schedule and track learning activities
- **Task Management**: Kanban-style task organization
- **Data Analytics**: Track learning progress and engagement

## 🛠️ Tech Stack

### Frontend
- **Next.js 15** - React framework with App Router
- **React 18** - UI library
- **TypeScript** - Type safety
- **Tailwind CSS** - Utility-first CSS framework
- **NextAuth.js** - Authentication
- **Socket.IO Client** - Real-time communication

### Backend
- **Node.js** - Runtime environment
- **Express** - Web framework
- **Socket.IO** - Real-time bidirectional communication
- **MongoDB** - NoSQL database
- **JWT** - Token-based authentication

### AI/ML
- **Python 3.13** - AI agent runtime
- **FastAPI** - Python web framework
- **LangChain** - AI framework
- **Groq API** - LLM integration

## 📋 Prerequisites

- Node.js 18+ and npm
- MongoDB (local or MongoDB Atlas)
- Python 3.13+
- Git

## 🔧 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/AI_Learning.git
cd AI_Learning
```

### 2. Install Frontend Dependencies
```bash
npm install
```

### 3. Install Backend Dependencies
```bash
cd backend
npm install
cd ..
```

### 4. Install Python Dependencies
```bash
pip install fastapi uvicorn langchain groq
```

### 5. Environment Setup

Create environment files based on the examples:

**Frontend (.env):**
```bash
cp .env.example .env
```

**Backend (backend/.env):**
```bash
cp backend/.env.example backend/.env
```

Fill in your actual values:
- `MONGODB_URI`: Your MongoDB connection string
- `GROQ_API_KEY`: Your Groq API key
- `SERPER_API_KEY`: Your Serper API key
- `JWT_SECRET`: A secure random string
- `NEXTAUTH_SECRET`: A secure random string for NextAuth

### 6. Run the Application

**Start Frontend (Development):**
```bash
npm run dev
```

**Start Backend:**
```bash
cd backend
node server.js
```

**Start AI Agent:**
```bash
python agent.py
```

## 🌐 Access Points

- **Frontend**: http://localhost:3000
- **Backend API**: http://localhost:3001
- **AI Agent**: http://localhost:8000

## 📁 Project Structure

```
AI_Learning/
├── src/
│   ├── app/                 # Next.js app router pages
│   ├── components/          # React components
│   ├── lib/                 # Utility libraries
│   └── types/               # TypeScript type definitions
├── backend/
│   ├── server.js           # Express server
│   └── package.json        # Backend dependencies
├── public/
│   ├── images/             # Static images
│   └── uploads/            # User uploads
├── agent.py                # Python AI agent
└── package.json            # Frontend dependencies
```

## 🔐 Security Features

- Environment variables protection with `.gitignore`
- JWT-based authentication
- Input validation and sanitization
- Secure file upload handling
- CORS configuration

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 API Documentation

### Authentication Endpoints
- `POST /api/auth/register` - User registration
- `POST /api/auth/signin` - User login
- `POST /api/auth/forgot-password` - Password reset

### Data Endpoints
- `GET /api/tables` - Get learning materials
- `POST /api/tables` - Create new material
- `GET /api/tracks` - Get learning tracks
- `POST /api/upload` - File upload

## 🛡️ Environment Variables

| Variable | Description | Required |
|----------|-------------|----------|
| `MONGODB_URI` | MongoDB connection string | Yes |
| `GROQ_API_KEY` | Groq AI API key | Yes |
| `SERPER_API_KEY` | Serper search API key | Yes |
| `JWT_SECRET` | JWT signing secret | Yes |
| `NEXTAUTH_SECRET` | NextAuth secret | Yes |
| `FASTAPI_URL` | AI agent URL | Yes |

## 📊 Database Schema

### Collections
- `Users` - User accounts and profiles
- `Notes` - Learning materials and notes
- `Tracks` - AI-generated learning tracks
- `ChatMessages` - Chat history
- `Conversations` - Chat sessions

## 🔄 Development Workflow

1. **Feature Development**
   - Create feature branch
   - Implement changes
   - Test locally
   - Submit PR

2. **Testing**
   - Run frontend: `npm run dev`
   - Run backend: `cd backend && node server.js`
   - Test AI agent: `python agent.py`

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Next.js team for the amazing framework
- MongoDB for the flexible database
- Groq for AI capabilities
- All contributors to this project

## 📧 Support

For support, email parth.garg_cs.h23@gla.ac.in or create an issue in the GitHub repository.

```
npm run dev
```
And if you're using **Yarn**, it's:

```
yarn dev
```

And voila! You're now ready to start developing. **Happy coding**!

## Highlighted Features
**200+ Next.js Dashboard Ul Components and Templates** - includes a variety of prebuilt **Ul elements, components, pages, and examples** crafted with a high-quality design.
Additionally, features seamless **essential integrations and extensive functionalities**.

- A library of over **200** professional dashboard UI components and elements.
- Five distinctive dashboard variations, catering to diverse use-cases.
- A comprehensive set of essential dashboard and admin pages.
- More than **45** **Next.js** files, ready for use.
- Styling facilitated by **Tailwind CSS** files.
- A design that resonates premium quality and high aesthetics.
- A handy UI kit with assets.
- Over ten web apps complete with examples.
- Support for both **dark mode** and **light mode**.
- Essential integrations including - Authentication (**NextAuth**), Database (**Postgres** with **Prisma**), and Search (**Algolia**).
- Detailed and user-friendly documentation.
- Customizable plugins and add-ons.
- **TypeScript** compatibility.
- Plus, much more!

All these features and more make **NextAdmin** a robust, well-rounded solution for all your dashboard development needs.

## Update Logs

### Version 1.2.1 - [Mar 20, 2025]
- Fix Peer dependency issues and NextConfig warning.
- Updated apexcharts and react-apexhcarts to the latest version.

### Version 1.2.0 - Major Upgrade and UI Improvements - [Jan 27, 2025]

- Upgraded to Next.js v15 and updated dependencies
- API integration with loading skeleton for tables and charts.
- Improved code structure for better readability.
- Rebuilt components like dropdown, sidebar, and all ui-elements using accessibility practices.
- Using search-params to store dropdown selection and refetch data.
- Semantic markups, better separation of concerns and more.

### Version 1.1.0
- Updated Dependencies
- Removed Unused Integrations
- Optimized App

### Version 1.0
- Initial Release - [May 13, 2024]
