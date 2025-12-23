# Obys Agency Website

A modern, creative design agency website built with vanilla JavaScript, GSAP animations, and Three.js.

## 🚀 Deployment to Vercel

This project is ready to deploy on Vercel. Follow these steps:

### Option 1: Deploy via Vercel CLI

```bash
# Install Vercel CLI (if not already installed)
npm i -g vercel

# Deploy
vercel

# For production deployment
vercel --prod
```

### Option 2: Deploy via Vercel Dashboard

1. Push your code to GitHub/GitLab/Bitbucket
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your repository
5. Vercel will automatically detect the static site
6. Click "Deploy"

### Configuration

The `vercel.json` file is already configured with:
- Static file serving
- Cache headers for fonts, images, CSS, and JS
- CORS headers for fonts
- Proper routing

## 📁 Project Structure

```
/
├── index.html              # Main HTML file
├── vercel.json            # Vercel configuration
├── .gitignore             # Git ignore rules
├── .editorconfig          # Editor configuration
├── README.md              # Project documentation
├── PROJECT_STRUCTURE.md   # Detailed structure documentation
├── assets/
│   ├── fonts/             # Web fonts (WOFF2)
│   └── img/               # Images
├── css/
│   ├── dev/
│   │   └── index.css      # Development CSS (structured)
│   └── index.min.css      # Production CSS (minified)
├── js/
│   ├── dev/
│   │   └── index.js       # Development JavaScript
│   └── index.min.js       # Production JavaScript
└── files/
    └── Obys-Showreel-2022.mp4  # Video file
```

> 📖 See [PROJECT_STRUCTURE.md](./PROJECT_STRUCTURE.md) for detailed structure documentation.

## 🎨 CSS Structure

The CSS file is organized into logical sections:

1. **Fonts** - @font-face declarations
2. **CSS Variables** - Custom properties for colors, fonts, transitions
3. **Reset / Normalize** - Base resets and normalization
4. **Base Styles** - Body, HTML, and global styles
5. **Layout** - Wrapper, container, and layout utilities
6. **Utilities** - Helper classes (sr-only, hidden, etc.)
7. **Components - Typography** - Text effects and typography
8. **Components - Preloader** - Loading screen styles
9. **Components - Flag Canvas** - Three.js canvas styles
10. **Components - Scroll Indicator** - Scroll animation indicator
11. **Components - Header & Menu** - Navigation components
12. **Components - Footer** - Footer styles
13. **Components - Hero Section** - Hero area styles
14. **Components - Video Section** - Video player styles
15. **Components - Projects Section** - Portfolio grid
16. **Components - About Section** - About page content
17. **Components - Partnership Section** - Partners marquee
18. **Media Queries** - Responsive breakpoints

## 🛠️ Development

### Local Development

```bash
# Using Python's built-in server
python3 -m http.server 8000

# Or using Node.js http-server
npx http-server -p 8000
```

Then open `http://localhost:8000` in your browser.

## 📝 Features

- ✨ Smooth scroll animations (GSAP ScrollTrigger)
- 🎨 Custom cursor effects
- 🎬 Video player with smart source selection
- 📱 Fully responsive design
- ⚡ Optimized performance
- ♿ Accessibility features (ARIA labels, semantic HTML)
- 🎯 Modern ES6+ JavaScript
- 🎨 CSS Custom Properties for easy theming

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This is a clone project for educational purposes.

## 🔗 Links

- Live Demo: [Deploy to Vercel to get your URL]
- Original: Obys Agency

