# Mahad Ahmad — Personal Portfolio

![Portfolio Preview](./.github/preview.webp) <!-- Optional: Add a preview screenshot of your site here in the future -->

A visually premium, fully responsive, single-file personal portfolio built for modern developers. Combining minimalistic monochrome aesthetics with dynamic 3D interactions, this portfolio is designed to showcase skills, experience, and projects effortlessly.

Deployed with **GitHub Pages** — no backend or complicated build steps required.

## ✨ Features

- **Single-File Architecture:** All HTML, CSS, and Vanilla JavaScript are neatly contained within `index.html`.
- **3D Hero Interactions:** A dynamic background powered by Three.js featuring a rotating wireframe icosahedron and floating particle map.
- **Custom UI Physics:** Interactive 3D tilt cards, custom cursor (dot and tracking ring), and smooth scroll-triggered reveal animations.
- **Strict Design System:** HSL-tailored monochrome palette paired with modern typography (`Syne` and `JetBrains Mono`).
- **Fully Responsive:** Seamlessly adapts to desktop, tablet, and mobile with a custom animated hamburger menu overlay.

## 🛠️ Tech Stack

- **Structure & Styling:** Semantic HTML5, Vanilla CSS3 (Custom Properties, Grid, Flexbox, Animations).
- **Interactivity:** Vanilla JavaScript (ES6+), IntersectionObserver API.
- **3D Graphics:** [Three.js](https://threejs.org/) (loaded via CDN).

## 🚀 Getting Started

Since this project has zero external frameworks or backend dependencies, getting started is extremely straightforward:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/mahadkhaann/mahadkhaann.github.io.git
   ```
2. **Navigate to the directory:**
   ```bash
   cd mahadkhaann.github.io
   ```
3. **Run Locally:**
   Simply double-click the `index.html` file to open it in your default web browser. Alternatively, use tools like VS Code Live Server for hot reloading.

## 📦 Deployment

This portfolio is ready natively for **GitHub Pages**.

1. Ensure the code is on the `main` branch.
2. Go to your GitHub Repository **Settings** > **Pages**.
3. Set the source to **Deploy from a branch** and select `main` > `/(root)`.
4. Click Save. Within a minute or two, your portfolio will go live!

## 🧑‍💻 Customization

The site is built to be easily personalized. Look through `index.html` and tweak the core CSS variables under `:root` to change the theme:
- Update font families (`--font-display`, `--font-mono`).
- Tweak the monochrome color palette (`--bg-primary`, `--text-primary`, etc.). 

If you want to unhide the **Projects** or **Blog** sections, simply search for `<!-- 04 / PROJECTS -->` or `<!-- 06 / BLOG -->` in the `index.html` file and remove the HTML comments surrounding them.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
