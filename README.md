# Realme Narzo 70x 5G - Product Landing Page

![Realme Narzo 70x 5G](assets/images/narzo_hero_front_1769578728282.png)

A modern, responsive product landing page for the **Realme Narzo 70x 5G** smartphone, built with Bootstrap 5 and custom SCSS.

## ✨ Features

- **Responsive Design** - Mobile-first approach, looks great on all devices
- **Bootstrap 5** - Modern framework for rapid development
- **Custom SCSS** - Modular stylesheets with variables, mixins, and partials
- **Hero Carousel** - Auto-playing product image showcase
- **Feature Cards** - Clean grid layout showcasing key features
- **Specifications Table** - Detailed technical specifications
- **Interactive Gallery** - Hover effects and smooth animations
- **Pricing Cards** - Multiple variants with glassmorphism design
- **Smooth Scrolling** - Enhanced UX with scroll animations
- **SEO Optimized** - Proper meta tags, semantic HTML, and accessibility

## 🚀 Quick Start

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- (Optional) SASS compiler for editing SCSS files

### Running Locally

1. **Clone or Download** this repository to your local machine

2. **Navigate** to the project directory:
   ```bash
   cd product_info
   ```

3. **Open** `index.html` in your browser:
   - Double-click `index.html`, or
   - Right-click → Open with → Your Browser, or
   - Use a local server (recommended):
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js
     npx serve
     
     # Using PHP
     php -S localhost:8000
     ```

4. **View** the website at `http://localhost:8000`

## 📁 Project Structure

```
product_info/
├── index.html              # Main HTML file
├── README.md              # This file
├── assets/
│   └── images/           # Product images
│       ├── narzo_hero_front_*.png
│       ├── narzo_back_view_*.png
│       ├── narzo_side_angle_*.png
│       ├── narzo_display_feature_*.png
│       ├── narzo_camera_closeup_*.png
│       ├── narzo_lifestyle_*.png
│       └── narzo_battery_feature_*.png
├── css/
│   └── style.css         # Compiled CSS
├── scss/
│   ├── style.scss        # Main SCSS file
│   ├── _variables.scss   # Color variables, spacing, etc.
│   ├── _mixins.scss      # Reusable SCSS mixins
│   ├── _header.scss      # Navigation & Hero section
│   ├── _features.scss    # Features & Specifications
│   ├── _gallery.scss     # Image gallery
│   ├── _pricing.scss     # Pricing cards
│   └── _footer.scss      # Footer styles
└── js/
    └── script.js         # Custom JavaScript
```

## 🎨 Customization

### Editing Styles

The project uses SCSS for styling. To make changes:

1. **Install SASS** (if not already installed):
   ```bash
   npm install -g sass
   ```

2. **Edit SCSS files** in the `scss/` directory:
   - `_variables.scss` - Colors, fonts, spacing
   - `_header.scss` - Navigation and hero section
   - `_features.scss` - Feature cards and specs
   - `_gallery.scss` - Gallery grid styles
   - `_pricing.scss` - Pricing cards
   - `_footer.scss` - Footer styles

3. **Compile SCSS to CSS**:
   ```bash
   sass scss/style.scss css/style.css
   ```

4. **Watch for changes** (auto-compile):
   ```bash
   sass --watch scss/style.scss:css/style.css
   ```

### Color Scheme

The design uses **Realme brand colors** defined in `_variables.scss`:

- **Realme Yellow**: `#FFCC00`
- **Realme Black**: `#1a1a1a`
- **White**: `#ffffff`
- **Accent Blue**: `#00a8ff`

## 🌐 GitHub Pages Deployment

Follow these steps to deploy your landing page on GitHub Pages:

### Method 1: Via GitHub Web Interface

1. **Create a new repository** on GitHub
2. **Upload all files** to the repository
3. Go to **Settings** → **Pages**
4. Under **Source**, select **main** branch
5. Click **Save**
6. Your site will be published at: `https://yourusername.github.io/repository-name/`

### Method 2: Via Git Command Line

1. **Initialize Git** in your project folder:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Realme Narzo 70x 5G landing page"
   ```

2. **Create a repository** on GitHub (without initializing README)

3. **Push to GitHub**:
   ```bash
   git remote add origin https://github.com/yourusername/repository-name.git
   git branch -M main
   git push -u origin main
   ```

4. **Enable GitHub Pages**:
   - Go to repository **Settings** → **Pages**
   - Select **main** branch as source
   - Click **Save**

5. **Access your site** at:
   ```
   https://yourusername.github.io/repository-name/
   ```

### Important Notes for GitHub Pages

- ✅ All file paths are **relative** - no changes needed
- ✅ Images are in `assets/images/` directory
- ✅ CSS is compiled and ready in `css/style.css`
- ✅ Bootstrap and icons are loaded via CDN

## 📱 Sections Overview

1. **Hero Section** - Product name, tagline, and image carousel
2. **Features** - 7 key features in a responsive grid
3. **Specifications** - Detailed technical specs table
4. **Gallery** - 6 product images with hover effects
5. **Pricing** - 3 pricing tiers with CTAs
6. **Footer** - Brand info, quick links, social media

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **Bootstrap 5.3.2** - UI Framework
- **SCSS/CSS3** - Styling with variables and mixins
- **JavaScript** - Interactive features
- **Bootstrap Icons** - Icon library
- **Google Fonts** - Poppins & Roboto

## ♿ Accessibility

The landing page follows accessibility best practices:

- Semantic HTML5 elements
- Alt text for all images
- ARIA labels for interactive elements
- Keyboard navigation support
- High contrast text
- Responsive touch targets

## 📄 License

This project is created for educational/demonstration purposes.

## 🤝 Support

For issues or questions:
- Email: support@realme.com
- Phone: 1800-103-2777

---

**Built with ❤️ for Realme | Dare to Leap**
