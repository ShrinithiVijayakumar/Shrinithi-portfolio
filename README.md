# Personal Portfolio Website

A modern, responsive portfolio website showcasing web development skills, projects, certificates, hobbies, and personal interests. Built with HTML, CSS, and JavaScript with unique customizations and animations.

## 🌟 Features

### ✨ Unique Design Elements
- **Particle Background Animation** - Dynamic floating particles
- **Dark/Light Theme Toggle** - Seamless theme switching with local storage
- **Typewriter Effect** - Animated text on homepage
- **Smooth Scrolling** - Enhanced navigation experience
- **Interactive Animations** - Hover effects and scroll-triggered animations

### 📱 Responsive Design
- Mobile-first approach
- Optimized for all screen sizes
- Touch-friendly interface
- Print-friendly styles

### 🎨 Modern UI Components
- Gradient backgrounds and modern color scheme
- Card-based layouts
- Interactive buttons and forms
- Smooth transitions and animations

## 📂 Project Structure

```
website/
├── index.html              # Homepage with hero section and overview
├── about.html              # About page with resume, skills, and timeline
├── projects.html           # Projects showcase with GitHub integration
├── certificates.html       # Certificates and achievements display
├── hobbies.html           # Creative hobbies, art, and writing
├── contact.html           # Contact form and social media links
├── styles/
│   ├── main.css           # Main styles and global variables
│   ├── about.css          # About page specific styles
│   ├── projects.css       # Projects page specific styles
│   ├── certificates.css   # Certificates page specific styles
│   ├── hobbies.css        # Hobbies page specific styles
│   └── contact.css        # Contact page specific styles
└── scripts/
    └── main.js            # JavaScript for interactions and animations
```

## 🎯 Page Features

### 🏠 Homepage (index.html)
- Hero section with typewriter animation
- Animated statistics counters
- Quick overview cards
- Floating technology icons

### 👤 About Page (about.html)
- Professional timeline
- Animated skill progress bars
- Technical skills categorization
- Resume download section

### 💼 Projects Page (projects.html)
- Project filtering system
- Interactive project cards
- GitHub statistics
- Live demo and source code links

### 🏆 Certificates Page (certificates.html)
- Certificate categorization and filtering
- Achievement timeline
- Interactive certificate showcase
- Professional certification display

### 🎨 Hobbies Page (hobbies.html)
- Art gallery with lightbox
- Creative writing showcase
- Photography portfolio
- Personal interests cards

### 📧 Contact Page (contact.html)
- Interactive contact form with validation
- Social media links
- FAQ accordion
- Availability status indicator

## 🚀 Getting Started

### 1. Customize Your Information

#### Update Personal Information
Edit the following files to add your personal information:

**index.html:**
```javascript
// Update the typewriter text in main.js or directly in HTML
this.typewriterEffect('name-typewriter', 'Your Name', 100);
this.typewriterEffect('role-typewriter', 'Your Title', 80);
```

**All pages:**
- Replace placeholder text with your information
- Update LinkedIn, GitHub, and email links
- Add your profile photo (replace placeholder images)

#### Update Project Information
**projects.html:**
- Replace placeholder project cards with your actual projects
- Update GitHub repository links
- Add your project screenshots

#### Update Certificates
**certificates.html:**
- Add your actual certificates
- Update certificate provider information
- Include certificate verification links

#### Update Hobbies Content
**hobbies.html:**
- Replace art gallery images with your artwork
- Update writing samples with your content
- Customize hobby categories

### 2. Customize Colors and Theme

**Edit styles/main.css:**
```css
:root {
    /* Customize these color variables */
    --primary-color: #667eea;     /* Your brand primary color */
    --secondary-color: #764ba2;   /* Your brand secondary color */
    --accent-color: #f093fb;      /* Your accent color */
    /* ... other variables */
}
```

### 3. Add Your Images

Replace placeholder images with your own:
- Profile photos
- Project screenshots
- Artwork/hobby images
- Certificate images

### 4. Configure Contact Form

**contact.html:**
Update the form submission handler in the JavaScript section or connect to your backend service:

```javascript
// Replace the setTimeout simulation with actual form submission
fetch('/api/contact', {
    method: 'POST',
    body: formData
})
.then(response => response.json())
.then(data => {
    // Handle success
});
```

### 5. Update Social Media Links

Replace all placeholder links with your actual profiles:
- LinkedIn: `https://linkedin.com/in/yourprofile`
- GitHub: `https://github.com/yourusername`
- Email: `your.email@example.com`
- Other social media platforms

## 🔧 Technical Features

### JavaScript Functionality
- **Particle System**: Animated background particles
- **Theme Toggle**: Dark/light mode with persistence
- **Typewriter Animation**: Dynamic text typing effect
- **Form Validation**: Contact form with error handling
- **Scroll Animations**: Intersection Observer API for animations
- **Filtering**: Project and certificate filtering
- **Lightbox**: Image gallery viewer

### CSS Features
- **CSS Variables**: Easy theme customization
- **Flexbox & Grid**: Modern layout techniques
- **Animations**: Smooth transitions and keyframe animations
- **Responsive Design**: Mobile-first approach
- **Dark Mode**: Complete dark theme support

## 🌐 Deployment Options

### GitHub Pages
1. Create a GitHub repository
2. Upload your files
3. Enable GitHub Pages in repository settings
4. Your site will be live at `https://yourusername.github.io/repository-name`

### Netlify
1. Create an account on Netlify
2. Drag and drop your folder to Netlify
3. Your site will be automatically deployed

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts to deploy

### Traditional Web Hosting
Upload all files to your web hosting provider's public directory (usually `public_html` or `www`).

## 📱 Browser Compatibility

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎨 Customization Tips

### Adding New Sections
1. Create new HTML structure following existing patterns
2. Add corresponding CSS in a new file or existing stylesheets
3. Include JavaScript for interactivity if needed
4. Update navigation menu

### Changing Animations
- Modify keyframe animations in CSS files
- Adjust animation durations and delays
- Customize easing functions

### Adding New Features
- Follow the existing code structure
- Use CSS variables for consistency
- Maintain responsive design principles

## 📋 SEO Optimization

- Update `<title>` tags for each page
- Add meta descriptions
- Include Open Graph tags for social sharing
- Use semantic HTML structure
- Add alt attributes to images

## 🔒 Security Considerations

- Validate form inputs on both client and server side
- Sanitize user data before processing
- Use HTTPS for production deployment
- Consider adding CAPTCHA to contact form

## 📞 Support

For questions or customization help:
- Check the code comments for guidance
- Refer to MDN Web Docs for HTML/CSS/JS reference
- Use browser developer tools for debugging

## 🎯 Future Enhancements

Consider adding:
- Blog functionality
- CMS integration
- Analytics tracking
- Performance optimization
- PWA features
- Multi-language support

---

**Happy Coding! 🚀**

Remember to replace all placeholder content with your actual information to make this portfolio truly yours!