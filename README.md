# User Management System

An **User Management System** built with **Angular** (frontend), **Tailwind CSS** (styling), and **TypeScript**. This application allows users to manage employee records, including adding, editing, deleting, and displaying user information.

---

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Screenshots](#screenshots)
- [License](#license)

---

## Features

- View employee data in a table.
- Add new employee records via a form with validation.
- Edit existing employee records.
- Delete employee records.

---

## Tech Stack

### Frontend
- **Framework:** Angular
- **Styling:** Tailwind CSS
- **Language:** TypeScript

### Backend
- **Framework:** Node.js, Express.js
- **Database:** MongoDB

---

## Installation

### Clone the Repository
```bash
git clone https://github.com/your-username/employee-management-system.git
cd employee-management-system
Install Dependencies
bash
Copy code
npm install
Start the Development Server
bash
Copy code
ng serve
Navigate to http://localhost:4200/ in your browser to view the app.

For Production Build
To build the app for production:

bash
Copy code
ng build --prod
Tailwind CSS Setup
This project uses Tailwind CSS for styling. The configuration is included in the repository. If you need to customize Tailwind, edit the tailwind.config.js file.

Usage
Start the development server using the ng serve command.
Interact with the application:
Add new users through the "Add User" form.
View user details in a responsive table.
Edit or delete users using the action buttons.
Folder Structure
sql
Copy code
employee-management-system/
├── src/
│   ├── app/
│   │   ├── components/
│   │   │   ├── user-list/
│   │   │   ├── add-user/
│   │   └── services/
│   ├── assets/
│   ├── environments/
│   ├── styles.css
│   └── index.html
├── tailwind.config.js
├── package.json
└── README.md
![image](https://github.com/user-attachments/assets/856a9348-10c5-4b6e-8106-aab403656b85)

