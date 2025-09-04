# AI Study Assistant

An intelligent study platform powered by Google's Gemini AI that helps students learn through interactive conversations, personalized quizzes, and adaptive learning paths.

## 🌟 Features

- **AI-Powered Study Assistant**
  - Powered by Google's Gemini Pro model
  - Context-aware responses using your study materials
  - Natural conversation flow with personality
  - Instant answers to study-related questions
  - Explanation of complex topics

- **Smart Quiz Generation**
  - Three difficulty levels (Easy, Medium, Hard)
  - Auto-generated questions from your notes
  - Multiple choice format (5 options)
  - Correct answer validation
  - Progress tracking
  - Customized to your study material

- **Notes Management**
  - Upload and organize study materials
  - Class-based organization
  - Context preservation for AI interactions
  - Full-text search capability
  - Easy content management

- **Interactive Learning**
  - Real-time AI responses
  - Personalized learning paths
  - Progress tracking
  - Adaptive difficulty
  - Study material recommendations

## 🛠️ Tech Stack

### Frontend
- React.js with Vite
- TailwindCSS for styling
- React Router v6
- Lucide Icons
- Axios for API calls

### Backend
- Python/Flask
- Google Gemini AI
- PostgreSQL Database
- SQLAlchemy ORM
- Flask-CORS

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- Python (v3.8 or higher)
- PostgreSQL
- Google Cloud Project with Gemini API access

### Environment Setup

1. Clone the repository:
```bash
git clone https://github.com/ayushpratapsingh1/AI-Study-App.git
cd AI-Study-App
```

2. Install frontend dependencies:
```bash
cd frontend
npm install
```

3. Install backend dependencies:
```bash
cd backend
pip install -r requirements.txt
```

### Running the Application

1. Start the backend server:
```bash
cd backend
python app.py
```

2. Start the frontend development server:
```bash
cd frontend
npm run dev
```

The application will be available at `http://localhost:3000`

## 🔧 Configuration

### Frontend Configuration
- Update API endpoints in `.env` file
- Customize theme in `tailwind.config.js`

### Backend Configuration
- Configure AI model settings in `config.py`
- Set up database connections
- Update environment variables

## 📝 API Documentation

### Chat Endpoints

```
POST /chat_with_ai
{
  "query": "string",
  "class_id": "number"
}

Response:
{
  "response": "string",
  "confidence": "number",
  "context": "string",
  "model_name": "string",
  "processing_time": "number"
}
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
