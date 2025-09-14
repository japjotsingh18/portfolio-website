# 🌐 Japjot Singh - Portfolio Website

A modern, tech-themed personal portfolio website featuring a futuristic design with dark mode, glowing neon accents, and smooth animations.

## ✨ Features

### 🎨 Design
- **Dark Futuristic Theme**: Deep black backgrounds with neon cyan and green accents
- **Glowing Effects**: Neon text shadows and glowing borders throughout
- **Smooth Animations**: Hover effects, fade-ins, typewriter text, and card flips
- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices
- **Interactive Elements**: Animated particles, matrix-style background, and cursor trails

### 🔧 Sections
1. **Hero Section**: Animated name with typewriter effect, subtitle, and call-to-action buttons
2. **About Me**: Brief bio with animated statistics cards
3. **Skills**: Interactive glowing skill badges organized by categories
4. **Projects**: Animated project cards with hover effects and tech tags
5. **Experience**: Scroll-based timeline with alternating animations
6. **Certifications**: Interactive certificate cards with rotating border effects
7. **Contact**: Contact form with glowing input fields and contact information
8. **Footer**: Social links with hover animations

### 🚀 Interactive Features
- **Loading Screen**: Animated logo and progress bar
- **Smooth Scrolling**: Navigation with active link highlighting
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Form Handling**: Contact form with validation and feedback
- **Notifications**: Success/error messages with slide animations
- **Resume Download**: Downloadable resume functionality
- **Easter Egg**: Konami code activation with special effects
- **Cursor Trail**: Animated dots following mouse movement
- **Matrix Background**: Animated digital rain effect

## 📁 Project Structure

```
portfolio_website/
├── index.html          # Main HTML file
├── styles.css          # Complete CSS with animations and responsive design
├── script.js           # JavaScript for interactivity and animations
└── README.md           # Project documentation
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and accessibility features
- **CSS3**: Advanced animations, transitions, and responsive design
- **JavaScript ES6+**: Modern JavaScript with DOM manipulation and animations
- **Font Awesome**: Icons for social links and buttons
- **Google Fonts**: Poppins, Orbitron, and Montserrat font families

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A code editor (VS Code, Sublime Text, etc.)
- Optional: Live Server extension for development

### Installation

1. **Clone or Download**: Get the project files to your local machine
2. **Open in Browser**: Double-click `index.html` or use a live server
3. **Customize**: Edit the content to match your information

### Development Setup

1. **Open in VS Code**:
   ```bash
   cd portfolio_website
   code .
   ```

2. **Install Live Server Extension** (Optional):
   - Go to Extensions in VS Code
   - Search for "Live Server"
   - Install and reload VS Code

3. **Start Development Server**:
   - Right-click on `index.html`
   - Select "Open with Live Server"
   - Your browser will open with live reload enabled

## 🎯 Customization Guide

### Personal Information
Edit the following sections in `index.html`:

1. **Hero Section**:
   - Change name in `.hero-name`
   - Update subtitle and tagline
   - Modify button links

2. **About Section**:
   - Replace bio text with your information
   - Update GPA and statistics

3. **Skills Section**:
   - Add/remove skill badges
   - Update categories as needed
   - Modify icons (Font Awesome classes)

4. **Projects Section**:
   - Replace project information
   - Update GitHub/demo links
   - Modify tech tags

5. **Experience Section**:
   - Update timeline items with your experience
   - Modify dates and descriptions

6. **Certifications Section**:
   - Add your certifications
   - Update certificate links
   - Modify completion dates

7. **Contact Section**:
   - Update email and phone number
   - Add your LinkedIn URL
   - Modify social media links

### Color Scheme
Modify CSS custom properties in `styles.css`:

```css
:root {
    --accent-cyan: #00ffff;      /* Primary neon color */
    --accent-green: #00ff88;     /* Secondary neon color */
    --accent-purple: #8b5cf6;    /* Tertiary accent */
    --bg-primary: #0a0a0a;       /* Main background */
    --bg-secondary: #111111;     /* Card backgrounds */
    --text-primary: #ffffff;     /* Main text color */
}
```

### Fonts
Update font imports in `index.html` head section:
```html
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@weights&display=swap" rel="stylesheet">
```

### Resume Download
Update the `downloadResume()` function in `script.js`:
- Replace with actual PDF file path
- Modify resume content
- Update filename

### Contact Form
To make the contact form functional:
1. Add form handling backend (PHP, Node.js, etc.)
2. Update form action and method
3. Modify the submit handler in `script.js`

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🎨 Animation Details

### CSS Animations
- **Typewriter Effect**: Blinking cursor animation
- **Particle Float**: Floating background particles
- **Matrix Rain**: Digital rain background effect
- **Glow Effects**: Pulsing neon glows
- **Hover Transforms**: Scale and translate effects

### JavaScript Animations
- **Scroll Animations**: Intersection Observer API
- **Typewriter Text**: Character-by-character typing
- **Stats Counter**: Animated number counting
- **Smooth Scrolling**: Enhanced navigation
- **Loading Screen**: Progress bar and fade effects

## 🔧 Performance Optimizations

- **Lazy Loading**: Images and animations load when needed
- **CSS Animations**: Hardware-accelerated transforms
- **Intersection Observer**: Efficient scroll-based animations
- **Debounced Events**: Optimized scroll and resize handlers
- **Page Visibility API**: Pause animations when tab is hidden

## 🎮 Easter Eggs

- **Konami Code**: Enter the classic cheat code (↑↑↓↓←→←→BA) for a surprise
- **Cursor Trail**: Interactive mouse trail effect
- **Matrix Rain**: Hidden digital rain animation
- **Loading Screen**: Animated portfolio initialization

## 🚀 Deployment Options

### GitHub Pages
1. Create a GitHub repository
2. Upload all files
3. Enable GitHub Pages in repository settings
4. Access via `https://yourusername.github.io/repository-name`

### Netlify
1. Create account at netlify.com
2. Drag and drop project folder
3. Get instant deployment with custom domain options

### Vercel
1. Create account at vercel.com
2. Connect GitHub repository
3. Automatic deployments on code changes

## 📧 Contact & Support

For questions or customization help:
- **Email**: jsing138@asu.edu
- **Phone**: +1 (623) 273 6288

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Font Awesome** for icons
- **Google Fonts** for typography
- **CSS-Tricks** for animation inspiration
- **MDN Web Docs** for technical reference

---

**Built with 💻 and creativity by Japjot Singh**
