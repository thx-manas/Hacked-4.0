SMARTCARE – HEALTHCARE APPOINTMENT AND CLINIC MANAGEMENT SYSTEM

SMARTCARE is a **modern healthcare appointment and clinic management web application** designed to simplify the interaction between **patients, doctors, and clinic administrators**.

The system allows patients to **book appointments online**, doctors to **manage schedules and patient records**, and clinics to **organize queues and monitor patient flow efficiently**.

This project was built by combining common features from several open-source healthcare systems and improving them with **modern web technologies, better UI/UX, and additional automation features**.

---

FEATURES-

Doctor Features

* Manage availability schedule
* View and manage booked appointments
* Access patient medical history
* Write consultation notes
* Generate digital prescriptions

Patient Features

* Register and login securely
* Search doctors by specialization
* Book and manage appointments
* View appointment history
* Upload medical records
* Receive appointment reminders

Reception / Queue Management

* Generate token numbers for walk-in patients
* Live queue tracking
* Update patient status:

  * Waiting
  * Arrived
  * Skipped
  * Completed

Admin Panel

* Manage doctors and patients
* Manage clinic departments
* Monitor appointments
* View analytics dashboard
* Generate reports

---

Additional Features

* Email and SMS appointment notifications
* Digital prescription generation
* Analytics dashboard with charts
* Patient record management
* Secure authentication system
* Responsive UI for mobile and desktop

---

TECH STACK-
Frontend

* React / Next.js
* Tailwind CSS
* Chart.js

Backend

* Node.js
* Express.js

Database

* PostgreSQL / MySQL

Authentication

* JWT Authentication

Deployment

* Vercel (Frontend)
* Render / Railway (Backend)

---
Project Structure

```
smartcare-system
│
├── frontend
│   ├── components
│   ├── pages
│   ├── styles
│   └── services
│
├── backend
│   ├── routes
│   ├── controllers
│   ├── models
│   ├── middleware
│   └── server.js
│
└── database
    └── schema.sql
```

---

INSTALLATION AND SETUP-

>Clone the Repository

```
git clone https://github.com/yourusername/smartcare-system.git
```

>Navigate to Project

```
cd smartcare-system
```

>Install Backend Dependencies

```
cd backend
npm install
```

>Install Frontend Dependencies

```
cd ../frontend
npm install
```

>Setup Environment Variables

Create `.env` file in backend:

```
PORT=5000
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=yourpassword
DB_NAME=smartcare
JWT_SECRET=yoursecretkey
```

>Run Backend

```
npm run start
```

>Run Frontend

```
npm run dev
```

---

Database Tables

* Users
* Doctors
* Patients
* Appointments
* Queue
* Prescriptions

---

Security Features

* Password hashing using bcrypt
* JWT authentication
* Role-based access control
* Protected API routes

---

Future Improvements

* AI-powered chatbot for patient assistance
* Telemedicine video consultations
* Mobile application
* Integration with wearable health devices
* Multi-clinic management system

---

Author

Developed by **TEAM DECEPTICONS**

THANK YOU
