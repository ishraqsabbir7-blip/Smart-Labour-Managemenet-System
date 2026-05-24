# Smart Labour Management System

A complete Flask-based Labour Management System for workforce management with 8 integrated features including attendance tracking, task assignment, salary calculation, substitute request chatbox, and performance analytics.

## Features

**Worker Profile** - Stores personal info (name, contact, address, joining date, department) and work info (assigned tasks, deadlines, shift). Workers can view their profile, edit personal contact info, and access a personal notification box.

**Attendance System** - Two-stage tracking where check-in marks 0.5 attendance and stores check-in time, while check-out updates to 1 full attendance and records check-out time. System automatically calculates total working hours.

**Admin Controls** - Admin can view all workers' profiles, attendance percentage, and cumulative hours. Can approve/reject substitute requests and leave applications delivered to personal notification box. Can finalize salary slips and manually update worker status (Active/Inactive).

**Manager Task Assignment** - Managers assign daily tasks with deadlines to workers. Tasks are visible on worker's profile. Workers can mark tasks as Completed, In Progress, or Delayed. Managers receive notifications in their personal notification box.

**Salary Calculation** - Base salary linked to minimum monthly working hours. Extra hours including substitute hours are added as bonus. Admin reviews before finalizing payment.

**Substitute Requests** - Workers can request substitutes if absent through centralized chatbox. Substitute hours credited to substitute worker's total hours. Substitute must accept request. Admin approves final substitution.

**Leave Management** - Workers submit leave requests with dates and reasons. Admin reviews and approves/rejects requests. System automatically updates worker status to On Leave when approved. Attendance system blocks check-in/out during leave periods. Admin manually changes status back to Active after leave ends.

**Performance Summary** - Monthly analysis of attendance, total hours, and efficiency. Penalty or deduction for missing hours. Workers can request performance slip including manager feedback.

## Tech Stack

Backend: Flask (Python)
Database: MySQL
Frontend: HTML5, CSS3, JavaScript
Local Server: XAMPP
