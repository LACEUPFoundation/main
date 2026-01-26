# LACE UP Foundation Website

A professional, responsive website for LACE UP Foundation - empowering youth through basketball culture, mental performance training, and creative expression.

## 🎯 Mission

LACE UP Foundation's mission is to empower the youth and build communities through a collaborative youth wellness and basketball initiative that combines basketball culture, mental performance training, creative expression, and social-emotional learning to equip young people with tools to navigate adversity, build resilience, and strengthen their personal and community identity.

**Tagline:** In everything you do, LACE UP.

## 🌟 Features

- **Responsive Design**: Optimized for all devices (desktop, tablet, mobile)
- **Modern Aesthetics**: Bold, athletic design inspired by basketball culture
- **Smooth Animations**: Engaging scroll effects and micro-interactions
- **Performance Optimized**: Fast loading with clean, semantic HTML
- **Accessibility**: WCAG compliant with proper ARIA labels and semantic structure

## 📁 Project Structure

```
laceup-foundation/
├── index.html          # Main HTML file
├── styles.css          # Complete styling
├── script.js           # Interactive functionality
├── logo.png            # LACE UP Foundation logo
└── README.md           # This file
```

## 🚀 Deployment to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **"+"** icon in the top-right corner
3. Select **"New repository"**
4. Name your repository (e.g., `laceup-foundation`)
5. Make it **Public**
6. Click **"Create repository"**

### Step 2: Upload Files

**Option A: Using GitHub Web Interface**

1. In your new repository, click **"uploading an existing file"**
2. Drag and drop all files:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `logo.png`
   - `README.md`
3. Click **"Commit changes"**

**Option B: Using Git Command Line**

```bash
# Initialize git in your project folder
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: LACE UP Foundation website"

# Add remote repository (replace YOUR-USERNAME and REPO-NAME)
git remote add origin https://github.com/YOUR-USERNAME/REPO-NAME.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **"Settings"** tab
3. Scroll down to **"Pages"** in the left sidebar
4. Under **"Source"**, select **"Deploy from a branch"**
5. Under **"Branch"**, select **"main"** and **"/ (root)"**
6. Click **"Save"**

### Step 4: Access Your Website

After a few minutes, your website will be live at:
```
https://YOUR-USERNAME.github.io/REPO-NAME/
```

For example: `https://laceupfoundation.github.io/laceup-foundation/`

## 🛠️ Customization

### Update Contact Information

Edit the contact section in `index.html`:
```html
<span>info@laceupfoundation.org</span>
```

### Change Colors

Modify CSS variables in `styles.css`:
```css
:root {
    --primary: #0066CC;
    --accent: #FFD700;
    /* etc. */
}
```

### Add Social Media Links

Add social media icons to the footer in `index.html` and style them in `styles.css`.

### Connect Contact Form

To make the contact form functional, you'll need to:

1. Use a service like [Formspree](https://formspree.io/), [Netlify Forms](https://www.netlify.com/products/forms/), or [EmailJS](https://www.emailjs.com/)
2. Or set up a backend endpoint to handle form submissions

Example with Formspree:
```html
<form class="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
    <!-- form fields -->
</form>
```

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎨 Design Inspiration

The website design incorporates:
- Basketball court aesthetics (court grid patterns, athletic typography)
- Bold, empowering color scheme (blue and gold)
- Modern, professional layout
- Youth-focused, energetic visual style

## 📄 License

© 2025 LACE UP Foundation. All rights reserved.

## 🤝 Support

For questions or support, contact: info@laceupfoundation.org

---

**Built with passion for empowering youth and building community unity.**

*In everything you do, LACE UP.*
