# Project Structure

This document describes the organization of the Obys Agency website project.

## 📁 Directory Structure

```
/
├── index.html                 # Main HTML file
├── vercel.json               # Vercel deployment configuration
├── .gitignore                # Git ignore rules
├── .editorconfig            # Editor configuration
├── README.md                 # Project documentation
├── PROJECT_STRUCTURE.md      # This file
│
├── assets/                   # Static assets
│   ├── fonts/               # Web fonts (WOFF2 format)
│   │   ├── PlainReg.woff2
│   │   ├── plainLight.woff2
│   │   ├── silkSerif.woff2
│   │   └── silkSerifReg.woff2
│   └── img/                 # Images
│       ├── favicon.ico      # Site favicon
│       ├── main-poster.jpg  # Video poster image
│       ├── effect-image.jpg # Displacement effect image
│       ├── Flag.jpg         # Flag image for canvas
│       ├── group.jpg        # Team photo
│       └── [project images] # Project showcase images
│
├── css/                      # Stylesheets
│   ├── dev/
│   │   └── index.css        # Development CSS (readable, organized)
│   └── index.min.css        # Production CSS (minified)
│
├── js/                       # JavaScript files
│   ├── dev/
│   │   └── index.js         # Development JavaScript (readable)
│   └── index.min.js         # Production JavaScript (minified)
│
└── files/                    # Media files
    └── Obys-Showreel-2022.mp4  # Video file
```

## 📋 File Organization

### Root Files
- **index.html** - Main HTML entry point
- **vercel.json** - Vercel deployment configuration
- **README.md** - Project documentation and setup instructions
- **.gitignore** - Git ignore patterns
- **.editorconfig** - Code editor configuration

### Assets
- **assets/fonts/** - Web fonts in WOFF2 format for optimal performance
- **assets/img/** - All image assets used in the project

### Stylesheets
- **css/dev/index.css** - Development CSS with:
  - Organized sections with comments
  - CSS custom properties (variables)
  - Readable formatting
- **css/index.min.css** - Production CSS:
  - Minified for performance
  - Generated from dev CSS
  - Single line, no comments

### JavaScript
- **js/dev/index.js** - Development JavaScript:
  - Modern ES6+ syntax
  - Organized modules
  - Readable formatting
- **js/index.min.js** - Production JavaScript:
  - Minified for performance
  - Generated from dev JS

### Media Files
- **files/** - Video files and other media assets

## 🎯 Development Workflow

1. **Edit source files** in `css/dev/` and `js/dev/`
2. **Test locally** using a local server
3. **Build/minify** before deployment
4. **Deploy** to Vercel

## 📝 Notes

- Always edit files in the `dev/` directories
- Minified files are generated automatically
- Never edit minified files directly
- Keep assets organized by type (fonts, images, media)

