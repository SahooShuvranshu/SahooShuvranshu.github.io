# 🚀 Shuvranshu Sekhar Sahoo - Portfolio

A modern, Discord-themed personal portfolio website showcasing my skills, projects, services, and blog. Built with vanilla HTML, CSS, and JavaScript.

**Live Demo:** [sahooshuvranshu.me](https://sahooshuvranshu.me)

---

## 📋 Table of Contents

- [Features](#features)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Setup & Installation](#setup--installation)
- [Pages Overview](#pages-overview)
- [Customization Guide](#customization-guide)
- [Social Links](#social-links)
- [License](#license)

---

## ✨ Features

- 🎨 **Discord-Inspired UI** - Modern and attractive design with Discord's color scheme
- 📱 **Fully Responsive** - Works seamlessly on desktop, tablet, and mobile devices
- ⚡ **Fast & Lightweight** - No framework bloat, vanilla JavaScript only
- 🎯 **Multi-Page Navigation** - Tabs for About Me, Skills, Projects, Services, and Blog
- 🌐 **Embedded Blogspot** - Integrated blog section with direct Blogspot feed
- 🔗 **Social Media Integration** - Links to all major social platforms
- 📊 **Dynamic Content Loading** - Pages load dynamically without full page refresh
- ♿ **Accessible** - Semantic HTML and ARIA labels for better accessibility
- 🚀 **GitHub Pages Ready** - Hosted on GitHub Pages with custom domain support

---

## 📁 Project Structure

```
SahooShuvranshu.github.io/
├── index.html              # Main portfolio page
├── README.md              # Project documentation
├── LICENSE                # License file
├── CNAME                  # Custom domain configuration
└── pages/
    ├── about.html         # About Me section
    ├── skills.html        # Skills & Technologies
    ├── projects.html      # Project Portfolio
    ├── services.html      # Services Offered
    └── blog.html          # Blog Section (Blogspot embed)
```

---

## 🛠 Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Advanced styling with animations and transitions
- **JavaScript (Vanilla)** - No dependencies, pure JavaScript
- **GitHub Pages** - Free hosting
- **Blogspot** - External blog integration
- **GitHub API** - For avatar and social links
- **Discord API Icons** - Badge designs and styling

---

## 🎯 Setup & Installation

### Prerequisites
- Git
- A modern web browser
- (Optional) A local web server for testing

### Clone the Repository

```bash
git clone https://github.com/SahooShuvranshu/SahooShuvranshu.github.io.git
cd SahooShuvranshu.github.io
```

### Run Locally

**Using Python:**
```bash
python -m http.server 8000
# or for Python 2
python -m SimpleHTTPServer 8000
```

Then open `http://localhost:8000` in your browser.

**Using Node.js (http-server):**
```bash
npx http-server
```

**Using Live Server (VS Code Extension):**
- Install the "Live Server" extension
- Right-click `index.html` and select "Open with Live Server"

---

## 📄 Pages Overview

### 1. **About Me** (`pages/about.html`)
- Personal introduction and background
- Professional summary
- Key highlights and achievements

### 2. **Skills** (`pages/skills.html`)
- Programming languages and frameworks
- Tools and technologies
- Skill categories with proficiency levels

### 3. **Projects** (`pages/projects.html`)
- Showcase of completed projects
- Project descriptions and technologies used
- Links to project demos and repositories

### 4. **Services** (`pages/services.html`)
- Services offered
- Service descriptions
- Expertise areas

### 5. **Blog** (`pages/blog.html`)
- Embedded Blogspot feed
- Articles and tutorials
- Tech insights and learnings

---

## 🎨 Customization Guide

### Updating Personal Information

Edit `index.html` and update:

```javascript
// Line ~239: Profile Avatar
<img src="https://avatars.githubusercontent.com/u/70892515?v=4" alt="Profile Avatar" class="discord-avatar">

// Line ~243: Username and Discriminator
<div class="discord-username">
    Your Name<span class="discord-discriminator">#YOUR_ID</span>
</div>
```

### Updating Social Links

Find and update all social links in `index.html`:

```html
<!-- GitHub -->
<a href="https://github.com/YourUsername" target="_blank">

<!-- LinkedIn -->
<a href="https://www.linkedin.com/in/your-profile" target="_blank">

<!-- Twitter/X -->
<a href="https://x.com/your_handle" target="_blank">

<!-- Email -->
<a href="mailto:your.email@example.com">
```

### Changing Colors

Update the main color scheme in CSS:

```css
/* Primary Color */
.discord-verified-badge-animated,
.discord-tab.active {
    color: #5865f2; /* Change this color */
}

/* Hover States */
.discord-contact-btn:hover {
    background-color: #2d7d32; /* Customize button colors */
}
```

### Updating Blog Link

Replace your Blogspot URL in `pages/blog.html`:

```html
<iframe src="https://YOUR-BLOGSPOT.blogspot.com/" ...></iframe>
<a href="https://YOUR-BLOGSPOT.blogspot.com/" ...>
```

### Customizing Resume Button

Edit line ~333 in `index.html`:

```javascript
const resumeBtn = document.querySelector('.discord-resume-btn');
if (resumeBtn) {
    resumeBtn.addEventListener('click', function() {
        window.open('YOUR_RESUME_URL_HERE', '_blank');
    });
}
```

---

## 🔗 Social Links

Connect with me on:

- **Website:** [sahooshuvranshu.me](https://sahooshuvranshu.me)
- **GitHub:** [@SahooShuvranshu](https://github.com/SahooShuvranshu)
- **LinkedIn:** [Shuvranshu Sekhar Sahoo](https://www.linkedin.com/in/shuvranshu-sekhar-sahoo-931396207)
- **Twitter/X:** [@Its_Shuvranshu](https://x.com/Its_Shuvranshu)
- **Discord:** [Its_Shuvranshu](https://discord.com/users/879695880528216075)
- **Instagram:** [@its_shuvranshu.alive](https://www.instagram.com/its_shuvranshu.alive/)
- **Blog:** [its-shuvranshu.blogspot.com](https://its-shuvranshu.blogspot.com/)
- **YouTube:** [@sahooshuvranshu](https://www.youtube.com/@sahooshuvranshu)

---

## 📱 Browser Support

- Chrome/Edge (Latest)
- Firefox (Latest)
- Safari (Latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

---

## 🚀 Deployment

### GitHub Pages

This repository is already configured for GitHub Pages:

1. Push changes to the `main` branch
2. GitHub automatically deploys to `https://SahooShuvranshu.github.io`
3. Custom domain configured via `CNAME` file

### Custom Domain Setup

To use a custom domain:

1. Edit the `CNAME` file with your domain
2. Configure DNS settings in your domain registrar
3. Enable GitHub Pages in repository settings

---

## 📝 Features to Consider

- [ ] Dark mode toggle
- [ ] Contact form
- [ ] Project filtering by category
- [ ] Search functionality
- [ ] Analytics integration
- [ ] Newsletter signup
- [ ] Comments section on blog

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙋 Support

If you have questions or want to collaborate, feel free to:

- Open an issue on [GitHub](https://github.com/SahooShuvranshu/SahooShuvranshu.github.io/issues)
- Contact me via [email](mailto:sahooshuvranshusekhar@gmail.com)
- Connect on [LinkedIn](https://www.linkedin.com/in/shuvranshu-sekhar-sahoo-931396207)

---

## 👨‍💻 Author

**Shuvranshu Sekhar Sahoo**
- Full Stack Developer | Discord Bot Developer | Tech Enthusiast
- Portfolio: [sahooshuvranshu.me](https://sahooshuvranshu.me)
- GitHub: [@SahooShuvranshu](https://github.com/SahooShuvranshu)

---

**Made with ❤️ | Last Updated: October 2025**