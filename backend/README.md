# Facial Recognition Attendance System

An intelligent attendance management system that uses facial recognition to automatically mark student attendance during classes. Built with FastAPI, face_recognition, and integrated with cloud services for robust and scalable deployment.

## 🎯 Project Overview

This system automates the attendance tracking process by:
- **Capturing student faces** during enrollment
- **Training ML models** to recognize individual students
- **Recognizing faces** in real-time during classes
- **Managing attendance sessions** with automatic absent marking
- **Generating reports** on attendance patterns and statistics

## 📋 Features

### Core Functionality
- **User Management**: Support for students, teachers, and guests
- **Face Enrollment**: Capture and store student face images
- **Face Recognition**: Real-time facial recognition for attendance marking
- **Attendance Sessions**: Create and manage class-based attendance sessions
- **Automatic Absent Marking**: Auto-marks students absent at session start
- **Attendance Reports**: Generate detailed attendance statistics and reports
- **Subject-based Tracking**: Track attendance per subject, section, and semester

### Advanced Features
- **Multi-face Recognition**: Recognize multiple students in a single image
- **Attendance History**: Track student attendance patterns over time
- **Low Attendance Alerts**: Identify students with attendance below threshold
- **Daily Reports**: Generate attendance reports for specific dates
- **Guest Management**: Support for guest attendance with temporary tokens

## 🏗️ Architecture

### Project Structure
```
backend/
├── main.py                 # FastAPI application and REST API endpoints
├── attendance.py           # Attendance session and marking logic
├── capture.py             # Image capture and cloud upload functionality
├── train.py               # Face model training and recognition
├── test.py                # Face recognition testing and validation
├── db.py                  # Database and Supabase integration
├── requirements.txt       # Python dependencies
├── Dockerfile             # Docker containerization
├── test_attendance.py     # Unit tests for attendance module
├── test_connection.py     # Database connection tests
└── test.py                # Recognition model tests
```

### Technology Stack

**Backend Framework**
- FastAPI: Modern async web framework
- Uvicorn: ASGI server

**Face Recognition**
- face_recognition: Deep learning-based facial recognition
- dlib: Machine learning library
- OpenCV: Computer vision operations
- NumPy: Numerical computing

**Cloud Services**
- Supabase: Database and file storage (PostgreSQL)
- Cloudinary: Image hosting and CDN

**Infrastructure**
- Docker: Containerization
- Python 3.10+: Runtime environment

## 📦 Dependencies

```
numpy==1.24.3
dlib-bin==19.24.6
face-recognition==1.2.3
opencv-python-headless==4.8.1.78
fastapi==0.104.1
uvicorn[standard]==0.24.0
python-multipart==0.0.6
cloudinary==1.36.0
supabase==2.3.0
python-dotenv==1.0.0
requests==2.31.0
```

## 🚀 Getting Started

### Prerequisites
- Python 3.10 or higher
- Docker (optional, for containerization)
- Supabase account and credentials
- Cloudinary account and credentials

### Installation

1. **Clone the repository**
```bash
cd backend
```

2. **Create environment file** (.env)
```env
SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Run the application**
```bash
uvicorn main:app --host 0.0.0.0 --port 8000
```

The API will be available at `http://localhost:8000`

### Expose with Ngrok (Optional)

To expose your local server to the internet for remote access:

1. **Install ngrok** (if not already installed)
```bash
# Download from https://ngrok.com/download
# Or use package manager
choco install ngrok  # Windows
brew install ngrok   # macOS
apt install ngrok    # Linux
```

2. **Open a new terminal** and start ngrok tunnel
```bash
ngrok http 8000
```

3. **Copy the public URL** provided by ngrok
```
Forwarding  https://xxxx-xxx-xxx-xxx.ngrok.io -> http://localhost:8000
```

Now your API is accessible publicly at the ngrok URL. Share this URL with frontend applications or external services that need to communicate with your backend.

**Note**: 
- Keep both terminals running (main app + ngrok)
- The ngrok URL changes each time you restart (unless you have a paid account)
- Useful for testing with mobile apps or remote frontends

### Docker Deployment

1. **Build the Docker image**
```bash
docker build -t attendance-system .
```

2. **Run the container**
```bash
docker run -p 8000:8000 \
  -e SUPABASE_URL=your_supabase_url \
  -e SUPABASE_KEY=your_supabase_key \
  -e CLOUDINARY_CLOUD_NAME=your_cloud_name \
  -e CLOUDINARY_API_KEY=your_api_key \
  -e CLOUDINARY_API_SECRET=your_api_secret \
  attendance-system
```

## 📡 API Endpoints

### Student Management
- `POST /students/register` - Register a new student with face images
- `GET /students/{student_id}` - Get student information
- `GET /students/attendance-history/{student_id}` - Get student attendance history

### Teacher Management
- `POST /teachers/register` - Register a new teacher
- `GET /teachers/{teacher_id}` - Get teacher information

### Attendance Sessions
- `POST /attendance/start-session` - Start a new attendance session
- `POST /attendance/end-session/{session_id}` - End an active session
- `GET /attendance/active-session/{section}` - Get active session for a section
- `POST /attendance/mark-present` - Mark a student present using face recognition
- `POST /attendance/mark-absent/{session_id}/{student_id}` - Manually mark absent

### Attendance Reports
- `GET /attendance/session/{session_id}` - Get attendance for a session
- `GET /attendance/daily-report` - Get daily attendance report
- `GET /attendance/subject-stats/{subject_id}` - Get subject attendance statistics
- `GET /attendance/low-attendance/{section}` - Get low attendance students

### Face Recognition
- `POST /recognize/single` - Recognize a single face
- `POST /recognize/multiple` - Recognize multiple faces in an image
- `POST /train/model` - Train face recognition model for a section

## 🔄 Workflow

### 1. Enrollment Phase
1. Student registers with multiple face images
2. Images are uploaded to Cloudinary
3. Image metadata stored in Supabase

### 2. Training Phase
1. Collect all enrolled student images for a section
2. Extract facial encodings using face_recognition library
3. Train ML model with encodings
4. Store model in Supabase storage

### 3. Attendance Phase
1. Teacher starts an attendance session
2. System automatically marks all section students as absent
3. Student stands before camera/takes photo
4. System recognizes student face
5. Attendance marked as present
6. Teacher ends session

### 4. Reporting Phase
1. Generate attendance statistics
2. Track low attendance students
3. Create daily/weekly/monthly reports

## 📊 Database Schema

### Key Tables
- **students**: Student enrollment data
- **teachers**: Teacher information
- **guests**: Guest user records
- **student_images**: Stored student photos
- **teacher_images**: Stored teacher photos
- **attendance_sessions**: Active/completed attendance sessions
- **attendance_records**: Individual student attendance marks
- **attendance_summary**: Aggregated attendance data
- **subjects**: Subject information
- **models_metadata**: Trained model information

## 🧪 Testing

Run the test suites:

```bash
# Test database connection
python test_connection.py

# Test attendance module
python test_attendance.py

# Test face recognition
python test.py
```

## ⚙️ Configuration

### Environment Variables
- `SUPABASE_URL`: Supabase project URL
- `SUPABASE_KEY`: Supabase API key
- `CLOUDINARY_CLOUD_NAME`: Cloudinary account name
- `CLOUDINARY_API_KEY`: Cloudinary API key
- `CLOUDINARY_API_SECRET`: Cloudinary API secret

### Key Functions

#### attendance.py
- `start_attendance_session()` - Initialize attendance session
- `end_attendance_session()` - Conclude session
- `mark_student_present()` - Mark student present
- `get_session_attendance()` - Retrieve session attendance
- `get_student_attendance_history()` - Get student history

#### train.py
- `train_face_model()` - Train recognition model
- `save_model()` - Persist model to storage

#### test.py
- `recognize_face()` - Recognize single face
- `recognize_multiple_faces()` - Recognize multiple faces

#### capture.py
- `upload_to_cloudinary()` - Upload images to CDN
- `download_from_cloudinary()` - Download stored images

## 🔐 Security Considerations

- Sensitive credentials stored in environment variables
- Secure image storage with Cloudinary CDN
- Database authentication via Supabase
- CORS middleware for cross-origin requests
- Input validation on all endpoints

## 📈 Performance Optimization

- Headless OpenCV for server environments (opencv-python-headless)
- Asynchronous FastAPI for high concurrency
- Cloudinary CDN for efficient image delivery
- Batch processing for multiple face recognition
- Model caching for reduced training time

## 🐛 Troubleshooting

### Common Issues

1. **Import Errors**: Ensure all dependencies are installed
   ```bash
   pip install -r requirements.txt
   ```

2. **Face Recognition Fails**: Verify image quality and lighting
   - Ensure faces are clearly visible
   - Good contrast and resolution recommended

3. **Database Connection Issues**: Check environment variables
   - Verify SUPABASE_URL and SUPABASE_KEY are correct
   - Test database connectivity with test_connection.py

4. **Cloudinary Upload Errors**: Validate credentials
   - Check CLOUDINARY_CLOUD_NAME, API_KEY, and API_SECRET
   - Ensure bucket permissions are correct

## 🚦 API Response Examples

### Successful Session Start
```json
{
  "session_id": "uuid-string",
  "teacher_id": "T001",
  "subject_id": 101,
  "section": "A",
  "semester": 4,
  "status": "active",
  "started_at": "2024-01-15T10:30:00",
  "students_marked_absent": 45
}
```

### Face Recognition Result
```json
{
  "recognized": true,
  "student_id": "S12345",
  "name": "John Doe",
  "confidence": 0.95,
  "enrollment_number": "CSE-2024-123"
}
```

## 📝 Future Enhancements

- Real-time WebSocket support for live attendance updates
- Mobile app integration
- Advanced analytics and ML-based attendance predictions
- Biometric data encryption
- Multi-modal recognition (facial + fingerprint)
- Scheduled automated reports
- Integration with student information system

## 📄 License

This project is part of a major academic initiative.

## 👥 Contributors

Developed as a comprehensive solution for educational attendance management.

## 📞 Support

For issues or questions, please check:
1. Environment configuration
2. Cloud service credentials
3. Test files for debugging
4. API documentation at `/docs` when server is running

---

**Last Updated**: February 2026
