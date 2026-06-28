# Camera Sidebar Navigation

A responsive, **CSS-only animated sidebar navigation menu** built without a single line of JavaScript. Uses the checkbox hack to toggle a smooth slide-in/out sidebar with social media links and Font Awesome icons.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![No JavaScript](https://img.shields.io/badge/JavaScript-None-lightgrey?style=flat)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

---

## 🔴 Live Demo

> 🌐 [View Live Site](https://brinda410.github.io/camera-sidebar-navigation)

---

## ✨ Features

- ⚡ **Zero JavaScript** — toggle powered entirely by the CSS checkbox hack
- 🎞️ **Smooth animation** — `0.4s` slide-in transition on the sidebar
- 📱 **Responsive layout** — fixed sidebar overlay works on all screen sizes
- 🎨 **Font Awesome icons** — icons alongside each nav item and social links
- 🔤 **Google Fonts** — Poppins typeface for a clean, modern look
- 🌑 **Semi-transparent dark sidebar** — `rgba(0,0,0,0.85)` with subtle glow shadow
- 🖱️ **Hover effects** — nav items highlight, social icons scale on hover

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Semantic structure, checkbox input trick |
| CSS3 | Animations, transitions, fixed positioning |
| [Font Awesome 6.4](https://fontawesome.com/) | Navigation & social icons |
| [Google Fonts – Poppins](https://fonts.google.com/specimen/Poppins) | Typography |

---

## 📁 Project Structure
camera-sidebar-navigation/

├── index.html       # Main HTML file

├── style.css        # All styles — layout, sidebar, animations

├── photo.jpg        # Background image

└── README.md

---

## 🚀 Getting Started

1. **Clone the repository**
```bash
   git clone https://github.com/brinda410/camera-sidebar-navigation.git
   cd camera-sidebar-navigation
```

2. **Add your background image**
   Drop any image named `photo.jpg` into the project folder, or update the path in `style.css`.

3. **Open in browser**
```bash
   open index.html
```
   No build tools, no dependencies, no setup required.

---

## ⚙️ How It Works

The sidebar toggle uses the **CSS checkbox hack** — a pure CSS pattern with zero JavaScript:

```css
/* Clicking the hamburger label checks the hidden checkbox */
#check:checked ~ .sidebar_menu {
    left: 0;       /* slides sidebar into view */
}

#check:checked ~ .btn_one {
    opacity: 0;    /* hides the hamburger icon */
}
```

The sidebar starts off-screen at `left: -300px` and slides to `left: 0` on check, driven by a CSS `transition`.

---

## 🎨 Customization

| What to change | Where |
|---|---|
| Sidebar width | `.sidebar_menu { width: ... }` in `style.css` |
| Background image | `.main_box { background: url(...) }` in `style.css` |
| Brand name | `<a href="#">SONY</a>` in `index.html` |
| Nav links | `<ul>` inside `.menu` in `index.html` |
| Hover accent color | `.sidebar_menu .menu li:hover` in `style.css` |

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙋‍♀️ Author

**Brinda**
- GitHub: [@brinda410](https://github.com/brinda410)

- LinkedIn: [linkedin.com/in/your-profile](https://www.linkedin.com/in/brindashree-r-3a239032b/)

⭐ If you found this useful, consider giving it a star!
