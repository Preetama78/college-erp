# College ERP Login Portal

A role-based ERP login system built with the MERN stack, replacing paper registers and scattered spreadsheets with a single secure platform for Students, Teachers, and Admins.

## Problem
Small colleges often manage attendance, fees, and results across paper records and disconnected Excel files, with no secure login, no remote access, and no budget for commercial ERP tools like SAP or Oracle.

## Features
- JWT-based authentication with bcrypt password hashing (cost factor 12)
- Role-Based Access Control (RBAC) for Student, Teacher, and Admin
- Admin: manage students, teachers, branches, and fees
- Teacher: mark attendance, upload exam marks, post announcements
- Student: view attendance %, results, and fee status
- Responsive UI, deployed fully online

## Tech Stack
- **Frontend:** React.js
- **Backend:** Node.js + Express.js
- **Database:** MongoDB (MongoDB Atlas)
- **Auth:** JWT + bcrypt
- **Deployment:** Vercel (frontend), Render (backend), MongoDB Atlas (DB)

## Architecture
Client (React) → REST API (Node/Express) → JWT Middleware + RBAC → MongoDB (Mongoose)

## My Contribution
Built the React frontend including the login page, role-based dashboard routing, and the Admin panel for managing students, teachers, and branches.

## Live Demo
https://college-erp-kohl.vercel.app/login

## Team
Anisha Panda, Amisha Gouda, Preetama Maharana, Kiran Poonia, Mamata Bhumia
Supervisor: Asst. Prof. Shuchishree Panigrahy — Kalam Institute of Technology, Berhampur
