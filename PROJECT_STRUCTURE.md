# Portfolio Project Structure

## Overview
This is a clean, minimal portfolio website built with pure HTML, CSS, and JavaScript. No build tools, no compilation, no dependencies to install.

## File Organization

### Root Files
- `index.html` - Main HTML structure
- `style.css` - All styling (Pure CSS, no SCSS)
- `script.js` - All JavaScript functionality
- `README.md` - Project documentation
- `.gitignore` - Git ignore rules
- `.gitattributes` - Git language detection

### Images Folder
The `images/` folder contains only the images actually used in the portfolio:

#### Navigation & UI
- `ms-logo-design-initial-gold-sm-letter-vector-38289644-removebg-preview.png` - Logo
- `menu.png` - Mobile menu icon
- `hireme.png` - Hire me button icon

#### Hero Section
- `portfolio-Photoroom.png` - Main hero image

#### Skills Section
- `website-design.png` - Data Analytics icon
- `sql-server-icon-9-removebg-preview.png` - Database Admin icon
- `app-design.png` - Business Analysis icon

#### Experience Section
- `tacttree circle.png` - TactTree company logo
- `itcg circle.png` - ITCG company logo
- `cs circle.png` - CodeSpeedy company logo

#### Education Section
- `svit.png` - SVIT college logo
- `school.png` - School logo

#### Projects Section
- `atliq - hospitality.png` - Project 1 image
- `sales 23-25.png` - Project 2 image
- `atliq suplly chain.png` - Project 3 image

#### Contact Section
- `linkedlogo.png` - LinkedIn icon
- `githublogo.png` - GitHub icon
- `gmail.png` - Gmail icon

#### Documents
- `MAITRI SONI_RESUME.pdf` - Resume PDF

## External Dependencies (CDN)

The project uses these external resources loaded via CDN:

1. **Google Fonts** - Poppins font family
   ```html
   <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
   ```

2. **Font Awesome** - Icons
   ```html
   <script src="https://kit.fontawesome.com/a062c2d457.js" crossorigin="anonymous"></script>
   ```

3. **Typed.js** - Typing animation
   ```html
   <script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>
   ```

## What's NOT Included

This project does NOT include:
- ❌ Local CSS libraries (Bootstrap, etc.)
- ❌ Local JavaScript libraries
- ❌ Build tools (Webpack, Gulp, etc.)
- ❌ SCSS/SASS files
- ❌ Node modules
- ❌ Unused images or assets

## Cleanup Status

✅ HTML cleaned - No inline styles  
✅ CSS organized - All styles in `style.css`  
✅ JavaScript organized - All scripts in `script.js`  
✅ Images organized - Only used images kept  
✅ Unused folders removed - `css/`, `js/`, `lib/`, `fonts/` can be deleted  

## Deployment

Simply upload these files to any web server:
- `index.html`
- `style.css`
- `script.js`
- `images/` folder (with all images)

That's it! No build process needed.

