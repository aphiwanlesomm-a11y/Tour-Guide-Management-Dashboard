# Tour-Guide-Management-Dashboard
ระบบ Dashboard สำหรับจัดการคิว ไกด์, รถ และเรือ" (Queue Management Dashboard)
Role: You are an Expert Frontend Developer specializing in React, Tailwind CSS, and Data Visualization.

Task: Create a modern, responsive "Tour Management Dashboard" in a single file (React Functional Component).

Core Requirements & Features:

CSV File Upload: - A prominent "Upload CSV" button.

Implement a basic CSV parser function to read the uploaded file, convert it to an array of objects, and update the dashboard state.

The dashboard should initially show mock data, but fully replace it when a CSV is uploaded.

Expected Data Structure (CSV Columns):

Name (String: Name of Guide/Driver/Boat)

Category (String: Guide, Car, Van, Boat)

Status (String: Available (ว่าง), Busy (ไม่ว่าง))

Zone (String: Near (ใกล้), Far (ไกล))

Rating (Number: 1 to 5)

Expertise (String: Tour name or skill)

BookingDate (String: YYYY-MM-DD or empty)

Phone (String)

Dashboard UI Layout:

Header: Dashboard Title and the CSV Upload Button.

Summary Cards (KPIs): Show total counts for Guides, Cars, Boats, and currently "Available" resources.

Filter Section: Dropdowns/Buttons to filter data by:

Category (All, Guide, Car, Boat)

Status (All, Available, Busy)

Zone (All, Near, Far)

Rating (All, 4+ Stars, etc.)

Data Table: A clean, modern table displaying the data.

Use color-coded badges for Status (Green for Available, Red/Gray for Busy).

Render stars (⭐) for the Rating column.

Show Expertise and Booking Date clearly.

Design System & Libraries:

Use lucide-react for icons (Upload, Star, MapPin, Car, Ship, User).

Use standard Tailwind CSS classes for styling. Make it look professional, clean, with rounded corners, subtle shadows, and adequate whitespace.

Ensure it is responsive.

Rules:

Provide ONLY ONE single runnable file (e.g., App.jsx or App.tsx).

Do not use external CSV parsing libraries like papaparse if it requires installation; write a simple native Javascript CSV string parser.

Include robust Mock Data (at least 10 rows covering all categories, statuses, and ratings) so the dashboard looks great before any file is uploaded.
