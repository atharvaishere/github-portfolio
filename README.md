# GitHub Portfolio Website

A modern, responsive portfolio website designed to showcase your GitHub projects and development skills. Built with HTML5, CSS3, and Bootstrap 5.

## Features

- **Modern Dark Theme Design** - Professional dark mode with gradient accents
- **Fully Responsive** - Mobile-first design that looks great on all devices
- **Smooth Animations** - Subtle hover effects and scroll animations
- **Easy to Customize** - Well-organized code with clear placeholder content
- **GitHub Pages Ready** - Deploy immediately to GitHub Pages
- **Bootstrap 5** - Leverages Bootstrap's grid system and components
- **Font Awesome Icons** - Professional icon library included
- **Google Fonts** - Clean, modern Inter font family

## Sections

1. **Navbar** - Sticky navigation with smooth scrolling
2. **Hero Section** - Eye-catching introduction with call-to-action buttons
3. **Projects Section** - Grid layout showcasing 6 featured projects
4. **About Section** - Personal bio and technical skills display
5. **Contact Section** - Contact information and placeholder form
6. **Footer** - Copyright and social media links

## Quick Start

### 1. Customize Your Content

#### Update Personal Information

Open `index.html` and replace the following placeholders:

- **Your Name/Brand**: Replace `DevPortfolio` with your name or brand
- **GitHub Username**: Replace `yourusername` with your actual GitHub username
- **Email**: Replace `your.email@example.com` with your email
- **LinkedIn**: Replace `yourprofile` with your LinkedIn username
- **Twitter**: Replace `yourhandle` with your Twitter handle

#### Update Projects

Each project card has the following structure:

```html
<div class="col-lg-4 col-md-6">
    <div class="project-card">
        <div class="project-header">
            <i class="fas fa-folder-open project-icon"></i>
            <div class="project-links">
                <a href="REPO_URL" target="_blank">
                    <i class="fab fa-github"></i>
                </a>
                <a href="DEMO_URL" target="_blank">
                    <i class="fas fa-external-link-alt"></i>
                </a>
            </div>
        </div>
        <h3 class="project-title">Project Name</h3>
        <p class="project-description">
            Project description here...
        </p>
        <div class="project-tech">
            <span class="tech-badge">Tech1</span>
            <span class="tech-badge">Tech2</span>
            <span class="tech-badge">Tech3</span>
        </div>
    </div>
</div>
```

To add or remove projects:
- **Add**: Copy a project card and modify the content
- **Remove**: Delete the entire `<div class="col-lg-4 col-md-6">` block

#### Update Skills

In the About section, modify the skills grid:

```html
<div class="skill-item">
    <i class="fab fa-js skill-icon"></i>
    <span>JavaScript</span>
</div>
```

Find Font Awesome icons at: https://fontawesome.com/icons

#### Update About Section

Replace the placeholder text in the about section with your own bio and professional summary.

### 2. Deploy to GitHub Pages

#### Option A: Using GitHub Web Interface

1. Go to your repository on GitHub
2. Click on **Settings**
3. Scroll down to **Pages** section
4. Under **Source**, select `main` branch
5. Click **Save**
6. Your site will be live at: `https://yourusername.github.io/github-portfolio/`

#### Option B: Using Git Commands

```bash
# Add all files
git add .

# Commit changes
git commit -m "Initial portfolio website"

# Push to GitHub
git push origin main

# Enable GitHub Pages in repository settings
```

### 3. Custom Domain (Optional)

To use a custom domain:

1. Add a `CNAME` file to your repository with your domain name
2. Configure your DNS settings with your domain provider
3. Update GitHub Pages settings to use your custom domain

## Customization Tips

### Change Color Scheme

Edit the CSS variables in `style.css`:

```css
:root {
    --primary-color: #3b82f6;      /* Main accent color */
    --primary-hover: #2563eb;      /* Hover state */
    --secondary-color: #10b981;    /* Secondary accent */
    --bg-dark: #0f172a;            /* Main background */
    --bg-darker: #020617;          /* Darker sections */
    --bg-card: #1e293b;            /* Card background */
}
```

### Add Profile Image

Replace the icon placeholder in the About section:

```html
<!-- Replace this -->
<div class="about-image">
    <i class="fas fa-user-circle"></i>
</div>

<!-- With this -->
<div class="about-image">
    <img src="path/to/your/image.jpg" alt="Your Name">
</div>
```

Add this CSS:

```css
.about-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 50%;
}
```

### Enable Contact Form

The contact form is a placeholder. To make it functional, you can use:

- **Formspree**: https://formspree.io/
- **Netlify Forms**: https://www.netlify.com/products/forms/
- **EmailJS**: https://www.emailjs.com/
- **Your own backend service**

Example with Formspree:

```html
<form class="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
    <!-- Your form fields -->
</form>
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with flexbox and grid
- **Bootstrap 5.3.2** - Responsive framework
- **Font Awesome 6.5.1** - Icon library
- **Google Fonts (Inter)** - Typography

## File Structure

```
github-portfolio/
├── index.html          # Main HTML file
├── style.css           # Custom CSS styles
└── README.md           # This file
```

## Performance Tips

1. **Optimize Images**: Compress images before uploading
2. **Lazy Loading**: Add `loading="lazy"` to images
3. **Minimize CSS**: Use a CSS minifier for production
4. **CDN**: Bootstrap and Font Awesome are loaded from CDN for better caching

## License

Feel free to use this template for your personal portfolio. No attribution required.

## Support

If you encounter any issues or have questions:

1. Check the HTML and CSS for proper syntax
2. Ensure all CDN links are accessible
3. Test in different browsers
4. Validate your HTML at https://validator.w3.org/

## Credits

- Bootstrap: https://getbootstrap.com/
- Font Awesome: https://fontawesome.com/
- Google Fonts: https://fonts.google.com/

---

**Happy Coding!** Showcase your projects with style.









Last updated: 2025-12-27 *