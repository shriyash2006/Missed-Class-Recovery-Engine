# Missed-Class-Recovery-Engine
Got it — you want **ONE clean README.md**, no confusion, everything in one place, including **full project + mindmap + workflow + architecture**.

👉 Copy everything below **as-is into your README.md** — this is structured to impress in review.

---

```markdown
# 🚀 AI-Powered Missed Class Recovery System

---

## 🧠 Project Mindmap (Complete System Overview)

```

Missed Class Recovery System
│
├── 👨‍🏫 Admin / Teacher Portal
│   ├── Manage Subjects (DBMS, OS, etc.)
│   ├── Upload Study Materials (PDF/PPT)
│   ├── Upload Lecture Plan (Date → Topic)
│   ├── Upload Student Data (Excel)
│   └── Upload / Mark Attendance
│
├── 📝 Attendance Module
│   ├── Manual Attendance (Checkbox)
│   ├── Excel/PDF Upload
│   └── Absentee Detection
│
├── 🧠 AI / ML Engine
│   ├── PDF Topic Extraction (Headings)
│   ├── Lecture Plan Mapping
│   ├── Topic Identification
│   ├── Summary Generation (LLM)
│   └── Priority Classification (Optional ML)
│
├── 📧 Notification System
│   ├── Email to Absentees
│   ├── Topic + Summary
│   └── PDF Notes Attachment
│
├── 📊 Analytics Module
│   ├── Absentee Reports
│   ├── Download Data
│   └── Teacher Insights
│
└── 🔐 Developer Module
├── Admin Login
├── Workflow Monitoring
└── API Integration

```

---

## 📌 Overview

The **Missed Class Recovery System** is an AI-powered web application that helps students recover missed lectures automatically.

When a student is marked absent:
- The system detects the missed lecture
- Identifies the topic taught
- Generates a summary using AI
- Sends an email with notes and resources

---

## 🎯 Objective

To automate the academic recovery process for absent students using:
- Attendance tracking
- Document intelligence
- AI-based summarization
- Workflow automation

---

## ⚙️ System Architecture

```

Teacher/Admin Portal
↓
Upload Data (PDF, Excel, Lecture Plan)
↓
Attendance Processing
↓
Absentee Detection
↓
Topic Mapping Engine
↓
AI Summary Generator
↓
Email Automation System
↓
Student Notification

```

---

## 🔄 End-to-End Workflow

```

1. Teacher uploads lecture plan & study materials
2. Teacher uploads or marks attendance
3. System detects absent students
4. System identifies topic taught (based on date)
5. AI generates summary of topic
6. Email is sent to absentees with:

   * Topic name
   * Summary
   * Notes/PDF

```

---

## 🔗 n8n Automation Workflow

```

Webhook Trigger (Attendance Submitted)
↓
Read Attendance Data (Excel/Google Sheets)
↓
Filter Absentees (IF Node)
↓
Fetch Topic (Lecture Plan Mapping)
↓
OpenAI Node (Generate Summary)
↓
Send Email (Gmail/SMTP)

```

---

## 🧩 Core Modules

### 1. Admin / Teacher Portal
- Upload study materials (PDF/PPT)
- Upload lecture plan
- Upload student data
- Manage subjects

---

### 2. Attendance Management
- Manual marking (Present/Absent)
- File upload (Excel/PDF)
- Automatic absentee detection

---

### 3. AI / ML Module
- Extract topics from PDFs
- Map lecture plan to content
- Generate summaries using LLM
- (Optional) ML-based priority classification

---

### 4. Notification System
- Sends automated emails to absent students
- Includes summary and study materials

---

### 5. Analytics Dashboard
- View absentee list
- Download reports
- Track attendance trends

---

## 🗂️ Project Structure

```

missed-class-recovery/
│
├── frontend/          # UI (React / HTML / Streamlit)
├── backend/           # API (Node.js / Django)
├── ml-module/         # NLP & ML scripts (Python)
├── workflows/         # n8n automation workflows
├── data/              # Sample datasets (Excel)
├── docs/              # PPT & diagrams
└── README.md

```

---

## 🧪 Tech Stack

### Frontend
- React.js / Streamlit

### Backend
- Node.js / Express OR Django

### AI / ML
- Python
- OpenAI API (for summaries)
- pdfplumber / PyMuPDF

### Automation
- n8n (workflow orchestration)

### Database
- MongoDB / PostgreSQL

### Email
- SMTP / Gmail API / SendGrid

---

## 📂 Input Formats

### Student Data (Excel)
| Name | Reg No | Email | Phone |

### Attendance Sheet
| Reg No | Status |
|--------|--------|
| 101    | Present |
| 102    | Absent  |

### Lecture Plan
| Date       | Topic              |
|------------|-------------------|
| 2026-03-23 | Memory Management |

---

## ✉️ Sample Email Output

```

Subject: Missed Class Recovery - OS

Dear Student,

You were absent for today's class.

Topic Covered:
Memory Management

Summary:
[AI Generated Summary]

Please review the attached material.

Regards,
Recovery System

```

---

## 🚀 Future Enhancements

- WhatsApp Notifications
- AI Chatbot for Doubts
- Personalized Learning Paths
- Face Recognition Attendance
- Performance Prediction System

---

## 🧠 Key Learning Outcomes

- Full-stack development
- AI integration in real systems
- Workflow automation using n8n
- NLP for document processing
- System design & architecture

---

## 👨‍💻 Author

**Shriyash Sahu**  
B.Tech | AI & ML Enthusiast

---

## 📜 License

For academic and educational use only.

---
```

---

