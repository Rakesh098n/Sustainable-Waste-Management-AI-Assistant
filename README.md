# 🌍 EcoSense – Sustainable Waste Management Assistant Using Generative AI

EcoSense is an AI-powered web application that helps users identify household waste, receive intelligent disposal guidance, locate nearby recycling centers, and track their sustainability efforts. Powered by **Generative AI (Llama 3.3 via Groq)**, EcoSense promotes responsible waste management through smart recommendations, interactive maps, and insightful analytics.

---

## 🌟 Key Features

### 🧠 AI-Powered Waste Scanner
- Classifies household waste using **Llama 3.3 (Groq AI)**
- Detects Plastic, Paper, Glass, Metal, Organic, E-waste, Hazardous Waste, and more
- Provides disposal instructions and recycling recommendations
- Generates sustainability tips for environmentally friendly disposal

### 🗺️ Interactive Recycling Map
- Built with **Leaflet.js**
- Displays nearby recycling centers, hazardous waste facilities, and compost locations
- Color-coded markers for different disposal categories
- Provides location details, accepted materials, and contact information

### 📊 Sustainability Analytics Dashboard
- Interactive visualizations powered by **Chart.js**
- Doughnut Chart for recyclable vs. non-recyclable waste
- Bar Chart for waste category distribution
- Line Chart showing weekly scanning activity
- KPI cards displaying recycling statistics and sustainability metrics

### 📜 Scan History Management
- Automatically stores previous scans
- View complete waste classification history
- Delete individual records or clear the entire history
- Track personal recycling progress over time

### 🛡️ Offline Fallback Mode
- Automatically switches to a local JSON database when cloud services are unavailable
- Continues working without requiring Groq or Firebase credentials
- Ensures uninterrupted user experience

---

# 📂 Repository Structure

```text
EcoSense/
│
├── .github/
│   └── workflows/
│       └── deploy.yml
│
├── 1. Brainstorming & Ideation/
├── 2. Requirement Analysis/
├── 3. Project Design Phase/
├── 4. Project Planning Phase/
├── 5. Project Development Phase/
│   ├── backend/
│   └── frontend/
├── 6. Performance Testing/
├── 7. Documentation & Demo/
│   ├── Project Documentation/
│   ├── Video Demonstration/
│   └── Project Demo Link/
├── 8. Project Demonstration/
│   ├── Live Website Screenshots/
│   └── Scalability & Future Plan/
│
├── backend/
│   ├── services/
│   ├── tests/
│   ├── app.py
│   ├── requirements.txt
│   └── .env.template
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   ├── vite.config.js
│   └── index.html
│
├── .gitignore
└── README.md
```

---

# 📁 Project Folder Overview

| Folder | Description |
|---------|-------------|
| **1. Brainstorming & Ideation** | Idea generation, problem identification, empathy map, and prioritization. |
| **2. Requirement Analysis** | Functional requirements, DFDs, customer journey maps, and technology stack. |
| **3. Project Design Phase** | System architecture and problem-solution fit documentation. |
| **4. Project Planning Phase** | Project planning, milestones, and development timeline. |
| **5. Project Development Phase** | Complete frontend and backend source code. |
| **6. Performance Testing** | API testing, unit testing, and performance evaluation reports. |
| **7. Documentation & Demo** | Project documentation, installation guide, and video demonstration. |
| **8. Project Demonstration** | Live screenshots, scalability roadmap, and future enhancement plans. |

---

# 💻 Technology Stack

### Frontend
- React.js
- Vite
- HTML5
- CSS3
- JavaScript

### Backend
- Flask
- Python

### AI & Cloud
- Groq AI
- Llama 3.3
- Firebase (Optional)
- Local JSON Database (Offline Mode)

### Visualization & Mapping
- Leaflet.js
- Chart.js

---

# 🌐 Live Application

| Service | Link |
|---------|------|
| 🌍 Live Web Application | https://sustainable-waste-management-amrn.onrender.com/ |
| ⚛️ Frontend (GitHub Pages) | https://lokeshkodamanchili.github.io/Sustainable-Waste-Management/ |
| ❤️ API Health Check | https://sustainable-waste-management-amrn.onrender.com/api/health |

---

# 🚀 Quick Local Setup

## 1️⃣ Clone the Repository

```bash
git clone <repository-url>
cd EcoSense
```

---

## 2️⃣ Backend Setup

```bash
cd backend

python -m venv venv
```

### Activate Virtual Environment

**Windows**

```powershell
.\venv\Scripts\Activate.ps1
```

**Linux / macOS**

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Start Flask Server

```bash
python app.py
```

Backend runs at:

```
http://127.0.0.1:5000
```

---

## 3️⃣ Frontend Setup

Open another terminal.

```bash
cd frontend

npm install

npm run dev
```

Open:

```
http://localhost:5173
```

---

## 4️⃣ Environment Variables

Copy

```
.env.template
```

to

```
.env
```

and configure:

```env
GROQ_API_KEY=your_key
FIREBASE_KEY=your_key
```

If no keys are provided, EcoSense automatically switches to **Offline Mode** using the local database.

---

## 5️⃣ Load Sample Data

After launching the application:

1. Open **Settings**
2. Click **Seed Sample Dataset**
3. Demo waste records will be generated automatically
4. Analytics charts and scan history will be populated instantly

---

# 🎯 Core Modules

- 🧠 AI Waste Classification
- ♻️ Recycling Recommendations
- 🗺️ Recycling Center Locator
- 📊 Sustainability Analytics
- 📜 Scan History
- ⚙️ Settings & Data Management

---

# 📈 Future Enhancements

- 📷 Image-based waste detection
- 🌍 Real-time recycling center integration
- 📱 Mobile application
- 🔐 User authentication
- ☁️ Cloud database synchronization
- 🌎 Multi-language support
- 🔔 Smart recycling reminders
- 📊 Advanced sustainability reports

---

# 👨‍💻 Developed For

**EcoSense – Sustainable Waste Management Assistant Using Generative AI**

An AI-powered solution that promotes responsible waste disposal, sustainable recycling practices, and environmental awareness through intelligent classification, interactive mapping, and real-time analytics.
