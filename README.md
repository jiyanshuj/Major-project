# 🚀 Major Project Portfolio - Complete Overview

Welcome to a comprehensive suite of modern, AI-powered educational and productivity applications. This portfolio showcases multiple full-stack projects built with cutting-edge technologies.

---

## 📑 Table of Contents

1. [Project Overview](#project-overview)
2. [Complete Project Catalog](#complete-project-catalog)
3. [Technology Stack Summary](#technology-stack-summary)
4. [Quick Links & Features](#quick-links--features)
5. [Project Showcase](#project-showcase)

---

## 🎯 Project Overview

This workspace contains 8 major applications designed for educational institutions, student development, and academic management. Each project is a fully-functional, production-ready application with frontend and backend components.

### 📊 Projects At a Glance

| Project | Purpose | Tech Stack | Status |
|---------|---------|-----------|--------|
| **NEURO CAMPUS** | AI-powered campus cloud network | React + Supabase + Gemini AI | ✅ Live |
| **Smart Career Guidance System** | Career path assessment & guidance | React + Flask + Gemini AI | ✅ Live |
| **Resume Gen** | AI resume builder | React/TypeScript + Flask | ✅ Live |
| **Admin Panel** | Student & teacher management | React + FastAPI | ✅ Live |
| **Teacher Panel** | Teacher dashboard & attendance | React/TypeScript + Supabase | ✅ Live |
| **AutoSlideX** | AI presentation generator | React + FastAPI + Gemini | ✅ Live |
| **PaperVista** | AI exam paper generator | React + FastAPI + Gemini | ✅ Live |
| **Facial Recognition Backend** | Attendance system backend | FastAPI + ML | ✅ Live |

---

## 📋 Complete Project Catalog

### 1. 🎓 NEURO CAMPUS - AI & ML Based Campus Cloud Network

**Description:** A comprehensive educational platform integrating AI, ML algorithms, and cloud computing to create a unified ecosystem for students, teachers, administrators, and guests.

**Live Demo:** https://neuro-campus-73w8.vercel.app/

#### Demo Credentials
- **Student Panel:** `22100BTAIMLM11277` / `Yugyug@123`

#### Key Features
✨ **AI & ML Powered Features**
- OCR-Based Attendance System
- AI Content Generation (PDF notes & PowerPoint presentations)
- Intelligent Question Paper Generator
- Sentiment Analysis for teacher evaluation
- Performance Analytics with ML-based predictions
- Document Verification with OCR

👥 **Multi-Panel System**
- Admin Panel (full management oversight)
- Teacher Panel (attendance, evaluation, AI tools)
- Student Panel (attendance, canteen, resume builder, aptitude practice)
- Guest Panel (university details, e-canteen)
- Accounts Panel (financial management)

🎯 **Core Modules**
- E-Library (digital library management)
- E-Canteen (online ordering)
- Student Forum (social community)
- Aptitude Tests (AI-driven practice)
- Resume Builder (AI-assisted)
- Virtual Campus Tour

#### Technology Stack
- **Frontend:** React 18+, Tailwind CSS
- **Backend:** Supabase (Database & Auth)
- **AI Services:** Google Generative AI
- **Hosting:** Vercel

---

### 2. 🚀 Smart Career Guidance System

**Description:** An AI-powered career guidance platform that helps students discover their ideal career path through intelligent skill assessments and personalized recommendations.

**Live Demo:** https://smart-career-guidance-system.vercel.app/

#### Key Features
- 🎯 30-Question Adaptive Quizzes covering 6 domains
- 🤖 Google Gemini AI for intelligent question generation
- 📊 Comprehensive Analytics with detailed performance breakdowns
- 💾 Cloud Database (Supabase)
- 🔐 Secure Authentication (Clerk)
- 📱 Fully Responsive Design
- ⚡ Production-Ready & Scalable

#### Quiz Domains
1. Operating Systems (OS)
2. Database Management Systems (DBMS)
3. Computer Networks
4. Aptitude
5. Verbal Communication
6. Programming Languages

#### Technology Stack
- **Frontend:** React 19.2.0 + TypeScript
- **Backend:** Flask 3.0.0
- **Database:** Supabase (PostgreSQL)
- **AI:** Google Gemini API
- **Auth:** Clerk
- **Hosting:** Vercel

#### Screenshots
![Home Page](Smart%20Career%20Guidance%20System/images/home-page.png)
*Landing page with animated background and quick navigation*

![Authentication](Smart%20Career%20Guidance%20System/images/Auth.png)
*Secure sign-in powered by Clerk*

![Quiz Configuration](Smart%20Career%20Guidance%20System/images/Langauge-level.png)
*Select difficulty level and programming language*

![Progress Tracking](Smart%20Career%20Guidance%20System/images/Progress-bar.png)
*Real-time progress tracking and quiz history*

![Quiz Questions](Smart%20Career%20Guidance%20System/images/Questions.png)
*Interactive multiple-choice questions*

![Performance Analysis](Smart%20Career%20Guidance%20System/images/Performance.png)
*Domain-wise performance visualization*

---

### 3. 📄 NextStep CV - Resume Generator

**Description:** A modern, full-stack resume generation platform that leverages AI and smart form handling to create professional, ATS-optimized resumes in seconds.

#### Key Features
✨ **Smart Resume Builder** - Intuitive multi-step form interface
🤖 **AI-Powered Optimization** - Gemini API integration for evaluation
📄 **Professional Templates** - Modern, ATS-optimized designs
🔐 **User Authentication** - Secure login with bcrypt encryption
💾 **PDF/Word Export** - Download in multiple formats
🎨 **Modern UI** - Dark mode, responsive design, Tailwind CSS
⚡ **Real-time Updates** - Instant form validation

#### Form Sections
- Basic Information (name, email, LinkedIn, GitHub, summary)
- Projects (title, description, technologies, links)
- Education (degree, institution, duration)
- Work Experience (company, role, responsibilities)
- Skills (categorized skills)
- Certifications (professional certifications)

#### Technology Stack
- **Frontend:** React 19.1.1 + TypeScript
- **Build Tool:** Vite 7.1.7
- **Styling:** Tailwind CSS 3.4.18
- **Backend:** Python Flask
- **AI:** Google Gemini API
- **Document Processing:** python-docx

#### Screenshots
![Hero Section](Resume%20Gen/images/01-hero-section.png)
*Landing page with dynamic gradient background*

![Basic Information](Resume%20Gen/images/02-resume-form-basic-info.png)
*Resume form - Basic information section*

![Projects Section](Resume%20Gen/images/03-projects-section.png)
*Resume form - Projects section*

![Education Section](Resume%20Gen/images/04-education-section.png)
*Resume form - Education details*

![Work Experience](Resume%20Gen/images/05-work-experience-certifications.png)
*Resume form - Work experience and certifications*

![Skills Section](Resume%20Gen/images/06-skills-section.png)
*Resume form - Skills categorization*

---

### 4. 👨‍💼 Admin Panel

**Description:** A React-based admin panel for managing student and teacher attendance using facial recognition technology.

#### Key Features

**Student Module**
- Student Registration with details capture
- Facial Recognition Training for accurate recognition
- Real-time Attendance Marking via facial recognition
- Data Management (view and manage student records)
- Session Analytics (analyze attendance by section/semester)

**Teacher Module**
- Teacher Registration and profile management
- Teacher Recognition using facial recognition
- Data Viewing of stored teacher information

#### Technology Stack
- **Frontend:** React 19.1.1, Vite 7.1.7
- **Styling:** Tailwind CSS 3.4.18
- **Icons:** Lucide React 0.548.0
- **Backend:** Python FastAPI via ngrok tunneling
- **Build:** Vite, PostCSS

#### API Configuration
Uses ngrok for secure tunneling to Python backend for facial recognition services.

---

### 5. 👨‍🏫 Teacher Panel

**Description:** A comprehensive React + TypeScript teacher management and attendance tracking system with facial recognition integration.

#### Key Features
- 🔐 Teacher Authentication (Supabase)
- 🔄 Password Management (forced reset on first login)
- 👤 Profile Management
- 📊 Attendance Tracking (facial recognition-based)
- 📋 Grade Management
- 📅 Academic Calendar
- 📚 Subject Management
- 👥 Student Roster
- ⚡ Real-time Data & Live Updates

#### Technology Stack
- **Frontend:** React 18.3.1 + TypeScript 5.5.3
- **Build Tool:** Vite 5.4.2
- **Styling:** Tailwind CSS 3.4.1
- **Animation:** Framer Motion 12.23.12
- **Backend:** Supabase (Auth + Database)
- **Icons:** Lucide React 0.344.0
- **Security:** bcryptjs 3.0.2

---

### 6. 🎯 AutoSlideX - Intelligent PowerPoint Presentation Generator

**Description:** A full-stack application that leverages Google's Gemini AI to automatically generate professional PowerPoint presentations from simple topics.

**Key Features**
✨ **AI-Powered Content Generation** - Gemini AI for automatic slide creation
🎨 **Professional Templates** - Multiple design templates
📊 **Interactive UI** - Modern, responsive interface with animations
💾 **Download Capability** - Export as PowerPoint files
🔄 **Real-time Editing** - Customize slides before export
🚀 **Fast Performance** - Optimized backend with fallback mechanisms

#### Technology Stack
- **Frontend:** React + Vite
- **Styling:** Tailwind CSS
- **Icons:** Lucide React
- **Backend:** FastAPI
- **AI:** Google Generative AI (Gemini)
- **Document:** python-pptx for PowerPoint generation

#### Screenshots
![Home Page](AutoSlideX/images/Home.png)
*Main interface - Enter topic and slide count*

![Preview](AutoSlideX/images/Preveiw.png)
*Slide preview before downloading*

![New Slide](AutoSlideX/images/New-slide.png)
*Create and customize individual slides*

![Download](AutoSlideX/images/Download.png)
*Export presentation as PPTX*

![Final PPT](AutoSlideX/images/Final-ppt.png)
*Generated PowerPoint presentation*

---

### 7. 📝 PaperVista - AI-Powered Exam Paper Generator

**Description:** A full-stack web application that leverages Google's Gemini AI to generate high-quality, customized exam papers for educators.

#### Key Features
- **AI-Powered Question Generation** - Gemini API for intelligent questions
- **Multiple Exam Types** - MST-1, MST-2, End-Semester
- **Customizable Parameters** - Course details, topics, configurations
- **Structured Output** - Organized format with parts and marks
- **Responsive Design** - Works on desktop and tablet
- **Real-time Processing** - Fast generation with optimized API usage

#### Exam Configuration
- Course Code
- Semester
- Subject Name
- Department
- Examination Period

#### Technology Stack
- **Frontend:** React 19.1.1, Vite 7.1.7, Tailwind CSS 3.4.18
- **Backend:** FastAPI 0.115.0, Uvicorn 0.32.0
- **AI:** Google Generative AI 0.8.3
- **Data Validation:** Pydantic 2.9.2
- **Python:** 3.11.9

#### Screenshots
![Exam Type Selection](PaperVista/images/Exam-type.png)
*Select exam type and specify course details*

![Topic Configuration](PaperVista/images/Topic.png)
*Configure exam topics and parameters*

![Overview](PaperVista/images/Overveiw.png)
*Main dashboard interface*

![Print Paper](PaperVista/images/Print-paper.png)
*Generate, preview, and print exam papers*

---

### 8. 🎓 Facial Recognition Attendance System (Backend)

**Description:** An intelligent attendance management system using facial recognition to automatically mark student attendance during classes.

#### Core Functionality
- **User Management** - Students, teachers, guests
- **Face Enrollment** - Capture and store student face images
- **Face Recognition** - Real-time facial recognition
- **Attendance Sessions** - Create and manage class-based sessions
- **Automatic Absent Marking** - Auto-mark students absent at session start
- **Attendance Reports** - Detailed statistics and reports
- **Subject-based Tracking** - Track per subject, section, semester

#### Advanced Features
- 🔍 Multi-face Recognition
- 📊 Attendance History & Patterns
- 🚨 Low Attendance Alerts
- 📅 Daily Reports
- 👤 Guest Management

#### Technology Stack
- **Framework:** FastAPI
- **Face Recognition:** face_recognition, dlib, OpenCV
- **Database:** Supabase (PostgreSQL)
- **Storage:** Cloudinary
- **ML:** NumPy, scikit-learn
- **Server:** Uvicorn (ASGI)
- **Python:** 3.10+

#### Key Dependencies
- numpy==1.24.3
- face-recognition==1.2.3
- opencv-python-headless==4.8.1.78
- fastapi==0.104.1
- supabase==2.3.0
- cloudinary==1.36.0

---

## 🛠️ Technology Stack Summary

### Frontend Technologies
| Technology | Version | Usage |
|-----------|---------|-------|
| React | 18-19+ | UI framework |
| React + TypeScript | 18+ | Type-safe React |
| Vite | 5-7+ | Build tool & dev server |
| Tailwind CSS | 3.4+ | Utility CSS framework |
| Lucide React | 0.3-0.5+ | Icon library |
| Framer Motion | 12+ | Animation library |
| Clerk | Latest | Authentication |

### Backend Technologies
| Technology | Version | Usage |
|-----------|---------|-------|
| FastAPI | 0.10+ | Async web framework |
| Flask | 3.0+ | Web framework |
| Python | 3.8-3.11 | Runtime |
| Uvicorn | 0.24+ | ASGI server |

### AI & ML Technologies
| Service | Usage |
|---------|-------|
| Google Gemini API | Content & question generation |
| face_recognition | Facial recognition |
| OpenCV | Computer vision |
| dlib | Machine learning |

### Database & Cloud
| Service | Usage |
|---------|-------|
| Supabase | Database (PostgreSQL) & Auth |
| Cloudinary | Image hosting & CDN |
| Vercel | Frontend hosting |

### Additional Tools
- PostCSS - CSS transformation
- ESLint - Code linting
- bcryptjs - Password hashing
- python-pptx - PowerPoint generation
- python-docx - Word document generation

---

## 🎯 Quick Links & Features

### 🌐 Live Deployments
- **NEURO CAMPUS:** https://neuro-campus-73w8.vercel.app/
- **Smart Career Guidance:** https://smart-career-guidance-system.vercel.app/

### 🔑 Demo Credentials
- **Student (NEURO CAMPUS):** Roll No: `22100BTAIMLM11277`, Password: `Yugyug@123`

### 🚀 Key Features Across All Projects

#### AI & Automation
- ✅ AI-powered content generation (Gemini API)
- ✅ Automated exam paper creation
- ✅ AI resume optimization
- ✅ Intelligent career guidance
- ✅ Facial recognition attendance
- ✅ Sentiment analysis
- ✅ OCR document processing

#### Security & Authentication
- ✅ Supabase Authentication
- ✅ Clerk Authentication
- ✅ bcrypt password hashing
- ✅ JWT tokens
- ✅ Role-based access control

#### Data Management
- ✅ PostgreSQL database (Supabase)
- ✅ Real-time data updates
- ✅ Cloud file storage (Cloudinary)
- ✅ Comprehensive analytics

#### User Experience
- ✅ Responsive design (mobile-first)
- ✅ Modern UI with Tailwind CSS
- ✅ Dark mode support
- ✅ Smooth animations
- ✅ Interactive components

---

## 📸 Project Showcase

### Smart Career Guidance System

<div align="center">

**Quiz Progress & Analytics**

![Progress Bar](Smart%20Career%20Guidance%20System/images/Progress-bar.png)

Real-time progress tracking with comprehensive quiz attempt history

</div>

<div align="center">

**Performance Visualization**

![Performance Analysis](Smart%20Career%20Guidance%20System/images/Performance.png)

Domain-wise performance breakdown and analytics

</div>

### Resume Generator

<div align="center">

**Form Interface**

![Resume Form](Resume%20Gen/images/02-resume-form-basic-info.png)

Intuitive multi-section resume builder

</div>

<div align="center">

**Skills Section**

![Skills](Resume%20Gen/images/06-skills-section.png)

Comprehensive skills categorization and management

</div>

### AutoSlideX - Presentation Generator

<div align="center">

**Presentation Creation**

![AutoSlideX Home](AutoSlideX/images/Home.png)

AI-powered presentation generation interface

</div>

<div align="center">

**Generated Output**

![Final Presentation](AutoSlideX/images/Final-ppt.png)

Professional PowerPoint presentations created with Gemini AI

</div>

### PaperVista - Exam Paper Generator

<div align="center">

**Exam Configuration**

![Exam Type](PaperVista/images/Exam-type.png)

Configure course details and exam type

</div>

<div align="center">

**Generated Papers**

![Print Paper](PaperVista/images/Print-paper.png)

Ready-to-print exam papers in professional format

</div>

---

## 📊 Project Statistics

- **Total Projects:** 8
- **Frontend Applications:** 5
- **Backend Services:** 3
- **AI Integrations:** 5 projects
- **Database Systems:** Supabase (PostgreSQL)
- **Live Deployments:** 2+ (Vercel)
- **Total Frontend Dependencies:** 50+
- **Total Backend Dependencies:** 20+

---

## 🔄 Workflow & Integration

### Project Interconnections
1. **Admin Panel** ↔ **Facial Recognition Backend** - Attendance & facial training
2. **Teacher Panel** ↔ **Facial Recognition Backend** - Real-time attendance marking
3. **NEURO CAMPUS** → All Systems - Central hub for student/teacher management
4. **Smart Career Guidance** ↔ **NEURO CAMPUS** - Career insights integration
5. **Resume Gen** ↔ **NEURO CAMPUS** - Resume building for students
6. **AutoSlideX** ↔ **NEURO CAMPUS** - Presentation generation service
7. **PaperVista** ↔ **NEURO CAMPUS** - Exam paper generation service

---

## 🚀 Getting Started

### For Developers

#### Frontend Development
```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Run lint checks
npm run lint
```

#### Backend Development
```bash
# Install dependencies
pip install -r requirements.txt

# Run FastAPI/Flask server
python main.py

# Development with auto-reload
uvicorn main:app --reload
```

### Environment Setup

Each project requires specific environment variables. Check individual README files for:
- Supabase credentials
- Google Gemini API keys
- Cloudinary credentials
- Ngrok URLs (for backend tunneling)
- Clerk authentication keys

---

## 📚 Documentation

Each project includes comprehensive documentation:
- **README.md** - Project overview and setup
- **TECHNICAL_SPECIFICATIONS.md** - Detailed specifications
- **API Documentation** - Backend endpoints and usage
- **Environment Configuration** - Setup guides

---

## ✨ Key Achievements

✅ **Full-Stack Applications** - Complete end-to-end solutions  
✅ **AI Integration** - Google Gemini API for intelligent features  
✅ **Scalable Architecture** - Cloud-based services and databases  
✅ **Modern Tech Stack** - Latest frameworks and tools  
✅ **Responsive Design** - Works on all device sizes  
✅ **Production Ready** - Live deployments and monitoring  
✅ **Security First** - Authentication, encryption, and data protection  
✅ **Performance Optimized** - Fast loading and smooth interactions  

---

## 📝 License

These projects are developed as part of educational portfolio work. Refer to individual project repositories for specific license information.

---

## 📧 Contact & Support

For questions or support regarding any of these projects, please refer to individual project documentation or contact the development team.

---

<div align="center">

### 🌟 Built with ❤️ using Modern Web Technologies

**React • TypeScript • FastAPI • Supabase • Google Gemini • Tailwind CSS**

*Last Updated: February 2026*

</div>
