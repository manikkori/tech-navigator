# 🚀 Tech Career Navigator (TechNav)

Tech Career Navigator is a comprehensive, interactive web application designed to help Computer Science and IT students discover their ideal tech career paths. By replacing confusion with clarity, this platform offers a smart psychological assessment and a massive library of tech domains to guide students toward a career that fits their skills and interests.

## 🌟 Key Features

* **🧠 Smart Career Assessment Quiz:** A situational quiz that analyzes user preferences and recommends the best-suited tech domain (e.g., Development, Data & AI, Cybersecurity).
* **📚 Massive Career Library:** Detailed information on 40+ tech careers categorized into 8 distinct fields, complete with descriptions and required skills.
* **✨ The "Magic Connection":** Seamlessly integrates quiz results with the career library using LocalStorage, automatically filtering and highlighting the recommended path for the user.
* **🌐 Bilingual Support (No-Reload):** Fully localized in both **English** and **Hinglish** to make the platform highly accessible and relatable for Indian college students.
* **🌙 Premium Dark Mode:** A sleek, user-friendly Dark/Light theme toggle that persists across all pages.
* **📱 Fully Responsive UI:** Designed with a mobile-first approach using Tailwind CSS, ensuring a flawless experience across desktops, tablets, and smartphones.
* **⚡ Dynamic Rendering:** Uses Vanilla JavaScript to render UI components dynamically from a centralized JSON-like data structure, making the codebase scalable and easy to maintain.

## 🛠️ Tech Stack

* **Frontend Structure:** HTML5
* **Styling & UI:** Tailwind CSS (via CDN)
* **Logic & DOM Manipulation:** Vanilla JavaScript (ES6+)
* **State Management:** Browser LocalStorage (for Theme, Language, and Quiz Results)
* **Typography:** Google Fonts (Poppins)

## 📂 Folder Structure

\`\`\`text
tech-career-navigator/
│
├── index.html                 # Main Landing Page & About Section
├── careers.html               # Dynamic Career Library & Filters
├── quiz.html                  # Career Assessment Interface
│
├── js/                        
│   ├── main.js                # Core UI logic, Filtering, and Modals
│   ├── quiz.js                # Quiz logic and result calculation
│   ├── data.js                # Centralized database of 40+ careers
│   ├── lang.js                # Bilingual translation logic
│   └── theme.js               # Dark/Light mode toggle logic
│
└── locales/                   
    ├── en.json                # English translation data
    └── hi.json                # Hinglish translation data
\`\`\`

## 🚀 How to Run Locally

1. Clone or download this repository to your local machine.
2. Open the project folder in your favorite code editor (e.g., VS Code).
3. Since the project uses the Fetch API for language JSON files, it needs to be run on a local server.
4. If using VS Code, install the **Live Server** extension.
5. Right-click on `index.html` and select **"Open with Live Server"**.
6. The application will launch in your default web browser.

## 💡 Why This Project?

During my BCA studies, I noticed a common pattern: most computer science students are highly confused about what to pursue after learning basic programming. The tech industry is vast, spanning Web Development, Cloud DevOps, AI, and UI/UX. TechNav was built to act as a digital mentor, bridging the gap between theoretical confusion and practical career roadmaps.

---
*Developed with ❤️ by Manik*
