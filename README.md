# TrustLend

A peer-to-peer equipment rental marketplace where owners can list their equipment and renters can browse, book, and manage rentals with confidence.

Built as a frontend capstone project for **TechCrush Frontend Cohort 7**.

## Tech Stack

- **HTML5** — semantic markup
- **Tailwind CSS** — utility-first styling via CDN
- **JavaScript** — vanilla JS for interactivity
- **Font Awesome** — icons
- **Google Fonts** — Poppins (400, 500, 600, 700, 800)

## Pages

| Page | File | Description |
|------|------|-------------|
| Landing Page | `landing_page.html` | Public homepage with hero section, equipment listings, how it works, trust & safety, testimonials, CTA, and footer |
| Authentication | `auth.html` | Combined signup/login with role toggle (Renter/Owner), password visibility, form validation |
| Booking Calendar | `booking.html` | Owner dashboard with weekly fleet view, status-coded booking bars, pagination, and export |
| Dispute Management | `admin_dispute_management.html` | Admin panel with dispute list, evidence review, timeline, and resolution workflow |

## Features

- **Landing Page** — full marketing page with search bar, 2×2 hero image grid, trust badges, stats bar, equipment cards with pricing, 4-step "How it works" flow, testimonials with ratings, and CTA banner
- **Role Toggle** — switch between Renter and Owner views; updates heading, description, and background image dynamically
- **Signup/Login Toggle** — single-page auth that shows/hides fields (name, phone, confirm password, terms) without a page reload
- **Password Visibility** — eye icon toggles between hidden and visible states
- **Password Match Validation** — checks confirm password on signup before submission
- **Booking Calendar** — colour-coded status bars (Active, Upcoming, Maintenance, Returned) spanning across a weekly grid
- **Fleet/Item View Toggle** — switches calendar perspective
- **Dispute Management** — tabbed dispute list with status filters, evidence photo grid with "+2 more", dispute timeline, resolution radio options, and draft saving
- **Export PDF / Export** — placeholder buttons for PDF generation

## Design System

| Token | Value | Usage |
|-------|-------|-------|
| Brand | `#132F6B` | Sidebar, buttons, headings |
| Sidebar | `#1C263B` | Admin sidebar background |
| Accent | `#F59E0B` | Highlights, active states, CTA buttons |
| Active Green | `#2E7D5B` | Active rental bars, FAB, export button |
| Upcoming Teal | `#1A7F7F` | Upcoming booking bars |
| Maintenance Yellow | `#C49A1A` | Maintenance status bars |
| Returned Gray | `#6B7280` | Returned/past status bars |
| Surface | `#F6F8FD` | Section backgrounds, form areas |
| Page Background | `#F0F2F5` | Dashboard body background |

**Font:** Poppins — loaded via Google Fonts CDN

## Project Structure

```
TrustLend/
├── landing_page.html                # Public landing/home page
├── auth.html                        # Signup & Login page
├── booking.html                     # Booking Calendar (Owner)
├── admin_dispute_management.html    # Admin Dispute Management
├── images/
│   ├── logo.png                     # Logo (white/orange for dark bg)
│   ├── logo-blue.png                # Logo (blue for white navbar)
│   ├── signup(renter & owner).png   # Auth page background (signup)
│   ├── login(renter & owner).png    # Auth page background (login)
│   ├── hero-camera.png              # Hero section images
│   ├── hero-camera(2).png
│   ├── hero-gear.png
│   ├── hero-gear(2).png
│   ├── sony-fx3.png                 # Equipment card images
│   ├── litheli-drill.png
│   ├── ad-fury.png
│   ├── Yunteng.png
│   ├── p6.png
│   ├── excavator.jpg                # Booking calendar assets
│   ├── boomlift.jpg
│   ├── powergen.jpg
│   ├── liftmaster.jpg
│   └── evidence/                    # Dispute evidence photos
│       ├── owner-1.jpg
│       ├── owner-2.jpg
│       ├── owner-3.jpg
│       ├── renter-1.jpg
│       ├── renter-2.jpg
│       └── renter-3.jpg
└── README.md
```

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Ohenewa-a/rent.it.git
   ```

2. Open with Live Server (VS Code) or any local server:
   ```bash
   cd rent.it
   # Right-click landing_page.html → Open with Live Server
   ```

3. No build step required — Tailwind is loaded via CDN.

## Team

**Capstone Group 1** — TechCrush Frontend Cohort 7

## License

This project was built for educational purposes as part of the TechCrush bootcamp curriculum.
