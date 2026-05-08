🏥 MEDICARE - Hospital Management System
A full-stack Hospital Management System (HMS) built using the MERN Stack — MongoDB, Express.js, React.js, and Node.js.

This project helps manage hospital workflows including patients, doctors, appointments, departments, and administrative operations through a modern and responsive interface.

🌟 Features
👨‍⚕️ Admin Panel
Add / Remove Doctors
Manage Services
Appointment Management
Dashboard Analytics
Search Doctors
Earnings Tracking
Role-Based Authentication
🩺 Doctor Panel
Doctor Login
View Appointments
Update Appointment Status
Profile Management
Availability Toggle
Earnings Dashboard
👤 Patient Features
Book Appointments
Browse Doctors & Services
Authentication & Authorization
Responsive UI
Emergency Contact Section
🛠️ Tech Stack
Frontend
React.js
Tailwind CSS
Axios
React Router DOM
Backend
Node.js
Express.js
MongoDB
Mongoose
JWT Authentication
Cloudinary
Clerk Authentication
Stripe Payment Gateway
📂 Project Structure
MEDICARE/
│
├── frontend/        # Patient Frontend
├── admin/           # Admin Dashboard
├── backend/         # Node + Express Backend
│
├── package.json
└── README.md
⚙️ Installation
1️⃣ Clone Repository
git clone https://github.com/your-username/MEDICARE.git
cd MEDICARE
2️⃣ Install Dependencies
Backend
cd backend
npm install
Frontend
cd frontend
npm install
Admin Panel
cd admin
npm install
🔑 Environment Variables
Create a .env file inside the backend folder and add the following variables.

☁️ Cloudinary Setup
Create an account on Cloudinary
Go to Dashboard → API Keys
Copy:
Cloud Name
API Key
API Secret
Create two folders:
Doctors
Services
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
🔐 Clerk Authentication Setup
Create account on Clerk
Create a project
Copy Publishable Key & Secret Key
CLERK_PUBLISHABLE_KEY=your_publishable_key
CLERK_SECRET_KEY=your_secret_key
💳 Stripe Payment Gateway Setup
Create account on Stripe
Open Developers → API Keys
Copy Secret Key
STRIPE_SECRET_KEY=your_stripe_secret_key
🔑 JWT Secret
JWT_SECRET=your_super_secure_jwt_secret
🌐 URLs
FRONTEND_URL=http://localhost:5173
ADMIN_URL=http://localhost:5174
▶️ Run Project
Backend
cd backend
npm run server
Frontend
cd frontend
npm run dev
Admin Panel
cd admin
npm run dev
🔐 Authentication & Security
JWT Based Authentication
Clerk Authentication
Role-Based Access Control
Protected Routes
Secure API Handling
📚 Learning Outcomes
Full MERN Stack Development
REST API Integration
Authentication & Authorization
Cloudinary File Uploads
Payment Gateway Integration
Database Modeling
Responsive UI Design
Real-world Project Architecture
🎯 Suitable For
Major Project
Final Year Project
Portfolio Project
Internship Project
Placement Preparation
🌐 Live Demo
Frontend: https://your-frontend-url.com
Admin Panel: https://your-admin-url.com
👨‍💻 Author
Sachin Tyagi
GitHub: https://github.com/sachin-tyagi80
⭐ Support
If you like this project, give it a ⭐ on GitHub.

⚠️ Important Note
Never upload your .env file or secret keys to GitHub.

Add this inside .gitignore

.env
📜 License
This project is for educational purposes only.
