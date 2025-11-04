# Portfolio Template

A modern, responsive HTML portfolio template designed for developers and tech professionals.

## Preview

![Portfolio Preview](https://github.com/user-attachments/assets/2f54d17e-8d67-40ec-a3a8-8dfe449dd9f1)

## Features

- ✨ **Modern Design**: Clean, professional layout with smooth animations
- 📱 **Fully Responsive**: Looks great on desktop, tablet, and mobile devices
- 🎨 **Professional Color Scheme**: Eye-catching gradient background with accessible colors
- ⚡ **Fast Loading**: All CSS embedded, no external dependencies
- 🔍 **SEO Friendly**: Proper HTML structure and meta tags
- ♿ **Accessible**: WCAG compliant with proper focus indicators and alt text
- 🎯 **Easy to Customize**: Well-commented code with clear sections

## Sections Included

1. **Header** - Fixed navigation with smooth scrolling
2. **Hero Section** - Name, title, and call-to-action
3. **About Section** - Professional bio with skills tags
4. **Projects Section** - Grid layout showcasing your work
5. **Contact Section** - Social links and contact information
6. **Footer** - Copyright and additional branding

## Quick Start

1. Open `index.html` in your browser
2. Replace placeholder content with your information
3. Update project cards with your actual projects
4. Customize colors and styling if desired
5. Deploy to your preferred hosting service

## Customization Guide

### Personal Information

Update the following sections in `index.html`:

```html
<!-- Hero Section -->
<h1>Your Name</h1>
<p class="subtitle">Your Professional Title</p>
<p class="tagline">Your personal tagline or motto</p>

<!-- About Section -->
<div class="about-text">
    <p>Your professional bio...</p>
</div>

<!-- Skills -->
<div class="skills">
    <span class="skill-tag">Your Skill</span>
    <!-- Add more skills -->
</div>

<!-- Profile Image -->
<img src="your-profile-image.jpg" alt="Your Name" />
```

### Adding Projects

To add a new project, duplicate this project card structure:

```html
<div class="project-card">
    <div class="project-image">🔗</div>
    <div class="project-content">
        <h3 class="project-title">Project Name</h3>
        <p class="project-description">Brief description of your project...</p>
        <div class="project-technologies">
            <span class="tech-tag">Technology</span>
            <span class="tech-tag">Framework</span>
        </div>
        <div class="project-links">
            <a href="github-link" class="project-link">View Code</a>
            <a href="demo-link" class="project-link">Live Demo</a>
        </div>
    </div>
</div>
```

### Social Links

Update the social links in the contact section:

```html
<div class="social-links">
    <a href="your-github-url" class="social-link" aria-label="GitHub Profile">
        <span>📱</span>
    </a>
    <a href="your-linkedin-url" class="social-link" aria-label="LinkedIn Profile">
        <span>💼</span>
    </a>
    <!-- Add more social links -->
</div>
```

### Color Customization

The main colors are defined in CSS custom properties. Update these values:

```css
/* Update the gradient colors */
background: linear-gradient(135deg, #your-color1 0%, #your-color2 100%);

/* Update accent colors */
color: #your-accent-color;
```

### Project Emojis

Each project card uses an emoji as a visual icon. Choose appropriate emojis:

- 🔐 - Security/Encryption projects
- ⚙️ - DevOps/Automation tools
- 🌐 - Web applications
- 🛡️ - Security/Monitoring tools
- 📱 - Mobile applications
- 🤖 - AI/ML projects
- 📊 - Data visualization
- 🚀 - Performance tools

## Browser Support

- Chrome (Latest)
- Firefox (Latest)
- Safari (Latest)
- Edge (Latest)

## File Structure

```
├── index.html          # Main portfolio page
└── README.md          # This file
```

## Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings → Pages
3. Select source branch (usually `main`)
4. Your portfolio will be available at `https://yourusername.github.io/repository-name`

### Netlify
1. Connect your GitHub repository to Netlify
2. Deploy settings: Build command: (none), Publish directory: `/`
3. Your site will be automatically deployed

### Vercel
1. Import your project from GitHub
2. No build configuration needed
3. Deploy automatically

## License

This template is released under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.

You are free to:
- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material

Under the following terms:
- **Attribution** — You must give appropriate credit
- **NonCommercial** — You may not use the material for commercial purposes
- **ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the same license

## Support

If you find this template helpful, please consider:
- ⭐ Starring the repository
- 🐛 Reporting issues
- 🔄 Contributing improvements
- 📢 Sharing with others

## Credits

Created with ❤️ by MayMeow