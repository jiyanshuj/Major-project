# 🚀 AI-Powered Educational Platform Suite

> A comprehensive collection of 8 production-ready applications transforming education through AI, machine learning, and cloud computing.

[![Live Demo](https://img.shields.io/badge/Demo-Live-success)](https://neuro-campus-73w8.vercel.app/)
[![React](https://img.shields.io/badge/React-19+-61DAFB?logo=react)](https://reactjs.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.10+-009688?logo=fastapi)](https://fastapi.tiangolo.com/)
[![AI Powered](https://img.shields.io/badge/AI-Gemini-4285F4?logo=google)](https://ai.google.dev/)

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Projects Portfolio](#-projects-portfolio)
- [Technology Stack](#-technology-stack)
- [Live Demos & Credentials](#-live-demos--credentials)
- [Key Features](#-key-features)
- [Getting Started](#-getting-started)
- [Project Architecture](#-project-architecture)
- [Statistics](#-statistics)

---

## 🎯 Overview

An integrated suite of educational applications designed for modern institutions, featuring AI-driven automation, real-time analytics, and seamless user experiences. Each application is production-ready with full-stack implementation.

### Portfolio Highlights

- **8 Production Applications** - Fully deployed and operational
- **AI-First Approach** - Google Gemini integration across platforms
- **Real-time Systems** - Live attendance, analytics, and updates
- **Secure & Scalable** - Cloud-based with enterprise-grade security
- **Modern Tech Stack** - React 19, FastAPI, TypeScript, Supabase

---

## 📦 Projects Portfolio

### 1. 🎓 NEURO CAMPUS - AI Campus Cloud Network

**The flagship platform** - A unified ecosystem integrating all educational services with AI-powered automation.

<details>
<summary><b>View Details</b></summary>

#### 🌐 Live Demo
[https://neuro-campus-73w8.vercel.app/](https://neuro-campus-73w8.vercel.app/)

**Demo Credentials:** `22100BTAIMLM11277` / `Yugyug@123`

#### Core Capabilities

**AI & ML Features**
- OCR-based attendance tracking
- AI content generation (PDF notes, PowerPoint)
- Intelligent exam paper generation
- Sentiment analysis for evaluations
- ML-powered performance predictions
- Automated document verification

**Multi-Panel Access**
- **Admin Panel** - Complete system oversight
- **Teacher Panel** - Attendance, evaluation, AI tools
- **Student Panel** - Attendance, canteen, resume builder, practice tests
- **Guest Panel** - University info, e-canteen access
- **Accounts Panel** - Financial management

**Core Modules**
- E-Library | E-Canteen | Student Forum
- Aptitude Tests | Resume Builder | Virtual Tour

#### Tech Stack
```
Frontend: React 18+, Tailwind CSS
Backend:  Supabase (Auth + PostgreSQL)
AI:       Google Generative AI (Gemini)
Hosting:  Vercel
```

</details>

---

### 2. 🚀 Smart Career Guidance System

**AI-powered career assessment** - Intelligent skill evaluation with personalized career path recommendations.

<details>
<summary><b>View Details</b></summary>

#### 🌐 Live Demo
[https://smart-career-guidance-system.vercel.app/](https://smart-career-guidance-system.vercel.app/)

#### Features
- 30-question adaptive quizzes across 6 domains
- AI-generated questions using Gemini
- Comprehensive analytics and performance tracking
- Domain coverage: OS, DBMS, Networks, Aptitude, Verbal, Programming

#### Tech Stack
```
Frontend: React 19.2 + TypeScript
Backend:  Flask 3.0
Database: Supabase (PostgreSQL)
AI:       Google Gemini API
Auth:     Clerk
Hosting:  Vercel
```

#### Sample Screens
- Interactive quiz interface with progress tracking
- Real-time performance analysis
- Domain-wise skill visualization

</details>

---

### 3. 📄 NextStep CV - AI Resume Generator

**Professional resume builder** - Create ATS-optimized resumes with AI-powered optimization in seconds.

<details>
<summary><b>View Details</b></summary>

#### Key Features
- Multi-step intelligent form interface
- AI-powered content optimization (Gemini API)
- Professional ATS-friendly templates
- PDF/Word export functionality
- Real-time validation and preview
- Dark mode support

#### Form Sections
Basic Info | Projects | Education | Experience | Skills | Certifications

#### Tech Stack
```
Frontend: React 19.1 + TypeScript + Vite 7.1
Styling:  Tailwind CSS 3.4
Backend:  Python Flask
AI:       Google Gemini API
Export:   python-docx
```

</details>

---

### 4. 👨‍💼 Admin Panel - Student & Teacher Management

**Facial recognition system** - Manage student and teacher attendance with advanced facial recognition.

<details>
<summary><b>View Details</b></summary>

#### Capabilities

**Student Management**
- Registration with detailed profiles
- Facial recognition training
- Real-time attendance marking
- Session analytics (by section/semester)

**Teacher Management**
- Registration and profile management
- Facial recognition enrollment
- Data viewing and management

#### Tech Stack
```
Frontend: React 19.1 + Vite 7.1 + Tailwind CSS 3.4
Icons:    Lucide React 0.548
Backend:  FastAPI (via ngrok tunneling)
ML:       Face Recognition, OpenCV
```

</details>

---

### 5. 👨‍🏫 Teacher Panel - Attendance & Grade Management

**Teacher dashboard** - Comprehensive teaching management with facial recognition integration.

<details>
<summary><b>View Details</b></summary>

#### Features
- Secure authentication with Supabase
- Password reset enforcement on first login
- Profile management
- Facial recognition-based attendance
- Grade and subject management
- Academic calendar integration
- Student roster access
- Real-time data updates

#### Tech Stack
```
Frontend:  React 18.3 + TypeScript 5.5
Build:     Vite 5.4
Styling:   Tailwind CSS 3.4
Animation: Framer Motion 12.23
Backend:   Supabase (Auth + Database)
Security:  bcryptjs 3.0
```

</details>

---

### 6. 🎯 AutoSlideX - AI Presentation Generator

**Intelligent PowerPoint creator** - Generate professional presentations from topics using Gemini AI.

<details>
<summary><b>View Details</b></summary>

#### Features
- AI-powered content generation
- Multiple professional templates
- Interactive editing interface
- Real-time slide customization
- PowerPoint export (.pptx)
- Responsive design with animations

#### Tech Stack
```
Frontend: React + Vite + Tailwind CSS
Icons:    Lucide React
Backend:  FastAPI
AI:       Google Generative AI (Gemini)
Export:   python-pptx
```

#### Workflow
1. Enter topic and slide count
2. AI generates structured content
3. Preview and customize slides
4. Download as PowerPoint

</details>

---

### 7. 📝 PaperVista - AI Exam Paper Generator

**Automated exam creation** - Generate customized, high-quality exam papers for educators.

<details>
<summary><b>View Details</b></summary>

#### Features
- Multiple exam types (MST-1, MST-2, End-Semester)
- Customizable parameters (course, semester, topics)
- Structured output with parts and marks distribution
- Real-time AI processing
- Print-ready format

#### Configuration Options
Course Code | Semester | Subject | Department | Exam Period

#### Tech Stack
```
Frontend:   React 19.1 + Vite 7.1 + Tailwind CSS 3.4
Backend:    FastAPI 0.115 + Uvicorn 0.32
AI:         Google Generative AI 0.8
Validation: Pydantic 2.9
Python:     3.11.9
```

</details>

---

### 8. 🎓 Facial Recognition Attendance Backend

**Intelligent attendance system** - Automated attendance using real-time facial recognition.

<details>
<summary><b>View Details</b></summary>

#### Core Functionality
- User management (students, teachers, guests)
- Face enrollment and storage
- Real-time facial recognition
- Attendance session management
- Automatic absent marking
- Detailed reports and analytics
- Subject-based tracking

#### Advanced Features
- Multi-face recognition
- Attendance history and patterns
- Low attendance alerts
- Daily automated reports
- Guest access management

#### Tech Stack
```
Framework:         FastAPI
Face Recognition:  face_recognition, dlib, OpenCV
Database:          Supabase (PostgreSQL)
Storage:           Cloudinary (Image CDN)
ML:                NumPy, scikit-learn
Server:            Uvicorn (ASGI)
Python:            3.10+
```

#### Key Dependencies
```
numpy==1.24.3
face-recognition==1.2.3
opencv-python-headless==4.8.1.78
fastapi==0.104.1
supabase==2.3.0
cloudinary==1.36.0
```

</details>

---

## 🛠️ Technology Stack

### Frontend Ecosystem

| Technology | Version | Purpose |
|-----------|---------|---------|
| **React** | 18-19+ | UI Framework |
| **TypeScript** | 5.5+ | Type Safety |
| **Vite** | 5-7+ | Build Tool |
| **Tailwind CSS** | 3.4+ | Styling |
| **Framer Motion** | 12+ | Animations |
| **Lucide React** | 0.3-0.5+ | Icons |
| **Clerk** | Latest | Authentication |

### Backend Ecosystem

| Technology | Version | Purpose |
|-----------|---------|---------|
| **FastAPI** | 0.10+ | Async Framework |
| **Flask** | 3.0+ | Web Framework |
| **Python** | 3.8-3.11 | Runtime |
| **Uvicorn** | 0.24+ | ASGI Server |
| **Pydantic** | 2.9+ | Data Validation |

### AI & Machine Learning

| Service | Application |
|---------|-------------|
| **Google Gemini API** | Content generation, Q&A, optimization |
| **face_recognition** | Facial detection and recognition |
| **OpenCV** | Computer vision processing |
| **dlib** | Machine learning algorithms |
| **NumPy** | Numerical computations |
| **scikit-learn** | ML utilities |

### Cloud & Database

| Service | Purpose |
|---------|---------|
| **Supabase** | PostgreSQL Database + Authentication |
| **Cloudinary** | Image hosting and CDN |
| **Vercel** | Frontend deployment |

### Additional Tools

- **PostCSS** - CSS transformation
- **ESLint** - Code quality
- **bcryptjs** - Password hashing
- **python-pptx** - PowerPoint generation
- **python-docx** - Word documents

---

## 🌐 Live Demos & Credentials

### Live Applications

| Application | URL |
|------------|-----|
| **NEURO CAMPUS** | [neuro-campus-73w8.vercel.app](https://neuro-campus-73w8.vercel.app/) |
| **Career Guidance** | [smart-career-guidance-system.vercel.app](https://smart-career-guidance-system.vercel.app/) |

### Demo Accounts

#### Teacher Panel
```
Username: T002
Password: Kamal@123
```

#### Student Panel (NEURO CAMPUS)
```
Username: 22100BTAIML11253
Password: Jain@123
```

#### Student Panel (Career Guidance)
```
Username: 22100BTAIMLM11277
Password: Yugyug@123
```

#### Student Forum
```
Enrollment: 22100BTAIML11253
Email: [Use your own email]
```

> **Note:** For platforms requiring authentication, create a new account if demo credentials don't work.

---

## ✨ Key Features

### AI & Automation
- ✅ AI content generation (Gemini API)
- ✅ Automated exam paper creation
- ✅ AI resume optimization
- ✅ Intelligent career guidance
- ✅ Facial recognition attendance
- ✅ Sentiment analysis
- ✅ OCR document processing
- ✅ Performance predictions

### Security & Authentication
- ✅ Supabase Authentication
- ✅ Clerk Authentication
- ✅ bcrypt password hashing
- ✅ JWT token management
- ✅ Role-based access control (RBAC)
- ✅ Secure API endpoints

### Data Management
- ✅ PostgreSQL database (Supabase)
- ✅ Real-time data synchronization
- ✅ Cloud file storage (Cloudinary)
- ✅ Comprehensive analytics
- ✅ Data export capabilities

### User Experience
- ✅ Fully responsive (mobile-first)
- ✅ Modern UI with Tailwind CSS
- ✅ Dark mode support
- ✅ Smooth animations
- ✅ Interactive components
- ✅ Real-time feedback

---

## 🚀 Getting Started

### Prerequisites

```bash
Node.js >= 18.x
Python >= 3.8
npm or yarn
pip
```

### Frontend Setup

```bash
# Clone repository
git clone <repository-url>
cd <project-folder>

# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

### Backend Setup

```bash
# Navigate to backend directory
cd backend

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run server
python main.py

# Or with auto-reload
uvicorn main:app --reload
```

### Environment Configuration

Create `.env` files in appropriate directories:

**Frontend (.env)**
```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_key
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_key
VITE_API_URL=your_backend_url
```

**Backend (.env)**
```env
GEMINI_API_KEY=your_gemini_key
SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_service_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

> **Note:** Obtain API keys from respective service providers (Supabase, Google AI Studio, Cloudinary, Clerk)

---

## 🏗️ Project Architecture

### System Integration Flow

```
┌─────────────────────────────────────────────────────────────┐
│                        NEURO CAMPUS                         │
│                    (Central Hub Platform)                   │
└──────────────┬──────────────────────────────┬───────────────┘
               │                              │
       ┌───────┴────────┐            ┌────────┴─────────┐
       │                │            │                  │
┌──────▼──────┐  ┌──────▼──────┐   ┌▼────────┐  ┌──────▼──────┐
│Admin Panel  │  │Teacher Panel│   │Resume   │  │Career       │
│             │  │             │   │Generator│  │Guidance     │
└──────┬──────┘  └──────┬──────┘   └─────────┘  └─────────────┘
       │                │
       └────────┬───────┘
                │
        ┌───────▼────────┐
        │   Facial       │
        │   Recognition  │
        │   Backend      │
        └────────────────┘

┌─────────────────────────────────────────────────────────────┐
│              AI Services Layer (Google Gemini)              │
│  ┌──────────┐  ┌──────────┐  ┌──────────┐  ┌──────────┐   │
│  │AutoSlideX│  │PaperVista│  │ Career   │  │ Resume   │   │
│  │          │  │          │  │ Guidance │  │ Builder  │   │
│  └──────────┘  └──────────┘  └──────────┘  └──────────┘   │
└─────────────────────────────────────────────────────────────┘
```

### Project Interconnections

1. **Admin Panel** ↔ **Facial Recognition Backend**
   - Student/teacher enrollment
   - Facial training data management

2. **Teacher Panel** ↔ **Facial Recognition Backend**
   - Real-time attendance marking
   - Session management

3. **NEURO CAMPUS** → **All Systems**
   - Central authentication
   - Unified student/teacher profiles

4. **Career Guidance** ↔ **NEURO CAMPUS**
   - Career insights integration
   - Student progress tracking

5. **Resume Generator** ↔ **NEURO CAMPUS**
   - Student profile data
   - Resume building service

6. **AutoSlideX + PaperVista** ↔ **NEURO CAMPUS**
   - Teacher content generation tools
   - Educational resource creation

---

## 📊 Statistics

### Portfolio Metrics

| Metric | Count |
|--------|-------|
| **Total Applications** | 8 |
| **Frontend Projects** | 5 |
| **Backend Services** | 3 |
| **AI Integrations** | 5 |
| **Live Deployments** | 2+ |
| **Total Dependencies** | 70+ |
| **Lines of Code** | 50,000+ |

### Technology Distribution

**Frontend:** 62.5% (5 projects)
**Backend:** 37.5% (3 projects)
**Full-Stack:** 100% (integrated systems)

### Feature Coverage

- **AI-Powered:** 62.5% of projects
- **Authentication:** 100% of projects
- **Real-time Features:** 75% of projects
- **Cloud-Hosted:** 100% of projects
- **Mobile Responsive:** 100% of projects

---

## 📚 Documentation

Each project includes comprehensive documentation:

- **README.md** - Project overview, setup, features
- **API Documentation** - Endpoint specifications
- **Environment Setup** - Configuration guides
- **Deployment Guides** - Production deployment steps
- **User Manuals** - End-user documentation

---

## 🎯 Use Cases

### For Educational Institutions
- Complete campus management
- Automated attendance tracking
- Student performance analytics
- Resource management

### For Teachers
- Attendance automation
- Content generation tools
- Grade management
- Student evaluation

### For Students
- Career guidance
- Resume building
- Aptitude practice
- Digital library access

### For Administrators
- System oversight
- Analytics and reporting
- User management
- Financial tracking

---

## 🔒 Security Features

- **Authentication:** Multi-provider (Supabase, Clerk)
- **Authorization:** Role-based access control
- **Encryption:** bcrypt password hashing
- **API Security:** JWT tokens, rate limiting
- **Data Protection:** HTTPS, secure storage
- **Privacy:** GDPR-compliant data handling

---

## 🚀 Performance Optimizations

- **Frontend:** Code splitting, lazy loading, image optimization
- **Backend:** Async operations, connection pooling, caching
- **Database:** Indexed queries, optimized schemas
- **AI:** Batch processing, response caching
- **CDN:** Cloudinary for static assets

---

## 🔄 Future Enhancements

### Planned Features
- [ ] Mobile applications (React Native)
- [ ] Advanced analytics dashboard
- [ ] Multi-language support
- [ ] Blockchain-based certificates
- [ ] IoT integration for smart classrooms
- [ ] Video conferencing integration
- [ ] Advanced AI tutoring system
- [ ] Parent portal

### Under Development
- [ ] API rate limiting improvements
- [ ] Enhanced facial recognition accuracy
- [ ] Real-time collaboration features
- [ ] Advanced reporting tools

---

## 🤝 Contributing

Contributions are welcome! Please follow these guidelines:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

These projects are developed as part of an educational portfolio. Individual projects may have specific licenses - refer to respective repositories for details.

---

## 📧 Contact & Support

For questions, support, or collaboration:

- **Issues:** Use GitHub Issues for bug reports
- **Discussions:** GitHub Discussions for feature requests
- **Email:** [Contact through repository]

---

## 🙏 Acknowledgments

- **Google AI** - Gemini API for AI capabilities
- **Supabase** - Database and authentication services
- **Vercel** - Hosting and deployment platform
- **Cloudinary** - Image hosting and CDN
- **Open Source Community** - Various libraries and tools

---

<div align="center">

### ⭐ Star this repository if you find it helpful!

### 🌟 Built with Passion Using Modern Technologies

**React • TypeScript • FastAPI • Supabase • Google Gemini • Tailwind CSS**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

---

**© 2026 Educational Platform Suite**

*Transforming Education Through AI and Innovation*

**[⬆ Back to Top](#-ai-powered-educational-platform-suite)**

</div>