# 🏥 Prescripto-main

This is a **Full-Stack Doctor Appointment Booking Web Application** that allows users to book appointments with doctors, while doctors and admins can manage schedules, availability, and users.  
Built using **React.js**, **Node.js**, **Express.js**, and **MongoDB**.

---

## 🚀 Project Overview

The Doctor Appointment System provides:
- A **user portal** for booking and managing appointments  
- An **admin panel** to manage doctors and users  
- A **secure backend API** for authentication, doctor management, and scheduling  

It’s designed to be simple, responsive, and efficient.

---

## 📁 Project Structure

| Folder | Description |
|---------|--------------|
| **frontend/** | React.js user interface built with Vite and Tailwind CSS |
| **backend/** | Node.js + Express API connected to MongoDB |
| **admin/** | Admin dashboard for managing doctors and users |
| **project-demo/** | Screenshots and demo files for visual reference |

---

## 🧑‍💻 Tech Stack

### **Frontend**
- React.js  
- Vite  
- Tailwind CSS  
- Axios  
- React Router DOM  

### **Backend**
- Node.js  
- Express.js  
- MongoDB (Mongoose)  
- JWT Authentication  
- Bcrypt for password hashing  

---

## ⚙️ Installation & Setup
2️⃣ Setup Backend
cd backend
npm install
npm start


Backend will typically run on: http://localhost:4000/
3️⃣ Setup Frontend
cd frontend
npm install
npm run dev

Frontend will run on: http://localhost:5173/
4️⃣ Setup Admin Panel
cd admin
npm install
npm run dev


🌐 Environment Variables
Create a .env file inside your backend folder with the following:
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=4000


📸 Screenshots

### 🏠 Home Page
<img width="772" height="412" alt="image" src="https://github.com/user-attachments/assets/8e9536b3-7bfb-4642-a74b-9344d42128b2" />


### 🧑‍⚕️ Doctor Listing
![Doctors](project-demo/doctors.png)

### 📅 Booking Page
![Booking](project-demo/booking.png)

### 🔐 Admin Dashboard
![Admin Dashboard](project-demo/admin-dashboard.png)
✨ Features
✅ User registration & login (JWT authentication)
✅ Book, view, and cancel appointments
✅ Admin dashboard for managing doctors & users
✅ Doctor approval workflow
✅ Secure APIs and clean UI
✅ Responsive design with Tailwind CSS

🧠 Future Enhancements


Email notifications for appointment reminders


Payment gateway integration


Doctor availability calendar view


Patient medical history tracking



📬 Contact
Author: Veesha Thaker
GitHub: @Veesha13
Project: Doctor Appointment System

⭐ If you like this project, give it a star on GitHub!

---

Would you like me to include **live demo / deployment instructions** (for example, if you plan to deploy on **Vercel** or **Render**)?  
I can modify the README to include that section too.


### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Veesha13/doctor-appointment-system.git
