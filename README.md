# MSEC Hostel Management Dashboard

A modern, scalable, production-ready full-stack **Hostel Management System** developed for **Meenakshi Sundararajan Engineering College (MSEC)**. Built with a decoupled architecture featuring a **FastAPI (Python 3)** backend and a **React 19 + TypeScript (Node.js)** frontend.

---

## 🎨 Design System & Color Palette

The user interface follows a clean, modern, and eye-catching aesthetic strictly implementing the MSEC institutional design specification:

- **Primary (Purple)**: `#4E2478` — Navigation, headers, primary buttons
- **Primary Dark**: `#38195A` — Hover / active states
- **Primary Light**: `#EDE4F5` — Tinted backgrounds, selected rows
- **Accent (Crimson)**: `#F30137` — CTAs, active indicators, alert badges
- **Accent Dark**: `#C4012C` — Hover on accent buttons
- **Accent Light**: `#FDE2E7` — Alert / notice backgrounds
- **Ink (Text)**: `#1A1523` — Body text with subtle purple undertone
- **Ink Muted**: `#5C5468` — Secondary / supporting text
- **Border**: `#E3DEE9` — Dividers, card borders
- **Surface**: `#FFFFFF` — Cards & content surfaces
- **Background**: `#FAF8FC` — Page background with warm purple tint
- **Success**: `#1C8A5C` — Attendance OK, cleared payments
- **Warning**: `#D98B16` — Due soon, late entries
- **Danger**: `#D6264C` — Overdue dues, absences, urgent tickets
- **Info**: `#2563A6` — Informational tags

### Typography
- **Headings, titles, numbers**: `Poppins` (Weights: 600, 700, 800)
- **Body, tables, forms, nav**: `Inter` (Weights: 400, 500, 600)

---

## 🏛️ 9 Functional Modules

1. **Dashboard Overview**
   - KPI metrics: Total residents, occupied vs. vacant rooms, pending fees, active complaints, today's roll-call rate.
   - Official Campus Notices & Announcements board.
   - Wing-wise capacity utilization (Kaveri Boys, Bhavani Girls, Vaigai Scholars).
   - Real-time campus movement activity feed.

2. **Student Management**
   - Complete student resident directory with search and department filters.
   - Detailed profile modals: Personal details, Blood Group, Room info.
   - Parent contact information and 24/7 emergency telephone records.
   - New Hostel Admission enrollment workflow.

3. **Room & Allocation Management**
   - Room matrix across floors, capacity counters, and AC/Non-AC classification.
   - Student bed assignment and check-in records.
   - Mutual and administrative **Room Transfer** request workflow.
   - Student check-out and bed vacating operations.

4. **Attendance & Outing Management**
   - Daily roll-call attendance sheet with date selection.
   - 1-click status recording: **Present**, **Late** (post 8:30 PM), **On Leave**, **Absent**.
   - Attendance summary counters and percentage rates.
   - Digital outpass and weekend leave application, warden approval, and gate return logging.

5. **Visitor Management**
   - Campus visitor entry logging with ID proof verification (Aadhar, Voter ID, License).
   - Relationship mapping to resident student and visit purpose.
   - Live badge counter for visitors currently inside campus.
   - One-click security gate departure check-out.

6. **Fee Management**
   - Accommodation, mess, and caution deposit fee schedules.
   - Student payment tracking (Paid, Pending, Overdue).
   - Payment collection recording with receipt reference numbers.
   - Printable official fee receipts.

7. **Complaints & Maintenance**
   - Multi-category maintenance tickets: Electricity, Plumbing, Furniture, Cleanliness, Wi-Fi, and Facilities.
   - Priority tagging (Low, Medium, High, Urgent) and status workflow (Pending, In Progress, Resolved).
   - Maintenance notes and technician assignment.

8. **Mess Management**
   - Interactive 7-day weekly meal timetable (Breakfast, Lunch, Evening Snacks, Dinner).
   - Meal serving schedules and special feast badges.
   - Student dining reviews, star ratings, and food quality complaints.
   - Warden menu configuration modal.

9. **Inventory & Reports**
   - Track hostel furniture, electrical fittings, RO dispensers, and housekeeping supplies.
   - Asset condition tracking (Good, Needs Repair, Damaged, Brand New).
   - Consolidated executive reports: Occupancy Report, Attendance Compliance, Financial Collection Rate, and Maintenance SLA.

---

## ⚡ Quick Start

### Backend API (FastAPI)
```powershell
cd backend
.\.venv\Scripts\activate
python run.py
```
- API Endpoint: `http://127.0.0.1:8000`
- Interactive Swagger Docs: `http://127.0.0.1:8000/docs`

### Frontend Dashboard (React + Vite)
```powershell
cd frontend
npm run dev
```
- Dashboard UI: `http://localhost:5173`

### Demo Login Accounts
- **Admin**: `admin@msec.edu.in` / `Admin@123`
- **Warden**: `warden.kaveri@msec.edu.in` / `Warden@123`
- **Student**: `rahul.cse@msec.edu.in` / `Student@123`
