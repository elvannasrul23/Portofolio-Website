# Elvan's Portfolio — HTML, CSS & Bootstrap

A clean, responsive portfolio website built with HTML5, custom CSS, and the Bootstrap 5 framework. Designed to showcase projects, skills, and personal journey with modern aesthetics.

---

## Screenshot

<!-- Anda dapat mengganti link src di bawah ini dengan screenshot website Anda yang sebenarnya -->
<img width="515" height="492" alt="image" src="https://github.com/user-attachments/assets/db129eec-973a-4149-a492-f6e311c1e911" />

---

## Overview

Visitors can explore Elvan's top projects (ranging from Data Analysis and Smart IoT Systems to Deep Learning), read about the portfolio's purpose, and experience smooth scroll animations. The layout is optimized for all devices using Bootstrap's responsive grid system.

This project is structured to fulfill the requirements of an **advanced teacher assessment** for website development.

---

## Features

- **Responsive Design** — Fully responsive layout built with Bootstrap 5.
- **Interactive UI** — Smooth scrolling animations using vanilla JavaScript (`IntersectionObserver`) and CSS hover effects on project cards.
- **External Routing** — Project cards are dynamically linked to live demos and presentations.
- **Clean Codebase** — Simple procedural structure with HTML/CSS/JS (ideal for easy maintenance and readability).
- **No Build Tools Required** — Runs instantly in any standard web browser without external package managers like npm.

---

## Project Structure

```
Portofolio/
├── index.html        # Main HTML structure and layout
├── style.css         # Custom CSS for colors and hover animations
├── script.js         # JavaScript for scroll visibility animations
├── assets/           # Project images (Data, IoT, Deep Learning)
└── README.md
```

---

## Requirements

- **Web Browser:** Any modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari).
- **Internet Connection:** Required only to load the Bootstrap 5 CDN files.

---

## Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/elvannasrul23/Portofolio-Website.git
   ```

2. **Navigate to the project folder:**
   ```bash
   cd Portofolio-Website
   ```

3. **Run the application:**
   - Simply double-click the `index.html` file to open it in your default web browser. No local server is strictly required.

---

## How It Works

| Section            | Description                                      | Technologies Used |
|--------------------|--------------------------------------------------|-------------------|
| **Navbar**         | Fixed-top navigation for branding                | Bootstrap 5       |
| **Hero Section**   | Bold red header introducing the portfolio        | HTML & CSS        |
| **Projects Grid**  | 3-column layout showcasing key projects          | Bootstrap Cards   |
| **Animations**     | Cards fade and slide in when scrolling into view | JS (IntersectionObserver) |

**Project Highlights:**
- **Data Analysis** -> Links to Streamlit App
- **Smart IoT Systems** -> Links to YouTube presentation
- **Deep Learning** -> Links to Vercel YOLO App

---

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

*Built as an assessment and showcase project for website development.*
