# 🇨🇦 Canadian-Format Resume Builder & PDF Exporter

An open-source, lightweight web application built to generate ATS-optimized, Canadian-standard resumes. Designed specifically for international candidates and professionals seeking employment opportunities and visa sponsorship in Canada.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)

---

## 🌟 Key Features

* **Strictly Canadian HR Compliant:** Standard single-column layout with zero personal detail fields (no photos, birth dates, or marital status) to eliminate hiring bias and pass ATS scans.
* **Visa Sponsorship Ready:** Includes optional fields to highlight international relocation readiness and open work availability directly in the header.
* **Live Real-Time Preview:** Side-by-side editing pane allows users to watch their resume update instantaneously as they type.
* **Zero Dependencies / Client-Side Only:** Runs 100% locally inside the browser. No server setup, no database, and complete data privacy (your personal information never leaves your browser).
* **One-Click PDF Export:** Uses native browser print controls optimized with `@media print` CSS rules to generate a clean, print-ready PDF layout without extra UI clutter.

---

## 🚀 How to Use

### Option 1: Direct Usage (Single File)
1. Download or clone this repository.
2. Open `index.html` directly in any modern Web Browser (Chrome, Firefox, Edge, Safari).
3. Fill in your professional background in the left panel.
4. Click **Download as PDF** or press `Ctrl + P` / `Cmd + P` to export your resume.

### Option 2: Run via Live Server
If you are developing locally with VS Code:
```bash
# Clone the repository
git clone [https://github.com/YOUR_USERNAME/canadian-resume-builder.git](https://github.com/YOUR_USERNAME/canadian-resume-builder.git)

# Open the directory
cd canadian-resume-builder

# Open in VS Code (or launch with Live Server extension)
code .
