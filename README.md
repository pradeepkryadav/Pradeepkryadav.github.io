# Pradeep Kumar - Personal Portfolio Website

A modern, responsive personal portfolio website showcasing professional experience, publications, awards, and press coverage.

## 🌟 Features

- **Modern Design**: Clean, minimalist design inspired by contemporary web standards
- **Dark/Light Mode**: Toggle between themes with persistent preference storage
- **Fully Responsive**: Optimized for all devices (desktop, tablet, mobile)
- **Smooth Animations**: Intersection Observer API for scroll-based animations
- **Interactive Navigation**: Active link highlighting and smooth scrolling
- **Performance Optimized**: Debounced scroll handlers and efficient rendering
- **Accessible**: Semantic HTML and ARIA labels for better accessibility

## 📂 Structure

```
PersonalWebsite/
├── index.html          # Main HTML file with all sections
├── styles.css          # Comprehensive CSS with light/dark themes
├── script.js           # JavaScript for interactivity
├── README.md           # This file
├── SGC/                # Source content directory (not deployed)
└── src/                # Additional source files
```

## 🚀 Sections

1. **Home/Hero**: Introduction with call-to-action buttons
2. **About**: Professional summary with key statistics
3. **Experience**: Timeline of career achievements
4. **Publications**: Research papers and contributions
5. **Awards**: Recognition and achievements
6. **Press**: Media features and articles
7. **Contact**: Contact information and form

## 🎨 Customization

### Update Personal Information

Edit `index.html` to update:
- Name and title in the hero section
- Professional experience details
- Contact information (email, LinkedIn, GitHub)
- Social media links

### Update Content

To add your specific information from the SGC directory:
1. Publications: Update publication cards with actual paper titles and links
2. Awards: Add certificate images or links
3. Press: Add actual article URLs
4. Experience: Expand timeline with more positions

### Color Scheme

Modify color variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;    /* Main brand color */
    --secondary-color: #1e40af;  /* Secondary brand color */
    --accent-color: #3b82f6;     /* Accent color */
}
```

### Add Profile Photo

Replace the hero image placeholder:
1. Add your photo to the project directory
2. Update the `.hero-image-placeholder` in `index.html`:
```html
<div class="hero-image-wrapper">
    <img src="your-photo.jpg" alt="Pradeep Kumar" />
</div>
```

## 🔧 Setup & Deployment

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/pradeepkryadav/Pradeepkryadav.github.io.git
cd Pradeepkryadav.github.io
```

2. Open `index.html` in your browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server
```

3. Visit `http://localhost:8000` in your browser

### Deploy to GitHub Pages

1. Commit all files:
```bash
git add index.html styles.css script.js README.md
git commit -m "Initial commit: Personal portfolio website"
```

2. Push to GitHub:
```bash
git push origin main
```

3. Enable GitHub Pages:
   - Go to repository Settings > Pages
   - Select "main" branch as source
   - Save

Your site will be live at: `https://pradeepkryadav.github.io/`

## 📧 Contact Form Integration

The contact form currently shows an alert. To enable real email submission, integrate with:

- **Formspree**: https://formspree.io/ (Easiest)
- **EmailJS**: https://www.emailjs.com/
- **Netlify Forms**: If deploying on Netlify
- **Custom Backend**: Build your own API endpoint

### Example Formspree Integration:

```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
    <!-- form fields -->
</form>
```

## 🎯 Next Steps

1. **Add actual content** from SGC directory:
   - Extract information from resume PDF
   - Add publication links and PDFs
   - Upload award certificates
   - Link to press articles

2. **Add images**:
   - Professional headshot
   - Award certificates
   - Project screenshots

3. **Optimize for SEO**:
   - Add meta tags
   - Create sitemap.xml
   - Add robots.txt
   - Implement structured data

4. **Analytics**:
   - Add Google Analytics
   - Monitor visitor behavior
   - Track contact form submissions

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom properties, Grid, Flexbox, animations
- **JavaScript**: Vanilla JS for all interactivity
- **Font Awesome**: Icons
- **Google Fonts**: Inter & JetBrains Mono

## 📄 License

© 2026 Pradeep Kumar. All rights reserved.

## 🤝 Contributing

This is a personal portfolio website. If you have suggestions, feel free to open an issue.

---

**Built with ❤️ by Pradeep Kumar**