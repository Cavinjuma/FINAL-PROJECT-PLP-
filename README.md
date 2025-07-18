# **Face Recognition Attendance System**

A robust system designed to authenticate individuals and record attendance using **facial recognition technology** powered by deep learning. This project simplifies attendance tracking for classrooms, workplaces, or events.


---

## **📋 Features**

- Role-based access for **administrators**, **lecturers**.
- Manage courses, units, venues, and attendance records through an intuitive interface.
- Capture and store multiple images for accurate identification.

## Project Structure

````
## Project Structure

```plaintext
Face-Recognition-Attendance-System/
├── database/
│   ├── attendance-db.sql         # SQL file to set up the database
│   └── database_connection.php   # Database connection script
├── models/
│   └── face-api-models.js        # JavaScript models for Face API
├── resources/
│   ├── assets/
│   │   ├── css/                  # CSS files
│   │   └── javascript/           # JavaScript files
│   ├── images/                   # Images directory
│   ├── labels/                   # Stored images of registered students
│   ├── lib/
│   │   └── global-functions.php  # Global PHP functions
│   ├── pages/
│   │   ├── admin/                # Admin-specific pages
│   │   ├── lecturer/             # Lecturer-specific pages
│   │   └── login.php             # Login page
├── index.php                     # Main entry point for all pages
├── .htaccess                     # Redirect rules
└── README.md                     # Project documentation


## 🧑‍💻 User Guide

### 1. Login as Administrator

- **Email**: `admin@gmail.com`
- **Password**: `@admin_`

Once logged in, you can:

- Add students.
- Manage courses, units, and venues.

⚠️ **Important**:

- Ensure to add at least **two students** and capture **five clear images** for each.
- Poor image quality will affect recognition accuracy. You can retake any image by clicking on it.

### 2. Login as Lecturer

- Create a lecturer account via the admin panel or use a pre-existing one.
- 
**Select lecture user type, to be able to login as lecture**

  *if you have issues using this email and password, create your lecture on admin panel*

- **Email**: `mark@gmail.com`
- **Password**: `@mark_`

As a lecturer:

- Select a course, unit, and venue on the home page.
- Launch the **Face Recognition** feature to begin attendance.

### Additional Features for the Lecturer Panel

- You can also export the attendance to an **Excel** sheet.
- Other simple features are available for managing the lecture panel.

📜 License
This project is licensed under the Apache License.

📧 Support
For any issues or inquiries, feel free to reach out via email: [Juma Cavin](mailto:jumacavin28@gmail.com).
