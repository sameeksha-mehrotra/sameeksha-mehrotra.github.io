# Sameeksha Mehrotra - Portfolio Website

A modern, design-focused portfolio website built to showcase AI/ML engineering skills and projects. Designed to impress tech recruiters with stunning visuals and smooth animations.

## Features

- **Stunning Visual Design** - Dark theme with gradient accents and glassmorphism effects
- **Smooth Animations** - Scroll-triggered animations, typing effects, and parallax scrolling
- **Fully Responsive** - Looks great on all devices from mobile to desktop
- **Interactive Elements** - Project filtering, skill bars, cursor glow effects
- **Performance Optimized** - Lazy loading, CSS animations, minimal dependencies
- **SEO Ready** - Meta tags, Open Graph support, semantic HTML
- **Accessible** - Follows WCAG guidelines, respects reduced motion preferences
- **Easter Egg** - Try the Konami code!

## Quick Start

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sameekshamehrotra/sameeksha-website.git
   cd sameeksha-website
   ```

2. **Open locally:**
   Simply open `index.html` in your browser, or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000

   # Using Node.js
   npx serve
   ```

3. **Visit:** `http://localhost:8000`

## Customization

### Personal Information
Edit `index.html` to update:
- Name and title
- About section content
- Projects (update links, descriptions, metrics)
- Work experience
- Publications and awards
- Contact information and social links

### Styling
Modify `styles.css` to customize:
- Colors: Update CSS custom properties in `:root`
- Typography: Change font imports and `--font-primary`
- Spacing: Adjust `--section-padding` and `--container-width`

### Adding Your Photo
Replace the placeholder in the About section:
```html
<!-- Find this in index.html -->
<div class="image-placeholder">...</div>

<!-- Replace with: -->
<img src="assets/your-photo.jpg" alt="Sameeksha Mehrotra" />
```

### Typing Text
Edit the phrases in `script.js`:
```javascript
const phrases = [
    'AI/ML Engineer',
    'Deep Learning Researcher',
    // Add your own titles
];
```

## Deployment

### GitHub Pages (Recommended)

1. **Create GitHub repository:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Portfolio website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
   git push -u origin main
   ```

2. **Enable GitHub Pages:**
   - Go to repository Settings > Pages
   - Source: Deploy from branch
   - Branch: `main` / `root`
   - Save

3. **Your site will be live at:** `https://YOUR_USERNAME.github.io`

### Netlify

1. Drag and drop the folder to [netlify.com/drop](https://netlify.com/drop)
2. Or connect your GitHub repo for continuous deployment

### Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run: `vercel`
3. Follow the prompts

### Custom Domain

Add a `CNAME` file with your domain:
```
www.yourdomain.com
```

## Project Structure

```
sameeksha-website/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # Interactivity & animations
├── README.md           # This file
└── assets/             # Images, resume, etc. (create as needed)
    ├── your-photo.jpg
    ├── resume.pdf
    └── og-image.png
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance Tips

- Compress images before adding to `assets/`
- Use WebP format for photos where supported
- Consider adding a service worker for offline support

## Form Handling

The contact form currently simulates submission. To make it functional:

### Option 1: Formspree
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

### Option 2: Netlify Forms
```html
<form name="contact" netlify>
```

### Option 3: Custom Backend
Update `script.js` to POST to your API endpoint.

## License

MIT License - Feel free to use and modify for your own portfolio!

---

Built with passion by Sameeksha Mehrotra
