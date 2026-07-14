# Portfolio Website - Annisa Putri Sajjida Intansari

A professional portfolio website showcasing IT Governance, IT Asset Management, and Project Management expertise.

## 📋 Table of Contents

- [Features](#features)
- [Sections](#sections)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Customization](#customization)
- [Deployment](#deployment)
- [Contact](#contact)

## ✨ Features

✅ **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
✅ **Modern UI** - Clean, professional, and visually appealing design
✅ **Smooth Navigation** - Smooth scrolling between sections
✅ **Contact Form** - Integrated contact form with email functionality
✅ **Social Links** - Easy access to social media profiles
✅ **Fast Loading** - Static HTML/CSS for optimal performance
✅ **SEO Ready** - Proper HTML structure for search engine optimization
✅ **Animations** - Subtle animations on scroll

## 📑 Sections

1. **Home** - Hero section with introduction and call-to-action buttons
2. **About Me** - Personal introduction and statistics
3. **Skills** - 16 core competencies displayed in card format
4. **Experience** - Professional timeline with achievements
5. **Projects** - Showcase of completed projects
6. **Certifications** - Professional certifications and credentials
7. **Blog** - Articles and insights (template for future posts)
8. **Contact** - Contact information and message form

## 🛠️ Technology Stack

- **HTML5** - Semantic structure
- **CSS3** - Modern styling with CSS variables and Grid/Flexbox
- **JavaScript (Vanilla)** - Interactive features without dependencies
- **Font Awesome** - Icons library

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/nisaputrimyid/portofolio.git
   cd portofolio
   ```

2. **Open in browser:**
   - Option A: Double-click `index.html`
   - Option B: Use a local server
     ```bash
     python -m http.server 8000
     # or
     npx http-server
     ```
   - Then open `http://localhost:8000`

## 🎨 Customization

### Update Personal Information

Edit the following sections in `index.html`:

1. **Hero Section** - Update name, title, and bio
2. **About Section** - Modify the about text and statistics
3. **Skills** - Add/remove/modify skill cards
4. **Experience** - Update your work history
5. **Projects** - Add your project details
6. **Certifications** - List your credentials
7. **Blog** - Add your blog posts
8. **Contact** - Update contact information

### Customize Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;      /* Main brand color */
    --secondary-color: #1e40af;    /* Darker shade */
    --accent-color: #f59e0b;       /* Accent color */
    /* ... more colors ... */
}
```

### Update Links

- Replace placeholder links in social media section
- Update email address in contact section
- Add real links to projects and blog posts
- Update social media URLs

## 🚀 Deployment

### GitHub Pages (Recommended)

1. Push your code to GitHub
2. Go to repository settings
3. Navigate to "Pages" section
4. Select "main" branch as source
5. Your site will be live at `https://nisaputrimyid.github.io/portofolio`

### Other Hosting Options

- **Netlify** - Drag and drop deployment
- **Vercel** - Optimized for web performance
- **Traditional Hosting** - Upload files via FTP

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 File Structure

```
portofolio/
├── index.html      # Main HTML file
├── styles.css      # Styling
├── script.js       # JavaScript functionality
├── README.md       # This file
└── images/         # (Optional) Image folder
```

## 🔧 Features Explanation

### Mobile Menu
The hamburger menu appears on screens smaller than 768px and toggles the navigation menu.

### Contact Form
The contact form uses a mailto link to open the user's email client. For more advanced functionality, consider integrating with services like:
- Formspree
- EmailJS
- Netlify Forms

### Scroll Animations
Cards animate into view as they become visible on the screen, providing a dynamic user experience.

### Active Navigation
The active navigation link highlights as you scroll through different sections.

## 🐛 Troubleshooting

**Contact form not working?**
- Update the email address in `script.js` (line with `annisa@example.com`)
- Consider using a form service for better email handling

**Images not loading?**
- Replace placeholder images with your own
- Update image paths in the HTML

**Styling issues?**
- Clear browser cache (Ctrl+Shift+Delete or Cmd+Shift+Delete)
- Check if CSS file is properly linked

## 📝 License

This project is open source and available under the MIT License.

## 👤 Author

**Annisa Putri Sajjida Intansari**
- Email: annisa@example.com
- LinkedIn: [Your LinkedIn Profile]
- GitHub: [Your GitHub Profile]

## 🙏 Credits

- [Font Awesome](https://fontawesome.com/) - Icons
- [Google Fonts](https://fonts.google.com/) - Typography

---

**Last Updated:** July 14, 2024

Made with ❤️ for your professional journey