# **Institution Admission Query and Verification System**

### **Overview**
This is a professional-grade, multi-level dashboard application designed for government and institutional use. The system simplifies the admission query and verification process for students and administrators. It integrates React for the frontend, Python (Flask) for backend operations, and Machine Learning (ML) algorithms to predict college admissions. Additionally, it leverages Large Language Models (LLMs) for chatbot-based query resolution, making it an intelligent and efficient platform.

---

[![Watch the video](https://img.youtube.com/vi/lPSQCN5WODk/maxresdefault.jpg)](https://youtu.be/lPSQCN5WODk)

---

### **Key Features**
1. **Multi-Level User Roles:**
   - **Super Admin**: Accesses and oversees all operations and data.
   - **Government Verifier**: Verifies institution data on behalf of the government.
   - **Institution Admin Verifier**: Approves or rejects submissions within institutions.
   - **Institution Data Provider**: Uploads and manages institutional data (courses, facilities, placements, etc.).

2. **Dynamic Dashboards:**
   - Tailored views and controls for each user role.
   - Intuitive UI designed using React and Tailwind CSS.

3. **AI-Powered Features:**
   - **College Predictor**: Uses ML algorithms to predict suitable colleges for students based on their academic records.
   - **LLM Chatbot**: Resolves queries related to admissions, courses, and facilities.

4. **Data Flow and Verification:**
   - Data moves through a hierarchical approval system from institutions to the government level.
   - Rejected data is editable and can be resubmitted with corrections.

5. **Temporary and Persistent Data Storage:**
   - LocalStorage for demo purposes.
   - Backend integration via Flask for persistent storage and advanced analytics.

---

### **Tech Stack**
- **Frontend:**
  - React
  - Tailwind CSS
- **Backend:**
  - Python (Flask)
  - REST APIs
- **Database:**
  - SQLite (for demo) or PostgreSQL/MySQL (for production)
- **AI and ML:**
  - Scikit-learn and TensorFlow for predictive modeling.
  - OpenAI/LLMs for chatbot functionalities.

---

### **System Architecture**
1. **Frontend:**
   - Modular React components for roles and dashboards.
   - Real-time updates using LocalStorage and APIs.

2. **Backend:**
   - Flask REST APIs for CRUD operations and data flow management.
   - ML integration for predictions and analytics.

3. **LLM Chatbot:**
   - Pre-trained Large Language Models for conversational interfaces.
   - Handles complex queries with contextual understanding.

---

### **Getting Started**

#### **Prerequisites**
- Node.js and npm/pnpm installed for frontend.
- Python and pip installed for backend.
- Flask and related dependencies:
  ```bash
  pip install flask flask-cors scikit-learn tensorflow openai
  ```

#### **Installation**

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo.git
   cd your-repo
   ```

2. **Frontend:**
   ```bash
   cd frontend
   pnpm install
   pnpm dev
   ```

3. **Backend:**
   ```bash
   cd backend
   python app.py
   ```

4. **Run Both Frontend and Backend:**
   - Frontend: Access via `http://localhost:3000`.
   - Backend: Access Flask APIs via `http://localhost:5000`.

---

### **Usage**
- **Login:** Choose your role to log in and access respective dashboards.
- **Institution Data Provider:**
  - Upload data for courses, facilities, placements, and fees.
  - Edit and resubmit rejected data.
- **Institution Admin Verifier:**
  - Approve or reject submissions with comments.
- **Government Verifier:**
  - Verify approved institution data.
  - Reject and return invalid data to the institution admin.
- **Super Admin:**
  - Monitor all levels and perform audits.

---

### **Future Enhancements**
- Add OAuth for secure user authentication.
- Deploy backend using Docker and Kubernetes.
- Integrate payment gateway for online admissions.
- Expand ML capabilities for personalized recommendations.

---
