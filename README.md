🐞 Bug Management System
A full-stack web application for efficient bug tracking and project management, designed to streamline the software development process by allowing role-based interaction between Admins, Project Managers, and Developers.

🔧 Features
🛡️ Role-Based Access Control

Admins can manage all users and projects.

Project Managers can create, assign, and manage bugs within their projects.

Developers can view and update bugs assigned to them.

📋 Bug Reporting & Tracking

Create detailed bug reports with severity and priority.

Track bug status (Open, In Progress, Resolved, Closed).

Assign bugs to specific developers.

🗂️ Project Management

Create and manage multiple projects.

Assign team members to projects with defined roles.

🧑‍💻 User Management

Secure login and session-based authentication.

Admin dashboard for adding/editing/deleting users.

🖥️ Dashboard UI

Clean and user-friendly interfaces built with EJS and Bootstrap.

Personalized views based on user roles.

🛠️ Tech Stack
Frontend: EJS, Bootstrap, HTML/CSS

Backend: Node.js, Express.js

Database: MongoDB

Authentication: Express-session, bcrypt

🚀 Getting Started
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/Aldrin-Rodrigues/Bug-Management-System.git
cd Bug-Management-System
2. Install Dependencies
bash
Copy
Edit
npm install
3. Setup MongoDB
Ensure MongoDB is installed and running.

Create a .env file and add your MongoDB connection string:

env
Copy
Edit
MONGODB_URI=mongodb://localhost:27017/bug-management
SESSION_SECRET=your_secret_key
4. Run the Application
bash
Copy
Edit
npm start
Visit http://localhost:3000 in your browser.

📸 Screenshots
(Add screenshots of dashboard, bug creation form, etc., here for better presentation)

👥 Contributors
Aldrin Rodrigues
Aritro Maiti
Ankit Arjunagi
Amaan Ahmed

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.