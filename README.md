# RAIdev Portfolio

A modern, responsive portfolio website for Raid Anis Kerkatou - PhD researcher in Quantum AI and Cybersecurity.

## Features

🚀 **Modern Design**
- Dark theme with neon accents (cyan, purple, pink)
- Responsive grid layouts
- Smooth animations and transitions
- Mobile-first approach

💡 **Sections**
- Home - Hero section with CTA buttons
- About - Biography with skill tags
- Research - Card-based research areas
- Portfolio - Project showcase with descriptions
- Blog - Article listings with dates
- Teaching - Course offerings
- CV - Experience, education, and publications
- Contact - Contact form and social links

⚡ **Technologies**
- Pure HTML5 (no frameworks)
- CSS3 (Grid, Flexbox, animations)
- Vanilla JavaScript (no dependencies)
- Fully static - no backend needed
- Font Awesome icons
- Google Fonts (Orbitron, Poppins, Inter)

📱 **Responsive**
- Mobile-first design
- Hamburger menu on tablets/phones
- Touch-friendly interactions
- Optimized for all screen sizes

## Quick Start

### Local Development

1. Clone the repository
```bash
git clone https://github.com/raidanis/raidev-portfolio.git
cd raidev-portfolio
```

2. Open in browser
```bash
# Option 1: Direct file open
open index.html

# Option 2: Python simple server
python -m http.server 8000

# Option 3: Node.js http-server
npx http-server
```

3. Visit `http://localhost:8000` (or your port)

### File Structure

```
raidev-portfolio/
├── index.html           # Main HTML file with all sections
├── css/
│   └── style.css        # All styling (1500+ lines)
├── js/
│   └── main.js          # All interactivity
├── images/              # Project images
├── README.md            # This file
└── .gitignore           # Git ignore rules
```

## Customization

### Update Personal Information

Edit `index.html`:
- Change "Raid Anis Kerkatou" to your name (appears in hero + title)
- Update email: `contact@raidanis.com`
- Modify location in contact section
- Update social media links in footer

### Modify Colors

Edit `css/style.css` (lines 9-16):
```css
--primary-dark: #0a0e27;      /* Main background */
--accent-cyan: #00d4ff;       /* Primary accent */
--accent-purple: #8a2be2;     /* Secondary accent */
--accent-pink: #ff006e;       /* Tertiary accent */
--accent-green: #00ff88;      /* Teaching accent */
```

### Add Projects

In `portfolio` section of `index.html`:
```html
<div class="portfolio-item">
    <div class="portfolio-image">
        <img src="images/your-project.jpg" alt="Project Name">
    </div>
    <div class="portfolio-info">
        <h3>Project Title</h3>
        <p>Description</p>
        <div class="portfolio-tags">
            <span>Technology</span>
        </div>
        <a href="#" class="btn btn-small">View Project</a>
    </div>
</div>
```

### Update Blog Posts

In `blog` section of `index.html`:
```html
<article class="blog-card">
    <div class="blog-date">Jan 1, 2024</div>
    <h3>Your Article Title</h3>
    <p>Article summary...</p>
    <a href="#" class="read-more">Read Article →</a>
</article>
```

## Deployment

### GitHub Pages (Free)

1. Create repository on GitHub
2. Push code to `main` branch
3. Enable GitHub Pages in Settings → Pages
4. Set source to `main` branch
5. Site will be live at `https://username.github.io/raidev-portfolio/`

### Netlify (Recommended)

1. Connect GitHub to Netlify
2. Select repository
3. Build settings: Leave blank (no build step needed)
4. Deploy - it's instant!

### Railway

1. Connect GitHub to Railway
2. Create new project from repo
3. Set start command: `python -m http.server 8000`
4. Auto-deploys on push

### Traditional Hosting

Upload via FTP:
1. `index.html`
2. `css/` directory
3. `js/` directory
4. `images/` directory

## Performance

- **No build step** - Changes visible instantly
- **No dependencies** - Pure HTML/CSS/JS
- **Optimized** - Minimal file sizes
- **Fast loading** - ~100KB total (uncompressed)
- **SEO friendly** - Semantic HTML
- **Accessibility** - WCAG compliant

## Features Detail

### Smooth Scrolling
- Click any navigation link
- Smooth scroll to section
- Active link highlighting

### Mobile Menu
- Hamburger menu for tablets/phones
- Click outside to close
- Responsive breakpoints at 768px and 480px

### Scroll Animation
- Cards fade in as you scroll
- Parallax background effects
- Glitch text animation on hero

### Interactive Elements
- Hover effects on cards
- Button animations
- Form validation
- Scroll-to-top button

### Accessibility
- Semantic HTML structure
- ARIA labels
- Keyboard navigation (Esc to close menu)
- High contrast colors
- Mobile-friendly tap targets

## Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

## Contributing

Feel free to fork, modify, and use as template for your own portfolio!

## License

This portfolio template is open source and available under the MIT License.

## Contact

**Raid Anis Kerkatou**
- Email: contact@raidanis.com
- Website (this repo deployed)
- GitHub: @raidanis

## Changelog

### v1.0.0 (Initial Release)
- Complete portfolio website
- 8 main sections
- Responsive design
- Mobile menu
- Contact form
- Blog section
- CV section
- Smooth animations
- Dark theme with neon accents

---

Built with ❤️ using pure HTML, CSS, and JavaScript.
