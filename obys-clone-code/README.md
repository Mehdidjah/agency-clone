# Obys Agency Website

A modern portfolio website with smooth scroll, stylish preloader, WebGL/3D hover effects and GSAP-driven animations.

**Created by Mehdi**

![Preview](https://github.com/user-attachments/assets/290d7236-7baf-4ed7-ab3a-3b190eabf105)

## ✨ Features

- 📱 Fully responsive layout
- 🎞️ GSAP animations (ScrollTrigger, SplitText, ScrollSmoother*)
- 🏳️ Canvas WebGL "flag" hover (Three.js)
- 🖼️ Displacement-hover for project images (pure WebGL, no Three.js)
- 🎥 Custom video player button that follows the cursor
- 🌀 Wavy underline interactions & text hover effects
- ⛳ Scroll indicator with speed modulation
- ⚡ Preloader with counter and word-fade sequence

## 🧱 Tech Stack

- HTML5
- SCSS/CSS (BEM methodology)
- JavaScript (ES Modules)
- GSAP 3 (ScrollTrigger, SplitText, ScrollSmoother*)
- Three.js

## 🚀 Deployment

This project is configured for easy deployment on Vercel. 

### Deploy to Vercel

1. Push your code to GitHub
2. Go to [vercel.com](https://vercel.com) and click "Add New Project"
3. Import your GitHub repository
4. Vercel will automatically detect it as a static site
5. Click "Deploy"

Or use Vercel CLI:
```bash
npm i -g vercel
vercel --prod
```

## 📁 Project Structure

```
├── index.html          # Main HTML file
├── assets/            # All assets (fonts, images)
│   ├── fonts/        # Web fonts
│   └── img/          # Images
├── css/              # Stylesheets
│   ├── dev/         # Development CSS
│   └── index.min.css # Production CSS
├── js/               # JavaScript files
│   ├── dev/         # Development JS
│   └── index.min.js  # Production JS
└── files/            # Video files
```

## 🛠️ Development

To run locally:

```bash
# Using Python
python3 -m http.server 8000

# Using Node.js
npx serve
```

Then open `http://localhost:8000` in your browser.

## 📝 License

This project is created by Mehdi. All rights reserved.
