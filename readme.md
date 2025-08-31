# Jawad Yaics - Personal Portfolio Website

A clean, modern, and mobile-optimized personal portfolio website for Jawad Yaics, a Computer Science student at FAST University.

## 🌟 Features

- **Multi-page Layout**: Separate HTML files for each section
- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices
- **Modern UI/UX**: Inspired by Ali Abdaal's website aesthetics
- **Interactive Elements**: Smooth animations, hover effects, and transitions
- **SEO Optimized**: Proper meta tags, semantic HTML, and structured data
- **Fast Loading**: Optimized CSS and JavaScript for performance
- **Accessibility**: WCAG compliant with proper contrast ratios and keyboard navigation

## 📁 Project Structure

```
jawad-yaics-portfolio-static/
├── index.html              # Homepage
├── learn-log.html          # Learn Log page (assignments & notes)
├── milestones.html         # Milestones page (certifications)
├── portfolio.html          # Portfolio page (projects)
├── contact.html            # Contact page
├── css/
│   └── style.css          # Main stylesheet
├── js/
│   └── main.js            # JavaScript functionality
├── images/                # Image assets (placeholder folder)
├── fonts/                 # Font files (placeholder folder)
├── favicon.ico            # Website favicon
└── README.md              # This file
```

## 🚀 Deployment Instructions

### GitHub Pages Deployment

1. **Create a new repository** on GitHub (e.g., `jawadyaics.github.io`)

2. **Upload all files** to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Jawad Yaics Portfolio"
   git branch -M main
   git remote add origin https://github.com/jawadyaics/jawadyaics.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Access your website** at: `https://jawadyaics.github.io`

### Alternative Deployment Options

#### Netlify
1. Drag and drop the entire folder to [Netlify Drop](https://app.netlify.com/drop)
2. Your site will be live instantly with a random URL
3. Optionally, connect to GitHub for automatic deployments

#### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the project directory
3. Follow the prompts to deploy

#### Traditional Web Hosting
1. Upload all files to your web hosting provider's public_html or www folder
2. Ensure index.html is in the root directory
3. Your site will be accessible via your domain

## 🎨 Customization

### Colors
The website uses a carefully chosen color palette defined in CSS variables:
- Background: `#F8F8F8` (off-white)
- Primary Blue: `#2980B9`
- Rich Beige/Gold: `#D4AC0D`
- Deep Blue: `#1A5276`
- Highlight Blue: `#85C1E9`
- Golden Highlight: `#F7DC6F`
- Neutral Beige: `#F5E6C8`

### Typography
- **Body Text**: Montserrat Light 300 Italic
- **Headings**: Playfair Display 600

### Adding Content

#### Learn Log Resources
Edit `learn-log.html` and add new resource cards in the `#resourcesGrid` section.

#### Milestones/Certifications
Edit `milestones.html` and add new certification cards in the `#certificationsGrid` section.

#### Portfolio Projects
Edit `portfolio.html` and add new project cards in the `#projectsGrid` section.

#### Contact Information
Update contact details in `contact.html` and the footer sections across all pages.

## 📱 Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Technical Details

### CSS Features
- CSS Grid and Flexbox for layouts
- CSS Custom Properties (variables) for theming
- CSS animations and transitions
- Mobile-first responsive design
- Print styles included

### JavaScript Features
- Vanilla JavaScript (no frameworks)
- Mobile menu toggle
- Smooth scrolling
- Intersection Observer for animations
- Form handling and validation
- Search and filter functionality

### Performance Optimizations
- Minified CSS and JavaScript
- Optimized images
- Lazy loading for images
- Debounced scroll events
- Efficient CSS selectors

## 📧 Contact

- **Email**: jawad.yaics@gmail.com
- **GitHub**: [@jawadyaics](https://github.com/jawadyaics)
- **LinkedIn**: [Muhammad Jawad](https://www.linkedin.com/in/muhammad-jawad-86616a27b/)
- **Instagram**: [@jawad.yaics](https://www.instagram.com/jawad.yaics)
- **YouTube**: [@Jawad_yaics](https://www.youtube.com/@Jawad_yaics)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Design inspiration from [Ali Abdaal](https://aliabdaal.com)
- Icons by [Lucide](https://lucide.dev)
- Fonts by [Google Fonts](https://fonts.google.com)

---

**Built with ❤️ by Jawad Yaics**

