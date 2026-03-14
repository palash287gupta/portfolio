# Palash Gupta - Developer Portfolio

Try Here: https://palash287gupta.github.io/portfolio/

A modern, responsive developer portfolio website built with HTML, CSS, and JavaScript. Optimized for GitHub Pages deployment.

## 🌟 Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: 
  - Typing effect for role titles
  - Smooth scroll navigation
  - Animated sections on scroll
  - Floating particles effect
  - Mobile hamburger menu
  - Scroll-to-top button
- **Sections**:
  - Hero/Landing page
  - About Me
  - Skills & Technologies
  - Work Experience
  - Featured Projects
  - Contact Information
- **SEO Optimized**: Meta tags and semantic HTML
- **Fast Loading**: No heavy dependencies, minimal external resources

## 🚀 Deployment to GitHub Pages

### Option 1: Deploy to `username.github.io` (Recommended)

1. **Create a new repository** on GitHub with the name: `your-username.github.io`
   - Replace `your-username` with your actual GitHub username
   - Example: `palashgupta.github.io`

2. **Initialize git in your portfolio folder**:
   ```bash
   cd /Users/palashgupta/Desktop/palash/portfolio
   git init
   git add .
   git commit -m "Initial commit: Add portfolio website"
   ```

3. **Add remote and push**:
   ```bash
   git remote add origin https://github.com/your-username/your-username.github.io.git
   git branch -M main
   git push -u origin main
   ```

4. **Access your site**: Your portfolio will be live at `https://your-username.github.io`

### Option 2: Deploy to a Project Repository

1. **Create a new repository** on GitHub (any name, e.g., `portfolio`)

2. **Initialize and push**:
   ```bash
   cd /Users/palashgupta/Desktop/palash/portfolio
   git init
   git add .
   git commit -m "Initial commit: Add portfolio website"
   git remote add origin https://github.com/your-username/portfolio.git
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click on **Settings** > **Pages**
   - Under "Source", select branch: `main` and folder: `/ (root)`
   - Click **Save**

4. **Access your site**: Your portfolio will be live at `https://your-username.github.io/portfolio`

## 📝 Customization Guide

### Update Personal Information

1. **Contact Details** - Update in `index.html`:
   - Email address (multiple places)
   - LinkedIn URL
   - GitHub URL

2. **Profile Content**:
   - Hero section description
   - About Me text
   - Work experience
   - Project descriptions
   - Skills and technologies

### Customize Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #00d4ff;      /* Primary accent color */
    --secondary-color: #0066ff;    /* Secondary color */
    --accent-color: #ff6b6b;       /* Accent for highlights */
    --bg-dark: #0a192f;            /* Dark background */
    --bg-light: #112240;           /* Light background */
    --text-primary: #ccd6f6;       /* Primary text color */
    --text-secondary: #8892b0;     /* Secondary text color */
    --text-highlight: #64ffda;     /* Highlight color */
}
```

### Add Your Photo

To add a profile photo instead of the icon:

1. Add your image to the portfolio folder (e.g., `profile.jpg`)
2. Replace the profile icon in `index.html`:

```html
<!-- Replace this: -->
<div class="profile-icon">
    <i class="fas fa-user-circle"></i>
</div>

<!-- With this: -->
<img src="profile.jpg" alt="Palash Gupta" style="width: 300px; height: 300px; border-radius: 50%; object-fit: cover;">
```

### Update Projects

Edit the projects section in `index.html`:

```html
<div class="project-card">
    <div class="project-icon">
        <i class="fas fa-project-icon"></i>
    </div>
    <h3>Project Name</h3>
    <p>Project description...</p>
    <div class="project-tags">
        <span class="tag">Technology 1</span>
        <span class="tag">Technology 2</span>
    </div>
</div>
```

### Add Links to Projects

To add live demo or GitHub links to projects:

```html
<div class="project-card">
    <!-- ... project content ... -->
    <div class="project-links">
        <a href="https://github.com/..." target="_blank" class="btn btn-primary">
            <i class="fab fa-github"></i> View Code
        </a>
        <a href="https://demo-link..." target="_blank" class="btn btn-secondary">
            <i class="fas fa-external-link-alt"></i> Live Demo
        </a>
    </div>
</div>
```

## 🔧 Local Development

To test locally:

1. **Simple way**: Just open `index.html` in your browser

2. **Using Python's HTTP server**:
   ```bash
   cd /Users/palashgupta/Desktop/palash/portfolio
   python3 -m http.server 8000
   ```
   Then visit `http://localhost:8000`

3. **Using Node.js's http-server**:
   ```bash
   npx http-server .
   ```

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🎨 Custom Domain (Optional)

To use a custom domain like `palashgupta.dev`:

1. **Buy a domain** from providers like Namecheap, GoDaddy, or Google Domains

2. **Add CNAME file** to your repository:
   ```bash
   echo "yourdomain.com" > CNAME
   git add CNAME
   git commit -m "Add custom domain"
   git push
   ```

3. **Configure DNS** at your domain provider:
   - Add an A record pointing to GitHub's IPs:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
   - Or add a CNAME record pointing to `your-username.github.io`

4. **Enable HTTPS** in GitHub Pages settings

## 📦 File Structure

```
portfolio/
│
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript functionality
├── README.md           # This file
└── CNAME              # (Optional) Custom domain file
```

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio!

## 📄 License

This project is open source and available under the MIT License.

## 📧 Contact

**Palash Gupta**
- Email: palash.gupta287@gmail.com
- LinkedIn: [palash-gupta-861a33150](https://www.linkedin.com/in/palash-gupta-861a33150)
- GitHub: [@palashgupta](https://github.com/palashgupta)

---

**Built with ❤️ for GitHub Pages**

If you found this helpful, consider giving it a ⭐ on GitHub!
