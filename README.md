# 🚀 Shuvranshu Sekhar Sahoo - Portfolio

![Portfolio Banner](https://capsule-render.vercel.app/api?type=waving&color=00f3ff&height=200&section=header&text=Shuvranshu%20Sekhar%20Sahoo&fontSize=50&fontColor=000000&fontAlignY=35)

<div align="center">

![GitHub License](https://img.shields.io/github/license/SahooShuvranshu/SahooShuvranshu.github.io?style=for-the-badge&color=blue)
![GitHub stars](https://img.shields.io/github/stars/SahooShuvranshu/SahooShuvranshu.github.io?style=for-the-badge&color=yellow)
![GitHub forks](https://img.shields.io/github/forks/SahooShuvranshu/SahooShuvranshu.github.io?style=for-the-badge&color=orange)
![GitHub issues](https://img.shields.io/github/issues/SahooShuvranshu/SahooShuvranshu.github.io?style=for-the-badge&color=red)
![GitHub last commit](https://img.shields.io/github/last-commit/SahooShuvranshu/SahooShuvranshu.github.io?style=for-the-badge&color=00f3ff)
![GitHub repo size](https://img.shields.io/github/repo-size/SahooShuvranshu/SahooShuvranshu.github.io?style=for-the-badge&color=green)

</div>

<br>

A highly interactive, **gamer-themed personal portfolio website** built to showcase my skills, projects, and services. Featuring a **dynamic theme system** that changes monthly, responsive grid layouts, and a modern, app-like navigation experience.

**🌐 Live Demo:** [sahooshuvranshu.github.io](https://sahooshuvranshu.github.io)

---

## ✨ Key Features

- **🎨 Dynamic Theme System**: The site automatically switches themes based on the current month, keeping the look fresh and engaging.
  - **January**: Elden Ring (Gold/Dark Fantasy)
  - **February**: Stardew Valley (Spring/Pastel)
  - **March**: Fallout (Terminal Green/Retro)
  - **April**: Halo (Sci-Fi/Military)
  - **May**: Terraria (Adventure/Forest)
  - **June**: Minecraft (Blocky/Green)
  - **July**: GTA Vice City (Retro/Neon)
  - **August**: The Witcher 3 (Silver/Dark Fantasy)
  - **September**: Doom (Aggressive/Red)
  - **October**: Hollow Knight (Moody/Ethereal)
  - **November**: God of War (Nordic/Red)
  - **December**: Cyberpunk (Neon/Future)

- **📱 Fully Responsive**: Optimized for desktops, tablets, and mobile devices with a fluid grid system.
- **⚡ High Performance**: Built with vanilla HTML, CSS, and JavaScript—no heavy frameworks.
- **🧩 Modular Architecture**: Content is loaded dynamically from separate HTML files (`pages/`) for easy maintenance.
- **🎮 Gamified UI**: Custom sound effects, hover animations, and a "status" system.

---

## 🛠️ Technologies Used

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![FontAwesome](https://img.shields.io/badge/Font%20Awesome-538DD7?style=for-the-badge&logo=fontawesome&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

---

## 📂 Project Structure

```bash
SahooShuvranshu.github.io/
├── index.html              # Main entry point (Shell & Navigation)
├── README.md               # Documentation
├── LICENSE                 # MIT License
├── CNAME                   # Custom domain config
├── media/                  # Images, sounds, and assets
└── pages/                  # Dynamic content sections
    ├── about.html          # Profile & Bio
    ├── skills.html         # Tech Stack & Stats
    ├── projects.html       # Project Showcase
    ├── services.html       # Offerings & Pricing
    ├── awards.html         # Certifications & Achievements
    └── blog.html           # Blog Integration
```

---

## 🚀 Getting Started

To run this project locally:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/SahooShuvranshu/SahooShuvranshu.github.io.git
    ```

2.  **Navigate to the directory:**
    ```bash
    cd SahooShuvranshu.github.io
    ```

3.  **Start a local server:**
    Since this project uses `fetch()` to load pages, you need a local server (opening `index.html` directly won't work due to CORS).
    
    *Using Python 3:*
    ```bash
    python3 -m http.server 8000
    ```
    
    *Using VS Code Live Server:*
    Right-click `index.html` and select "Open with Live Server".

4.  **Open in Browser:**
    Visit `http://localhost:8000`

---

## ⚙️ Configuration & Customization

### Theme Logic
The themes are defined in the `themes` array within `index.html`. Each theme object contains CSS variable overrides for colors, fonts, and background images.

```javascript
const themes = [
    {
        name: "Elden Ring",
        accent: "#c3a94e",
        // ... other properties
    },
    // ... other themes
];
```

To add a new theme, simply append a new object to this array. The `applyTheme()` function automatically handles the month-based selection.

### Content Management
The website uses a Single Page Application (SPA) approach where content is fetched dynamically:
- **Projects**: Edit `pages/projects.html`. Use the `.card` class for consistency.
- **Services**: Edit `pages/services.html`.
- **Profile**: Edit `pages/about.html`.

---

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

<div align="center">
  <p>Made with ❤️ and ☕ by <a href="https://github.com/SahooShuvranshu">Shuvranshu</a></p>
</div>
