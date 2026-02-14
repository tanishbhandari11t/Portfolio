# 🎨 Tanish Bhandari - Portfolio Website

Welcome to the comprehensive documentation for Tanish Bhandari's Portfolio - a cutting-edge, modern web development portfolio featuring seamless animations, responsive design, and an immersive user experience inspired by Awwwards-winning websites.

## 📋 Table of Contents
- [Project Overview](#project-overview)
- [Live Demo](#live-demo)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation & Setup](#installation--setup)
- [Design System](#design-system)
- [Animation Architecture](#animation-architecture)
- [Responsive Design](#responsive-design)
- [Performance Optimizations](#performance-optimizations)
- [Browser Compatibility](#browser-compatibility)
- [Deployment](#deployment)
- [Contact](#contact)

## 🎯 Project Overview
This portfolio showcases my work as a Computer Science student at Scaler School of Technology, Bengaluru. It demonstrates advanced web development techniques including:

- Award-worthy design principles inspired by Awwwards-winning sites
- Seamless page transitions using GSAP animations
- Interactive storytelling through scroll-triggered animations
- Mobile-first responsive design with breakpoints at 1000px
- Performance-optimized assets with lazy loading and efficient caching
- Modern development workflow using Vite for fast development and building
- Peach (#FFDAB9) themed color palette for a warm, elegant aesthetic

## 🚀 Live Demo
🌐 [View Live Portfolio](https://github.com/tanishbhandari11t/Portfolio)

## ✨ Features

### Core Features
- **Smooth Page Transitions**: Seamless navigation between pages with GSAP-powered animations
- **Scroll-Triggered Animations**: Dynamic content reveals and interactions based on scroll position
- **Responsive Design**: Optimized for all devices from mobile to desktop
- **Interactive Navigation**: Elegant slide-in menu with smooth animations
- **Contact Form**: Professional contact form with validation and success states
- **Project Showcase**: Interactive portfolio gallery with hover effects and 3D card animations
- **Performance Monitoring**: Built-in performance optimizations and lazy loading

### Featured Projects
- **Interactive World Map** - Full-stack web app with interactive country details
- **AuraPad** - Real-time collaborative code editor with chat
- **Timer Buddy** - Focus timer with multiple modes and themes
- **Personal Diary** - Private journaling web app with dark/light mode
- **3D Mapping** - 3D visualization and mapping project

### Advanced Features
- **Parallax Scrolling**: Multi-layer parallax effects for depth
- **Image Preloading**: Intelligent image preloading for smooth transitions
- **Animation Sequencing**: Complex animation timelines synchronized with user interactions
- **Mobile-First Animations**: Touch-friendly animations optimized for mobile devices

## 🛠 Technologies Used

### Core Technologies
- **HTML5**: Semantic markup with modern HTML features
- **CSS3**: Advanced CSS with custom properties, flexbox, and grid
- **JavaScript ES6+**: Modern JavaScript with modules and async/await
- **Vite**: Lightning-fast build tool and development server

### Animation & Effects
- **GSAP (GreenSock)**: Professional-grade animation library
- **ScrollTrigger**: GSAP plugin for scroll-based animations
- **Lenis**: Smooth scrolling library for enhanced user experience

### Styling & Design
- **Custom Fonts**: Three custom typefaces for distinctive typography
- **CSS Custom Properties**: Design system with CSS variables
- **Responsive Units**: Flexible sizing with rem, em, and viewport units
- **CSS Grid & Flexbox**: Modern layout techniques

### Development Tools
- **Node.js**: JavaScript runtime for development tools
- **npm**: Package manager for dependencies
- **Git**: Version control

### Deployment & Hosting
- **Vercel**: Global edge network deployment
- **GitHub**: Version control and collaboration

## 📁 Project Structure
```
newportfolio/
├── css/                     # Stylesheets
│   ├── globals.css          # CSS variables & global styles
│   ├── home.css             # Homepage styles
│   ├── about.css            # About section styles
│   ├── menu.css             # Navigation menu styles
│   ├── contact.css          # Contact page styles
│   ├── footer.css           # Footer styles
│   ├── fonts.css            # Custom font declarations
│   ├── transition.css       # Page transition styles
│   └── work.css             # Work/projects section styles
├── js/                      # JavaScript modules
│   ├── hero.js              # Hero section animations
│   ├── featured-work.js     # Featured projects animations
│   ├── services.js          # Skills/services section
│   ├── about.js             # About section animations
│   ├── menu.js              # Navigation menu logic
│   ├── footer.js            # Footer animations
│   ├── contact.js           # Contact form handling
│   ├── lenis-scroll.js      # Smooth scrolling
│   └── transition.js        # Page transitions
├── public/                  # Static assets
│   ├── fonts/               # Custom typefaces
│   └── images/              # All images
│       ├── global/          # Site-wide icons & symbols
│       ├── hero/            # Hero section images
│       ├── services/        # Skills section images
│       ├── services-header/ # Portrait image
│       └── work-items/      # Project screenshots
├── index.html               # Main homepage
├── contact.html             # Contact page
├── vite.config.js           # Vite configuration
├── package.json             # Dependencies
└── README.md                # This file
```

## 🚀 Installation & Setup

### Prerequisites
- Node.js (v16 or higher)
- npm package manager
- Git for version control

### Local Development Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/tanishbhandari11t/Portfolio.git
   ```

2. Navigate to project folder:
   ```bash
   cd Portfolio
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start development server:
   ```bash
   npm run dev
   ```
   The development server will start at `http://localhost:5173`

5. Build for production:
   ```bash
   npm run build
   ```

### Available Scripts
- `npm run dev` - Start development server with hot reload
- `npm run build` - Build optimized production bundle
- `npm run preview` - Preview production build locally

## 🎨 Design System

### Color Palette (Peach Theme)
The portfolio uses a warm peach-based color system defined in CSS custom properties:

| Variable | Value | Role |
|---|---|---|
| `--bg` | `#FFDAB9` | Main background (peach) |
| `--bg2` | `#f0c9a6` | Secondary background (darker peach) |
| `--fg` | `#2d1810` | Foreground/text (dark brown) |
| `--accent1` | `#e07850` | Primary accent (terracotta) |
| `--accent2` | `#ffe8d0` | Secondary accent (light peach) |
| `--accent3` | `#c9956b` | Tertiary accent (golden brown) |
| `--accent4` | `#8b5e3c` | Quaternary accent (medium brown) |

### Typography System
Three custom typefaces create the distinctive visual identity:

1. **Rader** - Used for headings (h1, h2, h3)
2. **Formula Narrow** - Used for body text and descriptions
3. **Supply Mono** - Used for UI elements and labels

## 🎭 Animation Architecture

### Page Transitions
Multi-layer overlay reveal system using GSAP with 5 sequenced overlays.

### Scroll-Triggered Animations

#### Hero Section
- **Image Cycling**: Continuous project image rotation every 250ms
- **Scroll Progress**: Image transforms based on scroll position
- **Responsive Scaling**: Dynamic scaling from 0.25 to 1

#### Featured Work Section
- **Horizontal Scrolling**: Project titles move horizontally across 4x viewport width
- **3D Image Cards**: 10 cards with z-index manipulation and staggered animations
- **Progress Indicators**: Visual section progress feedback

#### Services/Skills Section
- **Card Pinning**: Skill cards pin during scroll for layered effect
- **Vertical Movement**: Smooth transitions between descriptions

## 📱 Responsive Design

### Mobile Strategy (≤ 1000px)
- Simplified animations for performance
- Touch-friendly interactions
- Single-column stacked layouts

### Desktop Enhancements (> 1000px)
- Full animation suite enabled
- Multi-column grid layouts
- Interactive hover states

## ⚡ Performance Optimizations
- Hardware-accelerated GPU transforms
- Image preloading and caching
- Debounced resize handlers
- Code splitting with ES modules
- Vite build optimization

## 🌐 Browser Compatibility
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile Safari (iOS 14+)
- Chrome Mobile (Android 10+)

## 🚀 Deployment

### Vercel Deployment
1. Connect GitHub repository to Vercel
2. Automatic deployments on push to main branch
3. No additional environment variables required

## 📞 Contact

### About Me
**Tanish Bhandari**
- 📍 Bengaluru, Karnataka, India
- 🎓 BSc in Data Science & Application, Scaler School of Technology (2025-2029)
- 📧 Email: [tanishwork33@gmail.com](mailto:tanishwork33@gmail.com)
- 💼 LinkedIn: [tanishbhandari](https://linkedin.com/in/tanishbhandari)
- 🐙 GitHub: [@tanishbhandari11t](https://github.com/tanishbhandari11t)

### Technical Skills
- **Languages**: Python, Java, JavaScript, HTML, CSS
- **Developer Tools**: Git, Docker, AWS, Azure, VS Code, IntelliJ
- **Concepts**: OOP, System Design, REST API

### Achievements
- Participant in Vercel Hackathon, DeepTech Event, WEB3 Event
- Published articles on Medium focusing on AI and Technology

## 📄 License
This project is licensed under the MIT License.

## 🙏 Acknowledgments
- **GSAP Team**: For the incredible animation library
- **Vercel**: For seamless deployment and hosting
- **Prashant Koirala**: For the original portfolio template
- **Open Source Community**: All the amazing tools and libraries used

---

⭐ **If this portfolio inspires you, please give it a star on GitHub!**

Built with ❤️ by Tanish Bhandari
