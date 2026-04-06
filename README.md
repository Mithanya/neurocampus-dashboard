# NeuroCampus Pro

## Overview

NeuroCampus Pro is a professional academic dashboard that provides students and educators with real-time performance analytics, task management, schedule tracking, and attendance monitoring. The application features a secure neon-themed login page, a responsive interface with light/dark theme support, and a six‑day bar chart with distinct colors for each day.

## Live Demo

Access the live application at:  
[https://mithanya.github.io/neurocampus-dashboard/](https://mithanya.github.io/neurocampus-dashboard/)

## Features

- Secure login page with password authentication (demo mode)
- Dashboard with overall performance percentage and key metrics
- Six‑day bar chart (Monday to Saturday) with unique colors per bar
- Task list, schedule view, and attendance tracking modules
- Light and dark theme toggle with high contrast for readability
- Fully responsive layout for desktop, tablet, and mobile devices

## Technology Stack

- HTML5
- CSS3 (custom properties, flexbox, grid, glassmorphism)
- JavaScript (ES6)
- Chart.js (version 4.4.0)

## Installation and Usage

1. Clone or download the repository.
2. Open the `index.html` file in any modern web browser.
3. Enter any username and password (demo mode – no backend validation).
4. Click "Access Dashboard" to enter the application.
5. Use the sidebar to navigate between Dashboard, Tasks, Schedule, and Attendance.
6. Click "Theme" to switch between light and dark appearance.
7. Click "Exit" to log out and return to the login page.

## File Structure
neurocampus-pro/
├── index.html # Main application file (HTML, CSS, JS)
└── README.md # Project documentation

## Design Principles

- **Professional aesthetic** – No emojis, clean typography, subtle gradients, and glassmorphic cards.
- **Accessibility** – High contrast ratios in both light and dark themes.
- **Performance** – Lightweight, no external dependencies except Chart.js CDN.
- **Responsiveness** – Adapts seamlessly to different screen sizes.

## Customization

- The six‑day performance data can be modified in the `weeklyData` array inside the `showApp()` function.
- Bar colors are defined in the `barColors` array within `initPremiumBarChart()`.
- Theme colors are managed via CSS custom properties (variables) in `:root` and `.light`.

## Browser Support

Tested and compatible with the latest versions of:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari

## Contact

Mithanya Murugesan  
LinkedIn: [https://www.linkedin.com/in/mithanya-murugesan/](https://www.linkedin.com/in/mithanya-murugesan/)

## License

This project is provided for educational and demonstration purposes.

--- 
NeuroCampus Pro – Intelligent Academic Suite
