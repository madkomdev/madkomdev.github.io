# Madhu Kommula - Personal Portfolio

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. Features a clean design, smooth animations, and mobile-first responsive layout.

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic navigation
- **Contact Form**: Functional contact form with validation
- **Project Showcase**: Display your projects with links to GitHub and live demos
- **Resume Download**: Easy resume download functionality
- **Social Media Integration**: Links to LinkedIn, GitHub, and other social platforms
- **SEO Optimized**: Semantic HTML structure for better search engine visibility
- **Fast Loading**: Optimized for performance with minimal dependencies

## 📁 Project Structure

```
madkomdev/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── resume.pdf          # Your resume (add your own)
└── README.md           # This file
```

## 🛠️ Setup Instructions

### 1. Clone or Download
```bash
git clone https://github.com/your-username/madkomdev.git
cd madkomdev
```

### 2. Customize Your Information

#### Update Personal Information in `index.html`:

1. **Replace placeholder text** with your actual information:
   - Name: "Madhu Kommula" → Your name
   - Title: "Full Stack Developer & Software Engineer" → Your title
   - Email: "your.email@example.com" → Your email
   - Phone: "+1 (555) 123-4567" → Your phone number
   - Location: "Your City, Country" → Your location

2. **Update social media links**:
   - LinkedIn: `https://linkedin.com/in/your-profile`
   - GitHub: `https://github.com/your-username`
   - Twitter: `https://twitter.com/your-username`

3. **Add your profile image**:
   - Replace the placeholder image URL with your actual photo
   - Recommended size: 300x300px
   - Format: JPG or PNG

#### Update Projects Section:

Replace the sample projects with your actual projects:

```html
<div class="project-card">
    <div class="project-image">
        <img src="your-project-image.jpg" alt="Your Project Name">
        <div class="project-overlay">
            <a href="https://github.com/your-username/your-project" target="_blank" class="project-link">
                <i class="fab fa-github"></i>
            </a>
            <a href="https://your-project-demo.com" target="_blank" class="project-link">
                <i class="fas fa-external-link-alt"></i>
            </a>
        </div>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Your project description...</p>
        <div class="project-tech">
            <span class="tech-tag">React</span>
            <span class="tech-tag">Node.js</span>
            <!-- Add your technologies -->
        </div>
    </div>
</div>
```

#### Update Skills Section:

Modify the skills in `index.html` to match your expertise:

```html
<div class="skill-tags">
    <span class="skill-tag">Your Skill 1</span>
    <span class="skill-tag">Your Skill 2</span>
    <!-- Add your skills -->
</div>
```

### 3. Add Your Resume

1. Save your resume as `resume.pdf` in the project root directory
2. The download button will automatically link to this file

### 4. Customize Colors and Styling

Edit `styles.css` to match your brand colors:

```css
/* Primary color (used for buttons, links, etc.) */
:root {
    --primary-color: #4f46e5;
    --primary-hover: #3730a3;
    --secondary-color: #7c3aed;
    --accent-color: #fbbf24;
}
```

### 5. Deploy Your Portfolio

#### Option 1: GitHub Pages (Free)
1. Push your code to a GitHub repository
2. Go to repository Settings → Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://yourusername.github.io/repository-name`

#### Option 2: Netlify (Free)
1. Drag and drop your project folder to [Netlify](https://netlify.com)
2. Your site will be live instantly with a custom URL

#### Option 3: Vercel (Free)
1. Connect your GitHub repository to [Vercel](https://vercel.com)
2. Deploy with one click

## 🎨 Customization Guide

### Changing the Color Scheme

The portfolio uses CSS custom properties for easy color customization. Update these variables in `styles.css`:

```css
:root {
    --primary-color: #4f46e5;      /* Main brand color */
    --primary-hover: #3730a3;      /* Hover state */
    --secondary-color: #7c3aed;    /* Secondary color */
    --accent-color: #fbbf24;       /* Accent color */
    --text-color: #333;            /* Main text color */
    --bg-color: #ffffff;           /* Background color */
}
```

### Adding New Sections

To add a new section (e.g., "Experience" or "Education"):

1. Add the HTML structure in `index.html`
2. Add corresponding CSS styles in `styles.css`
3. Update the navigation menu
4. Add smooth scrolling functionality in `script.js`

### Modifying Animations

The portfolio includes several animations. You can customize them in `styles.css`:

- Hero section animations
- Project card hover effects
- Skill tag animations
- Scroll-triggered animations

### Contact Form Integration

The contact form is currently set up for demonstration. To make it functional:

1. **Use a form service** like Formspree, Netlify Forms, or EmailJS
2. **Backend integration** with Node.js, PHP, or Python
3. **Update the form action** in `index.html`

Example with Formspree:
```html
<form action="https://formspree.io/f/your-form-id" method="POST" class="contact-form">
```

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Performance Optimization

The portfolio is optimized for performance:

- Minimal external dependencies
- Optimized images
- Efficient CSS and JavaScript
- Lazy loading for images
- Debounced scroll events

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you make improvements, consider submitting a pull request!

## 📞 Support

If you have any questions or need help customizing your portfolio, feel free to reach out:

- Email: your.email@example.com
- LinkedIn: [Your LinkedIn Profile](https://linkedin.com/in/your-profile)
- GitHub: [Your GitHub Profile](https://github.com/your-username)

---

**Happy coding! 🚀**