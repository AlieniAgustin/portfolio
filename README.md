# 🚀 Agustín Alieni - Personal Portfolio

Welcome to the repository of my personal portfolio website. This project serves as a central hub to demonstrate my skills in **Software Engineering, Artificial Intelligence, and Backend Development**.

The site is built as a **static web application** (SPA feel) without a backend dependency, utilizing vanilla JavaScript to handle logic, routing, and a custom localization system.

🔗 **Live Demo:** link portfolio to do hernan

---

## 🛠 Project Structure

The project follows a clean and modular architecture to separate content, styles, and logic.

```text
/portfolio
│
├── index.html            # Main entry point (Semantic HTML5)
├── README.md             # Project documentation
│
├── css/
│   ├── style.css         # Core variables and styling (CSS3)
│   └── responsive.css    # Media queries for mobile/tablet adaptation
│
├── js/
│   ├── main.js           # DOM manipulation, event listeners, and UI logic
│   └── translations.js   # JSON-based dictionary for EN/ES text content
│
└── assets/
    ├── img/              # Project thumbnails, profile picture, and icons
    ├── videos/           # Local video assets
    └── docs/             # Downloadable resources
        ├── cv-agustin-alieni-es.pdf  # Resume in Spanish
        └── cv-agustin-alieni-en.pdf  # Resume in English
```

---

## ✨ Key Features

### ⚡ Zero Dependencies
Built with pure **HTML, CSS, and JavaScript**. No heavy frameworks required.

### 🌍 Dynamic Internationalization (i18n)

Custom JavaScript logic allows users to toggle between **English and Spanish** instantly.

- Smart content switching updates:
  - Text labels
  - Video sources (`src`)
  - Downloadable CV links (`href`)

### 📱 Fully Responsive
Optimized for **desktop, tablet, and mobile devices**, ensuring a consistent user experience across screen sizes.
