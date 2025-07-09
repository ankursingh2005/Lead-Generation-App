#Lead Automation Web App

A full-stack web application to automate the entire lead generation and follow-up process using **React**, **Tailwind CSS**, and **Express.js**.

---

#Features

-  Capture leads with a simple form (name + email)
-  Submit leads to a Node.js backend
-  Display stored leads instantly
-  Full-stack integration with REST API
-  Ready to extend with MongoDB, email, and CRM tools

---

##  Project Structure

lead-automation-app/
├── server/ # Express.js Backend
│ └── index.js
└── client/ # React Frontend
├── src/
│ ├── pages/
│ │ └── LeadAutomationPage.jsx
│ ├── App.jsx
│ └── index.js
└── public/

yaml
Copy
Edit

---

##  Getting Started

###  Backend Setup

```bash
cd server
npm install
node index.js
 Frontend Setup
bash
Copy
Edit
cd client
npm install
npm run dev


 API Endpoints
Method	Endpoint	Description
POST	/api/leads	Submit new lead
GET	/api/leads	Get all stored leads

 Deployment
Frontend: Vercel or Netlify
Backend: Render, Railway

MIT License © 2025 Ankur Singh
