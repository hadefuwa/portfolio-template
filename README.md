# Hamed Adefuwa - Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This website showcases projects, skills, and provides a professional online presence for Hamed Adefuwa.

## 🌟 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic content
- **Contact Form**: Functional contact form with validation
- **SEO Optimized**: Proper meta tags and semantic HTML
- **Fast Loading**: Optimized for performance
- **Cross-browser Compatible**: Works on all modern browsers

## 🚀 Live Demo

[View Live Portfolio](https://your-username.github.io/portfolio)

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
├── README.md           # This file
└── .gitignore          # Git ignore file
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Interactive functionality and animations
- **Font Awesome**: Icons
- **Google Fonts**: Typography (Inter font family)

## 📱 Sections

1. **Hero Section**: Introduction with call-to-action buttons
2. **About**: Personal information and statistics
3. **Projects**: Showcase of completed projects
4. **Skills**: Technical skills and technologies
5. **Contact**: Contact form and social links

## 🎨 Customization Guide

### Personal Information
Edit the following in `index.html`:

```html
<!-- Update your name -->
<h1 class="hero-title">
    Hi, I'm <span class="highlight">Your Name</span>
</h1>

<!-- Update your title -->
<p class="hero-subtitle">Your Professional Title</p>

<!-- Update your description -->
<p class="hero-description">
    Your personal description here...
</p>

<!-- Update contact information -->
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
```

### Projects
Replace the project cards in the projects section with your own:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-project-icon"></i>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-live-demo-url" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live Demo
            </a>
            <a href="your-github-url" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
        </div>
    </div>
</div>
```

### Skills
Update the skills section with your technologies:

```html
<div class="skill-item">
    <i class="fab fa-technology-icon"></i>
    <span>Technology Name</span>
</div>
```

### Colors and Styling
Modify the color scheme in `styles.css`:

```css
/* Primary colors */
:root {
    --primary-color: #2563eb;
    --secondary-color: #fbbf24;
    --gradient-start: #667eea;
    --gradient-end: #764ba2;
}
```

## 🚀 Hosting on GitHub Pages

### Step 1: Create GitHub Repository
1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon and select "New repository"
3. Name it `portfolio` (or your preferred name)
4. Make it public
5. Don't initialize with README (we already have one)

### Step 2: Upload Files
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/portfolio.git
   cd portfolio
   ```

2. Copy all the files from this project into the repository folder

3. Add, commit, and push the files:
   ```bash
   git add .
   git commit -m "Initial portfolio website"
   git push origin main
   ```

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click on "Settings" tab
3. Scroll down to "GitHub Pages" section
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click "Save"

### Step 4: Access Your Website
Your portfolio will be available at:
`https://your-username.github.io/portfolio`

## 🔧 Local Development

To run the website locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/portfolio.git
   cd portfolio
   ```

2. Open `index.html` in your web browser

Or use a local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000`

## 📝 Customization Tips

### Adding Your Photo
1. Replace the profile avatar icon with your photo:
   ```html
   <div class="profile-avatar">
       <img src="path/to/your/photo.jpg" alt="Your Name">
   </div>
   ```

2. Add CSS for the image:
   ```css
   .profile-avatar img {
       width: 100%;
       height: 100%;
       object-fit: cover;
       border-radius: 50%;
   }
   ```

### Adding Real Project Images
Replace the icon-based project images with actual screenshots:
```html
<div class="project-image">
    <img src="path/to/project-screenshot.jpg" alt="Project Name">
</div>
```

### Custom Domain (Optional)
1. Purchase a domain name
2. In your repository settings, under GitHub Pages, add your custom domain
3. Configure your domain's DNS settings to point to GitHub Pages

## 🎯 SEO Optimization

The website includes:
- Proper meta tags
- Semantic HTML structure
- Alt text for images
- Open Graph tags for social sharing
- Structured data for better search results

## 📊 Performance

- Optimized images and assets
- Minified CSS and JavaScript (for production)
- Lazy loading for better performance
- Efficient animations using CSS transforms

## 🔒 Security

- Form validation on both client and server side
- XSS protection
- Secure external links
- HTTPS enforcement on GitHub Pages

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you find any bugs or have suggestions, please open an issue.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Developer

**Hamed Adefuwa**
- Email: hamed.adefuwa@email.com
- GitHub: [@your-github-username](https://github.com/your-github-username)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/your-profile)

---

⭐ If you find this portfolio template helpful, please give it a star on GitHub! 