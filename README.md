# Ramesh Kumar - 3D Interactive Portfolio (Prototype)

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## 🎯 Overview

This is a **prototype single-page portfolio website** featuring an interactive 3D developer workspace built with Three.js and React. Scroll through animated sections showcasing projects, tech stack, and skills in a futuristic neon interface.

**Live Demo**: Just open `portfolio.html` in any modern browser—no build step required!

![Screenshot](https://via.placeholder.com/1200x600/010105/9933ff?text=3D+Portfolio+Prototype)

## 🚀 Quick Start

1. Clone/download this repo.
2. Open `portfolio.html` in your browser (Chrome/Firefox recommended for best WebGL performance).
3. Scroll to explore sections: Hero → Projects → Tech → Knowledge.

## ✨ Features

- **3D Interactive Scene**: Animated developer desk with character model, monitor glow, particles, dynamic lighting, and camera scroll.
- **Scroll-Driven Sections**: Hero intro, project cards, skill progress bars, knowledge grid.
- **Responsive Design**: Mobile-friendly with smooth animations and hover effects.
- **Zero Dependencies**: Self-contained HTML using CDN scripts (React, Three.js, Babel).
- **Neon Aesthetic**: Purple (#9933ff) accents, gradients, custom shaders.

## 📱 Sections

1. **Hero**: "RAMESH KUMAR - Creative Developer Building Immersive Web Experiences"
2. **Projects**: 6 customizable cards (Attendance System, E-Commerce, Netflix Clone, etc.)
3. **Tech Stack**: Skills with proficiency bars (React 88%, JavaScript 92%, etc.)
4. **Knowledge**: Domains like Web Dev, 3D Graphics, Backend, Toolchain.

## ✏️ Customization Guide

Edit the data objects directly in `portfolio.html` (search for comments):

```javascript
// Social links (add your URLs/icons)
const SOCIALS = [ /* GitHub, LinkedIn, Twitter, Instagram */ ];

// Projects (title, desc, tags, link, optional screenshot URL)
const PROJECTS = [ /* Your 6 projects */ ];

// Skills (name, icon, level %)
const TECH = [ /* React, JS, TypeScript, Node.js, etc. */ ];

// Knowledge areas
const KNOWLEDGE = [ /* Web Dev, 3D Graphics, etc. */ ];
```

**Pro Tip**: Add project screenshots via `img: "https://your-image-url.png"` or local paths.

## 🛠 Tech Stack

| Frontend | 3D/Graphics | Tools |
|----------|-------------|-------|
| React (CDN) | Three.js r128 | WebGL |
| HTML5/CSS3 | Custom Shaders | Babel (in-browser) |
| GSAP-like Animations | Particle Systems | Google Fonts |

## 📝 Note

This is **just a prototype portfolio website**. Enhance with more animations, external hosting (Netlify/Vercel), or convert to full React app.

## 📄 License

MIT License © 2026 [Ramesh Kumar](https://github.com/igene-wa18). See [LICENSE](LICENSE) for details.

## 🔗 Connect

- GitHub: [igene-wa18](https://github.com/igene-wa18)
- LinkedIn: [ramesh-kumar-a0785131a](https://www.linkedin.com/in/ramesh-kumar-a0785131a/)
- Instagram: [@igene_wa18](https://www.instagram.com/igene_wa18/)

**Made with ❤️ for portfolios. Fork & customize!**

