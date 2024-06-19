# Crestwood Academy Website and Admin Dashboard

## Project Description

This project consists of a comprehensive website for Crestwood Academy, including an admin dashboard for managing various aspects of the school's operations. The website provides information about the academy, including academic programs, news, events, and contact details. The admin dashboard allows administrators to manage student information, faculty details, events, and more.

![Crestwood Academy](/images/readme/crestwood1.png "Crestwood Academy")

## Features

### Website
- **Home Page**: Introduction to Crestwood Academy with links to various sections.
- **About Us**: Detailed information about the academy's mission, history, and values.
- **Academics**: Information on academic programs and courses offered.
- **Admissions**: Guidelines and procedures for prospective students.
- **News**: Latest news and announcements.
- **Events**: Upcoming events and activities.
- **Contact Us**: Contact information, including address, email, and social media links.
- **Postgraduate Application**: Online form for applying to postgraduate programs.
- **Thank You Page**: Confirmation page displayed after successful registration.

![Dashboard](/images/readme/admin-portal.png "Admin Dashboard")

### Admin Dashboard


![Dashboard](/images/readme/student-admin.png " Student Admin Dashboard")

#### Student Dashboard
- **Login Page**: Secure login for students.
- **Course Enrollment**: View and enroll in available courses.
- **Grades and Transcripts**: Access grades and download transcripts.
- **Timetable**: View and manage class schedules.
- **Assignments**: Submit and view assignments.

![Dashboard](/images/readme/student-login.png "Student Dashboard")

![Dashboard](/images/readme/teacher-portal.png "Teacher Dashboard")

#### Teacher Dashboard
- **Login Page**: Secure login for teachers.
- **Class Management**: Manage classes, including adding/removing students.
- **Grade Submission**: Enter and update student grades.
- **Schedule Management**: View and update class schedules.
- **Assignment Management**: Create and manage assignments for classes.

   ![Dashboard](/images/readme/teacher-login-page.png "teacher Dashboard")

![Dashboard](/images/readme/parent-portal.png "Parent Dashboard")

#### Parent Dashboard
- **Login Page**: Secure login for parents.
- **Student Progress**: View child's academic progress and grades.
- **Timetable Access**: View child's class schedules.
- **Communication**: Contact teachers and school administration.
- **Event Participation**: Sign up for and view school events and parent-teacher meetings.

  ![Dashboard](/images/readme/perant-login.png "Parent Dashboard")



## Setup Instructions

### Prerequisites

- [Node.js](https://nodejs.org/en/download/)
- [npm](https://www.npmjs.com/get-npm)
- [Bootstrap](https://getbootstrap.com/)
- [Font Awesome](https://fontawesome.com/)
- [SASS](https://sass-lang.com/)

### Installation

1. **Install Dependencies**

   ```bash
    npm install

2. **Run the project**

  ```bash
  npm start


3. **Compile SASS** 
   If you are using SASS, you can compile your SASS files to CSS using the following command:

   ```bash
   npm run sass

Ensure you have a script in your package.json for compiling SASS:
 
 \`\`\`"scripts": {
  "sass": "sass --watch sass:css"
}


