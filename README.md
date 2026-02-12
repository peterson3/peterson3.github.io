# Peterson Andrade — Portfolio

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://peterson3.github.io)
[![HTML5](https://img.shields.io/badge/HTML5-Modern-orange)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-Inline-blue)](https://developer.mozilla.org/en-US/docs/Web/CSS)

Modern, self-contained portfolio website for Peterson Andrade — .NET/C# Backend Engineer specializing in Funds Administration, event-driven architecture, and financial systems.

## 🎯 Overview

This is a single-page portfolio site built with modern HTML5, CSS3, and vanilla JavaScript. The entire site is self-contained in one HTML file with zero external dependencies, making it fast, reliable, and easy to deploy.

**Live Site:** [peterson3.github.io](https://peterson3.github.io)

## ✨ Features

- **🎨 Modern Design** — Dark theme with gradient backgrounds and animated grain texture
- **📱 Fully Responsive** — Works seamlessly on desktop, tablet, and mobile
- **⚡ Zero Dependencies** — No Bootstrap, jQuery, or external libraries
- **🎯 Performance-First** — Inline CSS/JS, optimized for speed
- **♿ Accessible** — Semantic HTML with proper ARIA labels
- **🔗 Deep Links** — Smooth scrolling navigation with active section highlights

## 🛠️ Tech Stack

- **HTML5** — Semantic markup with modern best practices
- **CSS3** — Custom properties (CSS variables), Grid, Flexbox, animations
- **Vanilla JavaScript** — Smooth scrolling, intersection observers, no frameworks
- **GitHub Pages** — Free hosting with automatic deployment

## 📂 Project Structure

```
peterson3.github.io/
├── index.html          # Complete portfolio (HTML + CSS + JS)
├── README.md           # This file
└── LICENSE             # Repository license
```

## 🚀 Local Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/peterson3/peterson3.github.io.git
   cd peterson3.github.io
   ```

2. **Open in browser:**
   ```bash
   # On Windows
   start index.html
   
   # On macOS
   open index.html
   
   # On Linux
   xdg-open index.html
   ```

3. **Or use a local server:**
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Node.js (if you have http-server installed)
   npx http-server
   ```

   Then open `http://localhost:8000` in your browser.

## 📝 Content Sections

- **Hero** — Introduction with key skills and focus areas
- **Work** — Backend engineering expertise and domain experience
- **Projects** — Portfolio of technical projects and tools
- **Stack** — Technologies, tools, and architecture principles
- **Content** — Talks, tutorials, and content creation
- **Contact** — Ways to get in touch

## 🎨 Customization

To customize the site for your own use:

1. **Colors** — Edit CSS variables in the `:root` selector (lines 11-18)
2. **Content** — Update text in each section (starting line ~300)
3. **Links** — Replace placeholder URLs with your actual profiles
4. **Sections** — Add/remove sections as needed (each wrapped in `<section>`)

### Key CSS Variables

```css
--bg: #070b14;           /* Background color */
--a: #7c3aed;            /* Purple accent */
--b: #22d3ee;            /* Cyan accent */
--c: #10b981;            /* Green accent */
--max: 1120px;           /* Max content width */
```

## 📦 Deployment

### GitHub Pages (Automatic)

1. Push changes to `main` branch
2. GitHub Pages automatically deploys from the root directory
3. Site is live at `https://[username].github.io`

### Manual Deployment

Since it's a single HTML file, you can deploy anywhere:
- **Netlify:** Drag & drop the file
- **Vercel:** Connect the repo or upload file
- **AWS S3:** Upload to bucket with static hosting enabled
- **Any web server:** Just upload `index.html`

## 🤝 Contributing

This is a personal portfolio, but if you find bugs or have suggestions:

1. Open an issue describing the problem/suggestion
2. Or fork the repo and submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🔗 Connect

- **GitHub:** [@peterson3](https://github.com/peterson3)
- **LinkedIn:** [Peterson Andrade](https://www.linkedin.com/in/your-handle/)
- **Email:** your.email@example.com

---

**Built with ❤️ and a focus on clean architecture, reliability, and simplicity.**