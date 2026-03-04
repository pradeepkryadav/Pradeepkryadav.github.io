# Pradeep Kumar - Personal Portfolio Website

A modern, responsive personal portfolio website showcasing professional experience, publications, awards, press coverage, and community service.

🌐 **Live Site**: [https://pradeepkryadav.github.io/](https://pradeepkryadav.github.io/)

## 🌟 Features

### Core Features
- **Modern Design**: Clean, minimalist design inspired by dharminthakkar.com
- **Dark/Light Mode**: Toggle between themes with persistent preference storage
- **Fully Responsive**: Optimized for all devices (desktop, tablet, mobile)
- **Smooth Animations**: Intersection Observer API for scroll-based animations
- **Interactive Navigation**: Active link highlighting and smooth scrolling
- **Performance Optimized**: Debounced scroll handlers and efficient rendering
- **Accessible**: Semantic HTML and ARIA labels for better accessibility

### Advanced Features
- **Expandable Experience**: Shows SAP by default with "Show All Experience" button to reveal 5 additional companies
- **Professional Profile Photo**: Integrated circular profile photo with fallback icon
- **Social Sharing**: Share publications and awards on LinkedIn, Twitter, Facebook, or copy links
- **Search & Filter**: Real-time search and category filtering on publications page
- **Dedicated Pages**: Separate pages for complete publications and awards listings
- **Social Work Gallery**: Community service activities with photos and icons
- **Real Links**: All publications, awards, and press articles have actual working URLs

## 📂 Project Structure

```
PersonalWebsite/
├── index.html                    # Main homepage with all sections
├── all-publications.html         # Dedicated page for all 20 publications
├── all-awards.html              # Dedicated page for all awards
├── styles.css                   # Comprehensive CSS with light/dark themes
├── script.js                    # JavaScript for all interactivity
├── README.md                    # Project documentation
├── IMAGES_SETUP.md              # Image setup instructions
├── assets/
│   └── images/
│       ├── profile/
│       │   └── Pradeep_Profile.jpg       # Professional headshot (219KB)
│       ├── awards/
│       │   └── Globee_Awards_2025.png    # Award certificate (305KB)
│       └── social-work/
│           ├── Special_Olympic_4thJuly2025.jpg  # Volunteer photo (777KB)
│           └── loudoun_hunger_relief.jpg        # Volunteer photo (980KB)
└── SGC/                         # Source content directory (not deployed)
```

## 🚀 Website Sections

### Main Page (index.html)

1. **Home/Hero**: Professional introduction with profile photo, title, and call-to-action buttons
2. **About**: Professional summary with key statistics (30+ papers, 5+ awards, 8 years experience, 4 volunteer activities)
3. **Experience**: Complete career timeline with 6 companies
   - **SAP** (Performance Architect) - Shown by default
   - 5 additional companies revealed via "Show All Experience" button:
     - Accenture Solutions Pvt Ltd
     - Cognizant Technology Solutions
     - Infosys BPO Ltd
     - Bebo Technologies Pvt Ltd
     - Cyber Gear
4. **Expertise**: Core competencies in performance engineering, cloud computing, and AI/ML
5. **Publications**: Preview of 12 featured research papers with links to dedicated page
6. **Awards**: International and SAP awards with certificate images
7. **Membership**: Professional affiliations (IEEE, ACM, ORCID, OpenReview)
8. **Social Work & Community Service**: 4 volunteer activities
   - Special Olympics Coach (Virginia) - with photo
   - CodePath.org Technical Interview Prep Mentor (USA) - icon only
   - The Mission Continues (Washington DC, USA) - icon only
   - Loudoun Hunger Relief Volunteer (Loudoun County, VA) - with photo
9. **Press**: 5 featured articles with actual links
10. **Contact**: Contact form and social media links

### Dedicated Pages

#### all-publications.html
- **20 Complete Publications** with full details:
  - Titles, journals, publication years, DOIs
  - Full abstracts (300-400 words each)
  - Tags for categorization (Performance, Cloud, JVM, AI/ML, etc.)
  - Direct links to papers
  - Social sharing buttons
- **Search Functionality**: Real-time search across titles, abstracts, and tags
- **Category Filters**: All (20), Performance (10), Cloud (6), JVM (5), AI/ML (4)
- **Publication Actions**: Read paper and share buttons for each entry

#### all-awards.html
- **International Awards** with full details and certificate images:
  - TITAN Business Awards (Gold Winner) - Certificate placeholder
  - Globee Awards 2025 (Silver Winner) - Actual certificate image
  - ISSN Innovation Awards (Innovation Excellence) - Certificate placeholder
- **SAP Internal Awards**: Grid of 7 awards including SAP CTO Circle of Excellence
- **Social Sharing**: Share buttons for each award
- **Certificate Display**: Full-size certificate images with award details

## 📊 Content Summary

### Publications (20 Total)
All publications include real URLs to papers on platforms like:
- Zenodo
- ResearchGate
- ACM Digital Library
- IEEE Xplore
- MDPI
- HAL Science
- SSRN

**Topics covered:**
- JVM Performance Optimization (5 papers)
- Cloud Computing & Migration (6 papers)
- Performance Engineering (10 papers)
- AI/ML Applications (4 papers)

### Awards (10 Total)
- 3 International Awards with certificates
- 7 SAP Internal Awards

### Press Coverage (5 Articles)
- Sourced from Business Insider, AnalyticsInsight, LatestLY, ABP Live, NewsVoir
- All articles include actual working links

### Professional Experience (6 Companies)
- SAP (2016-Present): Performance Architect
- Accenture Solutions Pvt Ltd (2015-2016)
- Cognizant Technology Solutions (2014-2015)
- Infosys BPO Ltd (2013-2014)
- Bebo Technologies Pvt Ltd (2012-2013)
- Cyber Gear (2011-2012)

### Images & Media
- ✅ Professional profile photo (Pradeep_Profile.jpg)
- ✅ 1 Award certificate (Globee Awards 2025)
- ✅ 2 Social work photos (Special Olympics, Loudoun Hunger Relief)
- 📋 2 Award certificate placeholders (ready for addition)

## 🎨 Customization

### Color Scheme

Modify color variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;    /* Main brand color */
    --secondary-color: #1e40af;  /* Secondary brand color */
    --accent-color: #3b82f6;     /* Accent color */
}
```

### Adding More Images

Follow the instructions in `IMAGES_SETUP.md` to add:
- Additional award certificates (TITAN, ISSN)
- Project screenshots
- More community service photos

Current image requirements:
- **Format**: JPG or PNG (JPG preferred for photos)
- **Size**: Keep under 500KB for fast loading
- **Profile photos**: 800x800px ideal
- **Certificates**: High resolution for readability
- **Social work photos**: 500x500px minimum for circular display

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

### GitHub Pages Deployment

✅ **Already Deployed and Live**

The website is currently live at: **https://pradeepkryadav.github.io/**

To update the live site:
```bash
# Make your changes to the files
git add .
git commit -m "Your descriptive commit message"
git push origin main
```

Changes will be reflected on the live site within 1-2 minutes.

## 📧 Contact Form Integration

The contact form currently shows an alert for demo purposes. To enable real email submission, integrate with:

- **Formspree**: https://formspree.io/ (Recommended - Easiest)
- **EmailJS**: https://www.emailjs.com/
- **Netlify Forms**: If deploying on Netlify
- **Custom Backend**: Build your own API endpoint

### Example Formspree Integration:

```html
<form id="contactForm" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
    <input type="text" name="name" id="name" required>
    <input type="email" name="email" id="email" required>
    <textarea name="message" id="message" required></textarea>
    <button type="submit" class="btn btn-primary">Send Message</button>
</form>
```

Then remove the preventDefault() JavaScript in script.js to allow natural form submission.

## 🎯 Implementation Status

### ✅ Completed Features

- [x] Modern responsive design with light/dark theme toggle
- [x] Complete homepage with 10 sections
- [x] Professional profile photo integrated
- [x] Full career experience (6 companies) with expandable view
- [x] 20 research publications with real links and full abstracts
- [x] Dedicated publications page with search and filter
- [x] 10 awards with certificate images
- [x] Dedicated awards page with social sharing
- [x] 5 press articles with actual URLs
- [x] Professional memberships section (IEEE, ACM, ORCID, OpenReview)
- [x] Social work section with 4 volunteer activities
- [x] Community service photos (2 activities with images)
- [x] Social sharing functionality (LinkedIn, Twitter, Facebook, Copy)
- [x] Mobile-responsive navigation with hamburger menu
- [x] Smooth scrolling and active nav highlighting
- [x] Intersection Observer animations
- [x] Performance optimizations (debounced scroll handlers)
- [x] Git repository initialized and synced with GitHub
- [x] Deployed to GitHub Pages (live site)

### 📋 Optional Future Enhancements

1. **SEO Optimization**:
   - Add comprehensive meta tags for social media
   - Create sitemap.xml
   - Add robots.txt
   - Implement structured data (JSON-LD)

2. **Additional Images**:
   - Add remaining award certificates (TITAN, ISSN)
   - Add project/work screenshots if desired

3. **Analytics**:
   - Add Google Analytics or privacy-focused alternative
   - Monitor visitor behavior
   - Track contact form submissions

4. **Contact Form**:
   - Integrate with Formspree or EmailJS for real submissions
   - Add form validation feedback
   - Implement success/error messages

5. **Performance**:
   - Add lazy loading for images
   - Implement service worker for offline support
   - Consider WebP format for images

6. **Accessibility**:
   - Add skip-to-content link
   - Enhance keyboard navigation
   - Run full WCAG audit

## 🛠️ Technologies Used

- **HTML5**: Semantic markup with modern structure
- **CSS3**: Custom properties, CSS Grid, Flexbox, animations, transitions
- **JavaScript (Vanilla)**: No frameworks - pure ES6+ JavaScript for all interactivity
- **Font Awesome 6.4.0**: Icons throughout the site
- **Google Fonts**: Inter (body text) & JetBrains Mono (code/technical elements)
- **Intersection Observer API**: Scroll-based animations
- **Local Storage API**: Theme persistence
- **Web Share API**: Native sharing on mobile devices
- **Git & GitHub**: Version control and hosting
- **GitHub Pages**: Free static site hosting

### Key JavaScript Features Implemented

1. **Theme Toggle**: Dark/light mode with localStorage persistence
2. **Mobile Menu**: Hamburger menu with smooth transitions
3. **Navbar Scroll Effects**: Shows/hides based on scroll position
4. **Active Nav Highlighting**: Automatically highlights current section
5. **Smooth Scrolling**: Native smooth scroll with offset for fixed navbar
6. **Experience Toggle**: Shows/hides additional career history
7. **Intersection Observer**: Fade-in animations for cards and sections
8. **Contact Form Handler**: Validates and handles form submission
9. **Scroll to Top Button**: Optional enhancement (code included)
10. **Performance Optimization**: Debounced scroll handlers
11. **Search Functionality**: Real-time publication search
12. **Filter System**: Category-based publication filtering
13. **Social Sharing**: Multi-platform share functionality with fallbacks

## 📱 Browser Support

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)
- ⚠️ Internet Explorer: Not supported (uses modern CSS features)

## 📊 Performance Metrics

- **Lightweight**: No heavy frameworks or libraries
- **Fast Load**: Optimized CSS and JavaScript
- **Responsive Images**: Properly sized and compressed
- **Debounced Events**: Efficient scroll handling
- **Lazy Animations**: Only animates elements in viewport

## 🔒 Privacy & Security

- No tracking or analytics (privacy-first approach)
- No cookies (except localStorage for theme preference)
- All external links open in new tabs
- Contact form data not stored (currently demo mode)
- All images hosted locally (no CDN dependencies for personal photos)

## 📄 License

© 2026 Pradeep Kumar. All rights reserved.

## 🤝 Support & Issues

For questions or issues with the website:
- Check `IMAGES_SETUP.md` for image-related help
- Review `script.js` comments for JavaScript functionality
- Inspect browser console for any errors

## 📈 Website Statistics

- **Total Pages**: 3 (index.html, all-publications.html, all-awards.html)
- **Total Sections**: 10 on main page
- **Publications Showcased**: 20 with full details
- **Awards Listed**: 10 (3 international, 7 SAP internal)
- **Press Articles**: 5 with actual links
- **Companies Featured**: 6 career positions
- **Volunteer Activities**: 4 community service roles
- **Images**: 4 total (1 profile, 1 certificate, 2 volunteer photos)
- **Lines of Code**: ~350 JavaScript, ~2000 CSS, ~1500 HTML
- **External Dependencies**: 2 (Font Awesome, Google Fonts)

---

**Built with ❤️ by Pradeep Kumar**

*Last Updated: March 2026*