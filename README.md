# Maitri Soni - Portfolio Website

A modern, responsive portfolio website showcasing my skills, experience, education, and projects. Built with pure HTML, CSS, and JavaScript.

> **Note**: This project has been migrated from SCSS to pure CSS. All styles are now in standard CSS format - no build tools or compilation required!

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works on all devices (desktop, tablet, mobile)
- **Smooth Scrolling**: Smooth navigation between sections
- **Animated Typing Effect**: Dynamic typing animation for role display using Typed.js
- **Interactive Navigation**: Sticky navbar with mobile menu support
- **Project Showcase**: Grid layout displaying featured projects with hover effects
- **Contact Form**: Functional contact form with validation
- **Social Links**: Quick access to LinkedIn, GitHub, and Email
- **Modern UI**: Clean, dark-themed design with smooth transitions

## 🛠️ Technologies Used

### Core Technologies
- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid (Pure CSS - no SCSS/SASS)
- **JavaScript (ES6+)**: Interactive functionality

> **Important**: This project uses **pure CSS**, not SCSS. All styles are written in standard CSS format. No compilation or build process needed!

### External Libraries
- **Typed.js**: Typing animation effect
- **Font Awesome**: Icon library
- **Google Fonts**: Poppins font family

## 📁 Project Structure

```
maitri-portfolio/
│
├── index.html          # Main HTML file
├── style.css           # Main stylesheet (Pure CSS)
├── script.js           # Main JavaScript file
├── README.md           # Project documentation
├── .gitignore          # Git ignore file
├── .gitattributes      # Git attributes (for language detection)
│
└── images/             # Image assets
    ├── Logo & Icons
    │   ├── ms-logo-design-initial-gold-sm-letter-vector-38289644-removebg-preview.png
    │   ├── menu.png
    │   └── hireme.png
    ├── Hero Section
    │   └── portfolio-Photoroom.png
    ├── Skills Icons
    │   ├── website-design.png
    │   ├── sql-server-icon-9-removebg-preview.png
    │   └── app-design.png
    ├── Experience Icons
    │   ├── tacttree circle.png
    │   ├── itcg circle.png
    │   └── cs circle.png
    ├── Education Icons
    │   ├── svit.png
    │   └── school.png
    ├── Project Images
    │   ├── atliq - hospitality.png
    │   ├── sales 23-25.png
    │   └── atliq suplly chain.png
    ├── Social Icons
    │   ├── linkedlogo.png
    │   ├── githublogo.png
    │   └── gmail.png
    └── MAITRI SONI_RESUME.pdf
```

> **Note**: This project uses only essential files. All external libraries (Typed.js, Font Awesome) are loaded via CDN. No local libraries or build tools required!

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for development)
- Internet connection (for CDN resources: Typed.js, Font Awesome, Google Fonts)

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd maitri-portfolio
   ```

2. **Open the project**
   - Simply open `index.html` in your web browser, or
   - Use a local development server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     
     # Using PHP
     php -S localhost:8000
     ```

3. **Access the website**
   - If opened directly: `file:///path/to/index.html`
   - If using a server: `http://localhost:8000`

## 📄 Sections

### 1. **Home/Hero Section**
- Introduction with animated typing effect
- Professional tagline
- "Hire Me" button with dropdown menu (Resume, LinkedIn, GitHub)

### 2. **About Section**
- Professional summary
- Skills showcase:
  - Data Analytics
  - Database Administration
  - Business Analysis

### 3. **Experience Section**
- Work experience timeline:
  - Data Analyst – Research & Operations at TactTree LLP
  - Data Analyst Intern at ITCG Solution Pvt. Ltd.
  - Frontend Web Development Intern at CodeSpeedy Technology Pvt. Ltd.

### 4. **Education Section**
- Academic background:
  - Bachelor in Information Technology (SVIT, Vasad)
  - Higher Secondary (Parth School of Science, Vadodara)

### 5. **Projects Section**
- Featured projects with images
- Links to GitHub repositories
- "See More" button for additional projects

### 6. **Contact Section**
- Contact form (Name, Email, Message)
- Social media links (LinkedIn, GitHub, Email)

## 🎨 Customization

### Changing Colors
Edit the color scheme in `style.css`:
```css
/* Main background */
background: #121212;

/* Accent color */
color: yellow;

/* Card backgrounds */
background: #333;
```

### Updating Content
- **Personal Information**: Edit `index.html` directly
- **Styling**: Modify `style.css`
- **Functionality**: Update `script.js`

### Adding Projects
Add new project cards in the projects section:
```html
<a href="project-url" target="_blank" class="proj-card">
    <img src="images/project-image.png" alt="Project Name">
    <h3>Project Name</h3>
</a>
```

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Features in Detail

### Responsive Navigation
- Desktop: Horizontal menu bar
- Mobile: Hamburger menu with dropdown

### Typed.js Integration
Dynamic role display with typing animation:
```javascript
var typed = new Typed("#typed", {
    strings: [
        "Frontend Developer",
        "Data Analyst",
        "Business Analyst"
    ],
    typeSpeed: 50,
    backSpeed: 30,
    loop: true
});
```

### Form Validation
Client-side validation for contact form:
- Required field validation
- Email format validation
- User-friendly error messages

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Maitri Soni**
- LinkedIn: [maitri-soni-a19753312](https://www.linkedin.com/in/maitri-soni-a19753312/)
- GitHub: [Maitrisoni1803](https://github.com/Maitrisoni1803)
- Email: maitrinsoni183@gmail.com

## 🙏 Acknowledgments

- [Typed.js](https://github.com/mattboldt/typed.js/) for the typing animation
- [Font Awesome](https://fontawesome.com/) for icons
- [Google Fonts](https://fonts.google.com/) for the Poppins font

## 📞 Contact

For any inquiries or collaboration opportunities, please reach out via:
- **Email**: maitrinsoni183@gmail.com
- **LinkedIn**: [Connect with me](https://www.linkedin.com/in/maitri-soni-a19753312/)
- **GitHub**: [View my work](https://github.com/Maitrisoni1803)

---

## 📌 Important Notes

### Language & Build Process
- **CSS Format**: This project uses **pure CSS** (not SCSS/SASS)
- **No Build Tools**: No compilation, preprocessing, or build process required
- **Direct Usage**: Simply open `index.html` in a browser - it works immediately!
- **GitHub Language**: The repository is correctly identified as CSS/HTML/JavaScript

### Migration from SCSS
This project was previously written in SCSS but has been converted to pure CSS for:
- ✅ Simpler deployment (no build step)
- ✅ Better compatibility (works everywhere)
- ✅ Easier maintenance (standard CSS)
- ✅ Faster loading (no compilation needed)

**Note**: The only SCSS files remaining are in the `fonts/` directory - these are icon font definitions and are not used by the main portfolio. They can be safely ignored.

