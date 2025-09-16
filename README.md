**📚 EduDashboard – Student Management System**

EduDashboard is a modular web-based student management system built with HTML, CSS, JavaScript, and Firebase Firestore.
It helps teachers, institutes, and students manage academic activities such as attendance, subjects, syllabus progress, tests, and doubt resolution.

**Important Notes**
Go to Images folder to check screenshot of Work.


**🚀 Features
🏫 Student Directory**

Add, edit, delete student records

Search and filter students by grade or name

Auto-generated student IDs

**📅 Attendance Tracker**

Mark daily attendance by batch

Track status: Present / Absent / Late / Excused

View and delete records with status indicators

**📚 Subject Manager**

Assign subjects to students

Manage chapters under each subject

Edit/delete subjects and chapters

AI-powered subject suggestions 

**📊 Syllabus Progress**

Track completion of chapters per subject

Progress bars for Not Started / In Progress / Completed

Auto-updates when chapters are marked completed

Integrated with Work Pool tasks

**📝 Work Pool**

Add and manage tasks for students

Prioritize tasks (High, Medium, Low)

Track task status (To Do / In Progress / Done)

Due date reminders

**❓ Doubt Box**

Students can raise doubts

Teachers/admins can assign tasks or mark as resolved

Track status: Open / Tasked / Resolved

**📘 Test Tracker**

Add and manage student tests

Record subject, date, total marks, scored marks

Filter by student

Score coloring for quick insights (Low/Medium/High)

**🛠️ Tech Stack**

Frontend: HTML, CSS, Vanilla JavaScript

Database: Firebase Firestore

Hosting (optional): Firebase Hosting / GitHub Pages

**⚙️ Setup Instructions**

**Clone the repository**

git clone https://github.com/your-username/edudashboard.git
cd edudashboard


**Configure Firebase**

**Create a Firebase project at Firebase Console**

**Enable Firestore Database**

Copy your config keys and replace them in each module file:

const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT_ID.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT_ID.appspot.com",
  messagingSenderId: "SENDER_ID",
  appId: "APP_ID"
};


**Open the Student Directory File D**

Navigate between modules using the navbar links

(Optional) Deploy to Firebase Hosting

npm install -g firebase-tools
firebase login
firebase init
firebase deploy

**📂 Project Structure**
/edudashboard
│── Student Directory.html    # Student management
│── Attendence.html         # Attendance tracker
│── Subject manager.html      # Subject assignment
│── Syllabus_progress.html    # Syllabus & progress tracker
│── workpool.html             # Work Pool task manager
│── Dought Task.html          # Doubt Box module
│── Test Treacker.html        # Test tracker module
│── README.md                 # Documentation

**📸 Screenshots (optional)**

Add screenshots of each module here for a better showcase.

**🤝 Contribution**

Pull requests are welcome!

Fork the repo

Create a new branch (feature/new-module)

Commit changes

Open a PR 🎉

**📜 License**

This project is licensed under the MIT License – feel free to use, modify, and share.
