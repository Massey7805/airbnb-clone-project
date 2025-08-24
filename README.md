# 🏠 AirBnB Clone – Software Engineering Project

## 📖 Overview
This project is part of the **ALX Frontend Software Engineering** program.  
The aim is to replicate core parts of the AirBnB experience with clean, responsive UI and interactive behavior, using modern, maintainable frontend practices.

---

## 🎯 Project Goals
- Build **responsive layouts** (mobile-first) using Flexbox & CSS Grid.
- Create reusable **UI components** (Navbar, Property Card, Footer, Filters).
- Add interactivity with **JavaScript (ES6+)** (modals, filters, dynamic rendering).
- Prepare for **API integration** (fetch & render data).
- Follow best practices for **version control**, documentation, and basic testing.

---

## 🛠️ Tech Stack
- **HTML5** — semantic structure & accessibility
- **CSS3** — Flexbox, Grid, transitions, responsive design
- **JavaScript (ES6+)** — DOM, modules, async
- **Git & GitHub** — version control & collaboration
- *(Optional, later)* **React / Next.js**, **Jest** for tests

---

## 🎨 UI/UX Design Planning

### 🌟 Design Goals
- **Clean, modern, responsive** layout across devices
- **Easy navigation** from browse → details → checkout
- **Consistency** in spacing, colors, and typography
- **Clear visual hierarchy** (prices, CTAs, ratings stand out)
- **Performance & accessibility** (fast, readable, keyboard-friendly)

### 🔑 Key Features to Implement
- Search + filters (location, price, availability)
- Property cards (images, ratings, price/night)
- Listing details (gallery, amenities, reviews)
- Simple checkout (minimal steps, clear confirmation)
- Smooth micro-interactions (hover, focus, transitions)

### 📄 Primary Pages

| Page | Description | Key Features |
|------|-------------|--------------|
| **Property Listing View** | Browse available stays in grid/list. | Images, title, price/night, rating, location; filter/search panel |
| **Listing Detailed View** | Full details for a selected stay. | Image gallery, description, amenities, reviews, map, **Book Now** CTA |
| **Simple Checkout View** | Confirm and finalize a booking. | Guest details form, date summary, price breakdown, confirm message |

### 🎨 Design Properties from Figma

#### Color Styles
- **Primary**: `#FF5A5F` (main buttons & highlights)
- **Secondary**: `#00A699` (accents)
- **Neutrals**:
  - Background Light: `#F7F7F7`
  - Text Dark: `#484848`
  - White: `#FFFFFF`
  - Border/Subtle: `#E0E0E0`

#### Typography
- **Font Family**: Circular (fallbacks: `Inter, Arial, sans-serif`)
- **Weights**: 400 (body), 500 (subhead), 700 (titles/buttons)
- **Sizes** (baseline example):
  - H1: 32px
  - H2: 24px
  - Body: 16px
  - Small: 14px
> Note: Use web-safe or open-source fallbacks if Circular isn’t available.

### 💡 Why Identify Design Properties?
Locking down colors & type early:
- Keeps **branding consistent** across pages/components
- Speeds up dev (no guessing tokens)
- Improves **accessibility** & readability
- Creates a shared **design system** for everyone (designers/devs/testers)

---

## 🧩 UI Component Patterns

### 1) Navbar
- Brand logo + primary nav
- Search bar (quick lookup)
- Auth: Login/Signup or Profile dropdown
- Sticky on scroll (optional)

### 2) Property Card
- Cover image, title, price/night, rating, location
- Hover elevation/outline
- Click → opens **Listing Detailed View**

### 3) Footer
- About / Contact / Terms & Policies links
- Social icons
- Consistent site-wide branding

**Future components (planned):**
- Search Filter Panel (price, date, amenities)
- Booking Form (dates, guests, confirm)
- User Profile Dropdown

---

## 👥 Project Roles and Responsibilities

### Project Manager
- Owns timeline, scope, and cross-team communication
- Manages risks/resources

### Product Owner
- Defines vision & goals, maintains backlog
- Prioritizes features based on user value

### Scrum Master
- Facilitates Agile ceremonies
- Removes blockers, safeguards process

### Frontend Developers
- Implement UI from Figma → code (HTML/CSS/JS)
- Ensure responsiveness & accessibility
- Wire pages (Listings, Details, Checkout)

### Backend Developers
- (If/when added) Build APIs & data models
- Security, performance, business logic

### UI/UX Designers
- Figma mockups & prototypes
- Design tokens (colors, type, spacing)
- Usability & accessibility reviews

### QA/Testers
- Test cases (unit/integration/E2E)
- Bug reporting & verification

### DevOps Engineers
- CI/CD, hosting, monitoring
- Perf/security best practices

---

## 📂 Suggested Project Structure
airbnb-clone-project/
│── index.html
│── style.css
│── script.js
│── assets/
│ ├── images/
│ ├── icons/
│── README.md

---

## 👨‍💻 Author
**Massey Beckham Akpor**  
- GitHub: [@Massey7805](https://github.com/Massey7805)
- LinkedIn: Beckham Massey (optional)

## 🌍 Live Demo (Coming Soon)
GitHub Pages or Netlify link will appear here.
