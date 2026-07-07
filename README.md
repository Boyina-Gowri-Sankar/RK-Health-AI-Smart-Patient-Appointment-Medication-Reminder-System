# 🏥 RK Health – AI Smart Patient Appointment & Medication Reminder System

> An AI-powered healthcare management platform that streamlines patient appointment scheduling, medication reminders, AI-generated health summaries, and centralized health record management using modern web technologies and cloud services.

---

## 📌 Overview

RK Health is an intelligent healthcare management system designed to simplify patient care by combining **appointment scheduling**, **medication management**, **AI-powered health summaries**, and **automated reminder services** into one unified platform.

The application enables healthcare providers and patients to efficiently manage appointments, maintain medical records, receive automated medication reminders via SMS, generate patient-friendly AI summaries from clinical notes, and monitor healthcare activities through an interactive dashboard.

By integrating **Groq AI**, **Google Apps Script**, **Google Sheets**, **Twilio SMS**, and **Google Calendar**, RK Health demonstrates how cloud technologies and Generative AI can improve accessibility, automation, and healthcare communication.

---

# 🎯 Project Objectives

- Digitize patient appointment management
- Automate medication reminders
- Generate AI-powered health summaries
- Maintain centralized patient health records
- Improve patient engagement and compliance
- Reduce manual administrative work
- Demonstrate practical integration of Generative AI into healthcare workflows

---

# ✨ Key Features

## 📅 Appointment Management
- Create new appointments
- View upcoming appointments
- Update appointment information
- Delete appointments
- Doctor & patient scheduling
- Visit notes management

---

## 💊 Medication Reminder System

- Store medication schedules
- Track dosage information
- Automated SMS reminders
- Reminder history
- Medication compliance monitoring

---

## 🤖 AI Health Summary

Powered by **Groq Llama 3.3 70B**.

The AI module converts clinical notes into easy-to-understand summaries including:

- Visit Overview
- Health Recommendations
- Medication Guidance
- Follow-up Instructions
- Patient-friendly explanations

---

## 📊 Dashboard

Interactive dashboard displaying:

- Total appointments
- Medication records
- Compliance percentage
- Patient logs
- AI summaries
- Generated reports

---

## 📄 Health Reports

Automatically generates complete patient reports including:

- Appointment history
- Medication records
- Reminder status
- AI-generated health summary
- Compliance indicator

---

## 📱 Automated Notifications

Integrated with Twilio SMS to send:

- Appointment reminders
- Medication reminders
- Patient notifications

---

## 📅 Google Calendar Integration

Automatically creates calendar events for appointments, helping patients never miss scheduled consultations.

---

## ☁ Cloud-Based Storage

Patient records are securely maintained using:

- Google Sheets
- Google Apps Script Backend

The cloud architecture removes the need for a traditional database server while allowing easy deployment and scalability.

---

# 🏗 System Architecture

```
                    User
                      │
                      ▼
             Web Dashboard (HTML/CSS/JS)
                      │
                      ▼
           Google Apps Script Backend
                      │
      ┌───────────────┼────────────────┐
      ▼               ▼                ▼
Google Sheets     Groq AI        Twilio SMS
(Database)      Health Summary    Reminders
      │               │                │
      └───────────────┼────────────────┘
                      ▼
              Google Calendar
                      │
                      ▼
            Patient Healthcare Portal
```

---

# ⚙ Technology Stack

| Category | Technologies |
|----------|--------------|
| Frontend | HTML5, CSS3, JavaScript |
| Backend | Google Apps Script |
| Database | Google Sheets |
| AI | Groq API (Llama 3.3 70B Versatile) |
| SMS | Twilio API |
| Calendar | Google Calendar API |
| Version Control | Git & GitHub |
| Deployment | GitHub Pages + Google Apps Script |

---

# 📂 Project Workflow

```
Patient Details
       │
       ▼
Appointment Booking
       │
       ▼
Google Apps Script Backend
       │
       ▼
Google Sheets Database
       │
       ├────────► AI Summary Generation
       │              │
       │              ▼
       │      Groq LLM Response
       │
       ├────────► SMS Reminder
       │              │
       │              ▼
       │          Twilio API
       │
       ├────────► Calendar Event
       │              │
       │              ▼
       │       Google Calendar
       │
       ▼
Dashboard Update
       │
       ▼
Health Report Generation
```

---

# 📦 Core Modules

### Patient Management
- Patient records
- Contact details
- Medical history

### Appointment Management
- Schedule appointments
- Manage doctors
- Visit tracking

### Medication Management
- Medicine schedules
- Dosage tracking
- Reminder management

### AI Engine
- Clinical note analysis
- Health summary generation
- Recommendation generation

### Notification Service
- SMS reminders
- Appointment alerts
- Medication alerts

### Dashboard
- Statistics
- Reports
- Activity monitoring

---

# 🔄 Application Workflow

1. Patient schedules an appointment.
2. Appointment data is stored in Google Sheets.
3. Medication information is recorded.
4. AI analyzes visit notes.
5. Groq generates a patient-friendly summary.
6. SMS reminders are sent through Twilio.
7. Google Calendar event is created.
8. Dashboard updates automatically.
9. Health reports are generated.

---

# 🔐 Input Validation

The system validates:

- Patient information
- Doctor information
- Phone numbers
- Appointment dates
- Medication details
- Required fields

This ensures reliable and consistent healthcare records.

---

# 📈 Dashboard Analytics

The dashboard provides:

- Total appointments
- Medication count
- Reminder compliance
- Health reports
- AI summaries
- Patient activity logs

---

# 🚀 Deployment

Frontend:
- GitHub Pages

Backend:
- Google Apps Script Web App

Cloud Storage:
- Google Sheets

AI:
- Groq API

Notification Service:
- Twilio

---

# 🌟 Benefits

- AI-assisted healthcare management
- Faster appointment scheduling
- Reduced manual paperwork
- Automated reminders
- Cloud-based architecture
- Improved patient compliance
- Easy deployment
- Cost-effective implementation
- Responsive user interface
- Scalable design

---

# 🔮 Future Enhancements

- User Authentication
- Multi-user support
- Doctor Portal
- Patient Portal
- Electronic Health Records (EHR)
- Wearable device integration
- Predictive health analytics
- Voice assistant support
- Email notifications
- Mobile application
- QR-based patient identification
- Medical image analysis
- Prescription management
- Cloud database migration
- Role-based access control

---

# 📚 Learning Outcomes

This project demonstrates practical implementation of:

- Full Stack Web Development
- Cloud Computing
- REST APIs
- Google Apps Script
- Google Sheets as Database
- AI Integration
- Prompt Engineering
- SMS Automation
- Healthcare Workflow Automation
- Dashboard Development
- API Integration
- Software Deployment

---

# 🎓 Conclusion

RK Health demonstrates how Artificial Intelligence and cloud technologies can modernize healthcare management through automation, intelligent decision-making, and seamless communication. By combining appointment scheduling, medication reminders, AI-generated health summaries, cloud-based record management, SMS notifications, and calendar integration, the system delivers a scalable, user-friendly, and practical healthcare solution.

The modular architecture makes the platform easy to maintain, extend, and deploy while providing a strong foundation for future enhancements such as predictive healthcare analytics, wearable device integration, secure authentication, and advanced patient engagement features.

---

## ⭐ If you found this project helpful, consider giving it a Star on GitHub!
