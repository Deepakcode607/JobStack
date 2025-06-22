💼 JobStack – MERN-based Job Portal Web Application
JobStack is a full-featured MERN Stack job portal designed to streamline the hiring and job application process. With dedicated user roles for Applicants and Recruiters, this web app provides a seamless and secure platform for job seekers and recruiters to interact.
<img src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif"
🚀 Features
👤 Authentication & Authorization
Role-based user sign-up (Applicant / Recruiter)

Secure JWT-based login with persistent sessions

🧑‍💼 Recruiter Dashboard
Create, update, and delete job postings

Manage applications (shortlist, accept, reject)

View applicant resumes

Edit recruiter profile

👨‍💻 Applicant Dashboard
Browse job listings with fuzzy search and filters

Apply for jobs with a Statement of Purpose (SOP)

View application statuses

Upload profile picture and resume

Edit applicant profile
📁 Project Structure
JobStack/
│
├── backend/
│   ├── public/
│   │   ├── profile/      # Profile picture uploads
│   │   └── resume/       # Resume uploads
│   └── ...               # Express + MongoDB server logic
│
├── frontend/
│   └── ...               # React app with Material UI
│
└── README.md
⚙️ Getting Started
📌 Prerequisites
Node.js

MongoDB

📥 Installation Steps
Start MongoDB server

bash
Copy
Edit
sudo service mongod start
Backend Setup

bash
Copy
Edit
cd backend
npm install
npm start
Runs Express server on http://localhost:4444

Frontend Setup

bash
Copy
Edit
cd ../frontend
npm install
npm start
Runs React app on http://localhost:3000

🧩 Tech Stack
🖥️ Frontend
React.js

Material UI

Axios

react-phone-input-2

material-ui-chip-input

🔙 Backend
Node.js & Express

MongoDB with Mongoose

JWT (jsonwebtoken)

Passport.js (local & JWT strategy)

Multer (file uploads)

Bcrypt (password hashing)

CORS, Session, Flash, Crypto, UUID

🔐 Security Highlights
Passwords hashed with bcrypt

Secure JWT-based API access

Session handling via Passport.js & Express sessions

📦 Future Enhancements
Email notifications on application status

Admin panel for superusers

Real-time messaging between applicant and recruiter

Enhanced job recommendation system

🙌 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## 👨‍💻 Author

Developed with ❤️ by [Deepak Kumar](https://github.com/Deepakcode607)










