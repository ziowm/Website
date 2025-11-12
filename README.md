# Portfolio Website - Moiz Uddin

A modern, responsive portfolio website showcasing my software engineering projects, experience, and skills. Built with HTML, CSS, JavaScript, and Tailwind CSS.

## Features

- **Stunning Hero Section** with animated gradient background and particle effects
- **Dark/Light Mode Toggle** with persistent theme preference
- **Typing Animation** showcasing multiple roles and specializations
- **Interactive Project Cards** with 3D hover effects
- **Animated Skill Bars** with smooth progression animations
- **Experience Timeline** with clean, professional layout
- **Responsive Design** optimized for all devices (mobile, tablet, desktop)
- **Smooth Scrolling** and parallax effects throughout
- **Contact Form** with email integration
- **Performance Optimized** with lazy loading and efficient animations
- **Accessibility Features** including keyboard navigation
- **Easter Egg** - Try the Konami code! (⬆️⬆️⬇️⬇️⬅️➡️⬅️➡️BA)

## Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom animations and styles
- **JavaScript (ES6+)** - Interactive features and animations
- **Tailwind CSS** - Utility-first CSS framework
- **Font Awesome** - Icon library
- **Google Fonts** - Inter & Fira Code fonts

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional but recommended)

### Installation

1. Clone or download this repository:
```bash
git clone https://github.com/ziowm/portfolio.git
cd portfolio
```

2. Open the website:

**Option 1: Direct File Opening**
```bash
open index.html
```

**Option 2: Using Python's Built-in Server (Recommended)**
```bash
# Python 3
python3 -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```
Then visit `http://localhost:8000` in your browser.

**Option 3: Using Node.js http-server**
```bash
npm install -g http-server
http-server -p 8000
```
Then visit `http://localhost:8000` in your browser.

**Option 4: Using VS Code Live Server**
- Install the "Live Server" extension
- Right-click on `index.html`
- Select "Open with Live Server"

## Project Structure

```
portfolio/
├── index.html              # Main HTML file
├── styles.css              # Custom CSS styles and animations
├── script.js               # JavaScript for interactivity
├── README.md               # Project documentation
└── Moiz_Uddin__SWE_Resume.pdf  # Resume PDF (downloadable)
```

## Customization

### Updating Content

1. **Personal Information**: Edit the hero section in `index.html` (lines 90-150)
2. **Experience**: Update the experience section (lines 300-400)
3. **Projects**: Modify project cards (lines 450-550)
4. **Skills**: Edit skill bars and technologies (lines 600-750)
5. **Contact Info**: Update email and social links throughout

### Changing Colors

The color scheme uses Tailwind CSS utilities and can be customized in the `tailwind.config` section of `index.html` (lines 19-45).

Primary colors:
- Blue: `#3b82f6`
- Purple: `#8b5cf6`
- Pink: `#ec4899`

### Modifying Animations

1. **Typing Animation**: Edit phrases in `script.js` (lines 60-67)
2. **Particles**: Adjust particle count and behavior (lines 80-150)
3. **Skill Bars**: Modify percentages in `index.html` skill section

## Features Breakdown

### Dark Mode
- Toggle between light and dark themes
- Preference saved in localStorage
- Smooth transitions between themes

### Animations
- Typing effect for role descriptions
- Particle system with connecting lines
- Scroll-triggered reveal animations
- Skill bar progression on scroll
- 3D hover effects on project cards
- Smooth parallax scrolling

### Interactive Elements
- Mobile-responsive navigation menu
- Active navigation highlighting on scroll
- Scroll-to-top button
- Contact form with mailto integration
- Hover effects on all interactive elements

### Performance Optimizations
- Intersection Observer for efficient scroll animations
- Debounced scroll events
- CSS-based animations where possible
- Optimized particle rendering

## Browser Support

- Chrome (recommended) - Latest
- Firefox - Latest
- Safari - Latest
- Edge - Latest
- Mobile browsers (iOS Safari, Chrome Mobile)

## Deployment

### GitHub Pages

1. Create a new repository on GitHub
2. Push your code:
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/ziowm/portfolio.git
git push -u origin main
```
3. Go to repository Settings > Pages
4. Select "main" branch and "/ (root)" folder
5. Click Save
6. Your site will be live at `https://ziowm.github.io/portfolio/`

### Netlify

1. Install Netlify CLI:
```bash
npm install -g netlify-cli
```

2. Deploy:
```bash
netlify deploy --prod
```

### Vercel

1. Install Vercel CLI:
```bash
npm install -g vercel
```

2. Deploy:
```bash
vercel --prod
```

## Performance Tips

1. **Images**: Compress images before adding them
2. **Fonts**: Use font subsetting for faster loading
3. **CDNs**: All external resources loaded via CDN
4. **Caching**: Enable browser caching for static assets
5. **Minification**: Minify CSS and JS for production

## Accessibility

- Semantic HTML5 elements
- ARIA labels where appropriate
- Keyboard navigation support
- High contrast mode compatible
- Screen reader friendly
- Focus indicators on interactive elements

## SEO Optimization

- Meta tags for description and social sharing
- Semantic HTML structure
- Fast loading times
- Mobile-responsive design
- Clean URL structure

## Known Issues

None at this time. If you find any bugs, please report them!

## Future Enhancements

- [ ] Add blog section
- [ ] Integrate with CMS for easy content updates
- [ ] Add more project details with case studies
- [ ] Implement contact form backend
- [ ] Add testimonials section
- [ ] Create multilingual support
- [ ] Add analytics integration

## Credits

- **Design & Development**: Moiz Uddin
- **Icons**: [Font Awesome](https://fontawesome.com/)
- **Fonts**: [Google Fonts](https://fonts.google.com/)
- **CSS Framework**: [Tailwind CSS](https://tailwindcss.com/)

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

- **Email**: uddin.moiz@gmail.com
- **LinkedIn**: [linkedin.com/in/ziowm](https://linkedin.com/in/ziowm)
- **GitHub**: [github.com/ziowm](https://github.com/ziowm)
- **Phone**: 240-550-5353

---

Built with ❤️ by Moiz Uddin
