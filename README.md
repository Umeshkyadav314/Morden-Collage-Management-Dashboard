
## Getting Started

# Project Title : Morden Collage Management Dashboard
A Modern College Management Dashboard is a comprehensive system that allows administrators, teachers,
students, and parents to efficiently manage academic activities, communication,
and administrative processes. Here are the key details and features for each user role: 

# Key Features:
- User Management: Role-based access for admins, teachers, students, and parents.
- Attendance Tracking: Real-time student attendance records accessible to teachers and parents.
- Gradebook & Progress Reports: Teachers can input grades, and students/parents can view academic progress.
- Course & Timetable Management: Scheduling for classes, exams, and extracurricular activities.
- Notifications & Messaging: Centralized communication between admin, teachers, students, and parents (emails, SMS, push notifications).
- Fee Management: Automated fee tracking, payment gateway integration, and invoicing for students.
- Document Management: Storage and access to important documents like transcripts, certificates, and assignments.
- Parent Portal: Access to student academic records, attendance, and performance summaries.
- Library Management: Book lending, inventory, and history tracking for students and staff.
- Reporting & Analytics: Detailed reports on student performance, teacher efficiency, and administrative tasks.
- Mobile Accessibility: Access to the dashboard via a mobile-friendly interface.


## Role-Specific Features:

# Admin:
 - User Role Management: Assign roles (teacher, student, parent) and manage permissions.
 - Fee & Financial Tracking: Manage tuition fees, dues, and financial reports.
 - Academic Calendar & Event Management: Oversee and update the calendar, including exams, holidays, and events.
 - Reports & Analytics: Generate insights on institution performance, student trends, and resource management.
 - 
# Teacher:
- Attendance Management: Mark and track student attendance in real time.
- Gradebook: Enter and update grades, create assessments, and track student performance.
- Assignment & Resource Sharing: Upload assignments, class materials, and provide resources for students.
- Communication Tools: Send notifications to students and parents regarding performance or updates.
- Timetable Management: Manage class schedules and organize academic activities.
  
# Student:
 - Personal Dashboard: View grades, attendance, assignments, and exam schedules.
 - Assignment Submission: Submit homework and projects online, receive feedback from teachers.
 - Course Enrollment: Enroll in courses, access course materials, and check progress.
 - Examination & Results: View exam schedules and results in real time.
   
# Parent:
 - Progress Tracking: View student academic performance, attendance, and behavior reports.
 - Communication: Interact with teachers and school staff for updates on their child.
 - Fee Payment & Tracking: View fee invoices, make payments online, and track payment history.
 - Notifications & Alerts: Receive notifications about academic progress, attendance issues, and important school events.


## Tech Stack

- **Next.js** (React Framework)
- **TypeScript** (Static Typing)
- **Prisma** (Database ORM)
- **Tailwind CSS** (UI Styling)
- **Docker** (Containerization)

## Prerequisites

- Node.js 18+
- Docker (optional)
- PostgreSQL/MySQL (for Prisma)

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/Umeshkyadav314/Morden-Collage-Management-Dashboard.git
    cd your-repository
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Set up Prisma:

    ```bash
    npx prisma migrate dev
    ```

4. Run the development server:

    ```bash
    npm run dev
    ```

    The app will be running at [http://localhost:3000](http://localhost:3000).

## Docker Setup

1. Build and start containers:

    ```bash
    docker-compose up --build
    ```

## Folder Structure

- **/prisma**: Prisma schema & migrations
- **/src**: Application code (components, pages, etc.)
- **Dockerfile**: Container build instructions
- **tailwind.config.ts**: Tailwind CSS setup

## Environment Variables

Create a `.env` file:

```bash
DATABASE_URL=your-database-url
NEXT_PUBLIC_API_URL=http://localhost:3000/api
