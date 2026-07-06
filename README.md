# MedFlow — Hospital Management System

A front-end prototype of a Hospital Management System (HMS), built as a college project to demonstrate core hospital operations in a single interactive web app: patient records, appointments, staff management, ward/bed allocation, billing, and pharmacy inventory.

**[Live Demo](#)** · Built with HTML, CSS, and vanilla JavaScript — no frameworks, no build step.

---

## Overview

MedFlow simulates the day-to-day workflows of a mid-sized hospital from a single admin console. It's designed to show how the different departments of a hospital (admissions, medical staff, wards, billing, and pharmacy) connect to one another in one system.

## Features

- **Dashboard** — Real-time-style overview: bed occupancy, admitted patients, today's appointments, and low pharmacy stock alerts.
- **Patients** — Register new patients, auto-assign an available bed on admission, search and filter records.
- **Appointments** — Book appointments with a specific doctor/department, filter by status (Scheduled / Completed / Cancelled), mark visits complete.
- **Doctors & Staff** — Maintain a staff directory with specialty, department, and live duty status (Available / In Surgery / Off Duty).
- **Wards & Beds** — Visual bed maps across 4 wards (Cardiology, Orthopedics, Pediatrics, Maternity) with color-coded occupancy status.
- **Billing** — Generate invoices per patient, track pending vs. paid balances, mark invoices as paid.
- **Pharmacy Stock** — Track medicine/consumable inventory with automatic low-stock flags and restocking.

## Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 (custom properties / design tokens) |
| Logic | Vanilla JavaScript (no framework) |
| Fonts | Space Grotesk, IBM Plex Sans, IBM Plex Mono (Google Fonts) |

No external libraries or package installs are required — it runs directly in any modern browser.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/medflow-hms.git
   ```
2. Open `hospital_management_system.html` directly in your browser, **or** run it with a local server (recommended for the best experience):
   ```bash
   # using VS Code
   Right-click the file → "Open with Live Server"
   ```
3. That's it — no build step, no dependencies.

## Project Structure

```
medflow-hms/
├── hospital_management_system.html   # Main application (HTML + CSS + JS)
└── README.md
```

## Notes & Limitations

- This is a **front-end prototype** built for demonstration purposes. All data is held in memory and resets on page refresh — there is no backend or database connected.
- Designed to illustrate system design and UI/UX for a Hospital Management System, as a foundation that could later be connected to a real backend (e.g. Node.js/Express + a database) for persistent storage and authentication.

## Possible Future Enhancements

- Backend integration with persistent storage (MongoDB/MySQL)
- Role-based login (Admin / Doctor / Receptionist)
- Patient discharge workflow and medical history logs
- Exportable billing reports (PDF)

## Author

Built as a college/academic project demonstrating full-stack system design thinking through a front-end prototype.

## License

This project is open source and available for educational use.# Hospital-Management-System
Front-end prototype of a Hospital Management System — patient records, appointments, staff, ward/bed allocation, billing, and pharmacy inventory in one interactive HTML/CSS/JS app.
