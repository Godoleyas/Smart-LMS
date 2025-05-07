# 🎓 SmartLMS - The AI-Powered Learning Management System

SmartLMS is a comprehensive, intelligent Learning Management System designed to enhance both teaching and learning experiences. In addition to offering all features of a traditional LMS, SmartLMS integrates with **Google's Gemini AI** to automatically summarize teacher prompts and generate intelligent descriptions for course videos — making content more accessible, searchable, and engaging.

## 🚀 Features

### ✅ Core LMS Features
- **User Roles**: Admin, Teacher, Student
- **Course Management**: Create, update, and manage courses
- **Lesson Modules**: Add video lectures, PDFs, quizzes, and assignments
- **Quizzes & Assignments**: Auto-grading, deadlines, manual review
- **Discussion Forums**: Integrated Q&A and peer interaction
- **Progress Tracking**: Dashboard for students and teachers
- **Certificates**: Auto-generated certificates on course completion
- **Calendar & Reminders**: Schedule sessions and send notifications

### 🤖 AI-Powered Features (Gemini Integration)
- **Prompt Summarization**: Teachers can input lecture notes or prompt text; Gemini generates concise summaries.
- **Auto-Generated Video Descriptions**: When a course video is uploaded, Gemini provides an AI-generated description based on metadata or manual prompts.
- **Smart Search**: Gemini-enhanced keyword tagging for faster content discovery.

## 🛠️ Tech Stack

- **Backend**: Django (Python) + Django REST Framework
- **Frontend**: Tailwind CSS
- **Database**: MySQL
- **AI Integration**: Gemini API (via Google AI SDK)



## 📷 Screenshots

> _Coming soon: UI demos and walkthroughs_

## 🧠 How the AI Works

The Gemini AI integration is seamless:
1. Teachers provide a textual prompt while uploading content or videos.
2. The text is sent to the Gemini API.
3. The summarized version is returned and auto-populated as the description or metadata.
4. This boosts video clarity, engagement, and indexing.

## 🔒 Security

- Role-based permissions
- CSRF and CORS Protection
- Activity logs for Admin auditing (planned)

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/yourusername/smartlms.git
cd smartlms

# Backend Setup
cd backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver


