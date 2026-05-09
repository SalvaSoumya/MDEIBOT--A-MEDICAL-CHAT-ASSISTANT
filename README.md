# MEDIBOT – AI Healthcare Assistant

MEDIBOT is a cloud-based healthcare assistant designed to improve healthcare accessibility through AI-powered symptom analysis, automated chat support, health tracking, and wellness management.

The platform provides users with instant health guidance, symptom checking, health record management, appointment reminders, and wellness resources through an interactive and user-friendly interface.

---

## Overview

MEDIBOT was developed to address the challenge of limited and delayed healthcare accessibility, especially for users in remote or underserved areas.

The system acts as a digital healthcare companion that helps users:

- Analyze symptoms
- Access AI-powered health support
- Store health records
- Track wellness activities
- Receive reminders and notifications
- Access health education resources

The platform combines cloud computing, AI APIs, and full-stack web development to provide a scalable and accessible healthcare support system.

---

## Objectives

- Improve healthcare accessibility through a cloud-based platform
- Provide instant symptom analysis and guidance
- Deliver automated healthcare support using AI chat assistance
- Enable users to manage personal health records
- Track wellness metrics and activities
- Provide medication and appointment reminders
- Promote health awareness through educational resources

---

## Features

### User Authentication
- Secure login and registration system
- User account management
- Protected access to health information

---

## Symptom Checker

- AI-powered symptom analysis
- Suggests possible health conditions
- Uses Infermedica API for medical insights
- Collects symptom, age, and gender information

---

## AI Chatbot Assistant

- Real-time healthcare support
- Interactive conversational interface
- Health-related question answering
- Chat history management

Integrated APIs:
- Healthwise API
- NHS UK API

---

## Health Records & Notes

- Personal health information storage
- Medical notes management
- Health dashboard for wellness tracking
- Track vitals such as:
  - Heart Rate
  - Blood Pressure
  - Sleep

---

## Notifications & Reminders

- Medication reminders
- Appointment notifications
- Calendar integration
- Health alerts and updates

---

## Health Tips & Education

- Wellness tips
- Diet and nutrition guidance
- Yoga and meditation resources
- Trusted health educational content

---

## Chat History Storage

- Stores previous conversations
- Enables users to review earlier health discussions
- MongoDB-based storage system

---

## Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript
- React
- Bootstrap

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### APIs & Services
- Infermedica API
- Healthwise API
- NHS UK API
- Calendar API

### Deployment
- Vercel

---

## System Architecture

The platform follows a three-tier cloud-based architecture:

1. Frontend Cloud – User Interface
2. Backend Cloud – Business Logic & APIs
3. Database & External Services Layer

### Backend Modules

- auth.js
- records.js
- symptoms.js
- chat.js
- health.js
- notifications.js

---

## Project Structure

```bash
MEDIBOT/
│
├── frontend/
│   ├── public/
│   ├── src/
│   ├── components/
│   └── pages/
│
├── backend/
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   └── server.js
│
├── database/
│   └── mongodb/
│
├── api/
│   ├── symptom_checker/
│   ├── chatbot/
│   └── notifications/
│
├── health_records/
├── reminders/
├── README.md
└── requirements.txt
```

---

## Modules

### Authentication Module
Handles secure user registration and login functionality.

### Symptom Checker Module
Processes symptoms and provides AI-generated health suggestions.

### Chatbot Assistant Module
Offers automated healthcare guidance through conversational AI.

### Health Dashboard Module
Tracks user wellness metrics and personal health records.

### Notifications Module
Sends reminders for appointments, medications, and health activities.

### Health Tips Module
Provides wellness and preventive healthcare education.

---

## Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/your-username/medibot.git

cd medibot
```

---

### 2. Install Dependencies

```bash
npm install
```

---

### 3. Configure Environment Variables

Create a `.env` file and add:

```env
MONGODB_URI=your_mongodb_uri
INFERMEDICA_API_KEY=your_api_key
HEALTHWISE_API_KEY=your_api_key
```

---

### 4. Run Backend

```bash
node server.js
```

---

### 5. Run Frontend

```bash
npm start
```

---

## Deployment

The project was deployed using Vercel.

Deployment platform:
- Vercel Cloud Deployment

---

## Application Functionalities

### Dashboard
- Homepage with healthcare assistance overview

### Registration & Login
- User onboarding and authentication

### Chat Dashboard
- AI-powered healthcare conversations

### Symptom Checker
- Symptom analysis with condition suggestions

### Health & Wellness Portal
- Wellness guidance and educational resources

### Appointment Booking
- Schedule healthcare appointments

### Notifications Page
- Health updates and reminders

---

## Security & Privacy

The platform ensures secure handling of user health information through:

- Authentication mechanisms
- Protected user sessions
- Secure database storage
- Controlled API access

Sensitive information and API keys should be managed using environment variables.

---

## Future Enhancements

- Advanced AI diagnosis assistance
- Mobile application support
- Voice-enabled healthcare assistant
- Real-time doctor consultation
- Wearable device integration
- Cloud database scalability improvements

---

## License

This project is developed for academic and educational purposes.

---

## Author

Salva Soumya

GitHub: https://github.com/SalvaSoumya
