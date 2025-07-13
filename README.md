# minihackathon

# 🛠️ Tech Event Registration API

## 📌 Problem Statement
Build an API system to register participants in tech events and allow admins to view registrations.

---

## 👨‍💻 Tech Stack
- Backend: Flask (Python)
- Frontend: HTML, CSS, JS
- Data Storage: `data.json` file
- API Testing: Postman

---

## 🔧 API Endpoints

### ✅ POST /register
Registers a new participant.
- **Required fields**: name, email, college, event
- Prevents duplicate registration by email

### ✅ GET /participants
Returns a list of all participants  
Optional: `GET /participants?event=HackDay`

---

## 🧪 Testing
- Tested using Postman
- Checked success and error scenarios
- Verified duplicate protection and filtering

---

## 👥 Team
- **Frontend Developer**: Haniya (Built HTML UI)
- **Backend Developer**: Harsh Limkar (Flask API, Data storage)
- **PPT Creator**: Selvamagal (Slides & Summary)
- **Tester + Documenter**: Sasvanthu (API Testing + Documentation)

---

## 📂 Project Folder Structure