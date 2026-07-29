# TrustLend

A peer-to-peer equipment rental marketplace where owners can list their equipment and renters can browse, book, and manage rentals with confidence.

Built as a frontend capstone project for **TechCrush Frontend Cohort 7**.

## Tech Stack

- **HTML5** — semantic markup
- **Tailwind CSS** — utility-first styling via CDN
- **JavaScript** — vanilla JS for interactivity
- **Font Awesome** — icons
- **Google Fonts** — Poppins (400, 500, 600, 700)

## Pages

| Page | File | Description |
|------|------|-------------|
| Authentication | `auth.html` | Combined signup/login with role toggle (Renter/Owner), password visibility, form validation |
| Booking Calendar | `booking.html` | Owner dashboard with weekly fleet view, status-coded booking bars, pagination, and export |

## Features

- **Role Toggle** — switch between Renter and Owner views; updates heading, description, and background image dynamically
- **Signup/Login Toggle** — single-page auth that shows/hides fields (name, phone, confirm password, terms) without a page reload
- **Password Visibility** — eye icon toggles between hidden and visible states
- **Password Match Validation** — checks confirm password on signup before submission
- **Booking Calendar** — colour-coded status bars (Active, Upcoming, Maintenance, Returned) spanning across a weekly grid
- **Fleet/Item View Toggle** — switches calendar perspective
- **Export PDF** — placeholder for PDF generation
- **Responsive Layout** — adapts to different screen sizes (desktop-first)

## Design System

| Token | Value | Usage |
|-------|-------|-------|
| Brand | `#132F6B` | Sidebar, buttons, headings |
| Accent | `#F59E0B` | Highlights, active states, links |
| Active Green | `#2E7D5B` | Active rental bars, FAB, export button |
| Upcoming Teal | `#1A7F7F` | Upcoming booking bars |
| Maintenance Yellow | `#C49A1A` | Maintenance status bars |
| Returned Gray | `#6B7280` | Returned/past status bars |
| Surface | `#F6F8FD` | Form backgrounds |
| Page Background | `#F0F2F5` | Body background |

**Font:** Poppins — loaded via Google Fonts CDN

## Project Structure

```
TrustLend/
├── auth.html              # Signup & Login page
├── booking.html           # Booking Calendar (Owner)
├── images/
│   ├── logo.png           # TrustLend logo icon
│   ├── avatar.png         # User avatar placeholder
│   ├── signup(renter & owner).png
│   ├── login(renter & owner).png
│   ├── excavator.jpg
│   ├── boomlift.jpg
│   ├── powergen.jpg
│   └── liftmaster.jpg
├── screenshots/           # Preview images for README
└── README.md
```

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/TrustLend.git
   ```

2. Open with Live Server (VS Code) or any local server:
   ```bash
   cd TrustLend
   # Right-click auth.html → Open with Live Server
   ```

3. No build step required — Tailwind is loaded via CDN.

## Team

**Capstone Group 1** — TechCrush Frontend Cohort 7

## License

This project was built for educational purposes as part of the TechCrush bootcamp curriculum.
