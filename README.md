# Small Fish Club Website

A modern, responsive website for Small Fish Club - Restaurant, Café & Animation located in Saidia, Morocco.

## 🌊 About

This website showcases Small Fish Club's offerings with a beautiful coastal design featuring:
- **Restaurant**: Delicious Moroccan and Mediterranean cuisine
- **Café**: Refreshing drinks and coffee
- **Animation**: Family-friendly entertainment

## 🎨 Features

- ✨ Modern, responsive design with coastal blue & yellow theme
- 📱 Mobile-first approach with smooth animations
- 🎯 Single-page application with smooth scrolling
- 🍔 Interactive menu with category filtering
- 🖼️ Beautiful image gallery
- ⭐ Customer testimonials section
- 📍 Google Maps integration
- 📞 Click-to-call functionality
- 🚀 Fast loading with lazy image loading
- ♿ SEO-friendly and accessible

## 📂 Project Structure

\\\
smallfishclub/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # All styling
├── js/
│   └── main.js         # JavaScript functionality
├── images/             # Image assets
│   ├── hero.png
│   ├── hamburger.png
│   ├── smoky-burger.png
│   ├── pizza-pepperoni.png
│   ├── moroccan-salad.png
│   └── banana-split.png
└── README.md           # This file
\\\

## 🚀 Deployment to GitHub Pages

### Step 1: Push to GitHub Repository

1. Navigate to your project folder:
\\\ash
cd \"C:\\Karim\\projects\\sites for clients\\smallfishclub\"
\\\

2. Initialize Git (if not already done):
\\\ash
git init
\\\

3. Add all files:
\\\ash
git add .
\\\

4. Commit your changes:
\\\ash
git commit -m \"Initial commit: Small Fish Club website\"
\\\

5. Add your GitHub repository as remote:
\\\ash
git remote add origin https://github.com/YOUR_USERNAME/smallfishclub.git
\\\

6. Push to GitHub:
\\\ash
git branch -M main
git push -u origin main
\\\

### Step 2: Enable GitHub Pages

1. Go to your GitHub repository
2. Click on **Settings**
3. Scroll down to **Pages** in the left sidebar
4. Under **Source**, select **main** branch
5. Click **Save**
6. Your site will be published at: https://YOUR_USERNAME.github.io/smallfishclub/

## 💻 Local Development

To run the website locally:

1. Simply open index.html in your web browser
2. Or use a local server (recommended):

Using Python:
\\\ash
python -m http.server 8000
\\\

Using Node.js (with http-server):
\\\ash
npx http-server
\\\

Then visit http://localhost:8000 in your browser.

## 🎨 Customization Guide

### Changing Colors

Edit the CSS variables in css/styles.css:

\\\css
:root {
    --primary-blue: #0077BE;
    --accent-yellow: #FFD700;
    /* ... other colors */
}
\\\

### Updating Content

- **Business Info**: Edit text in index.html
- **Menu Items**: Update the menu section in index.html
- **Images**: Replace images in the images/ folder
- **Contact Info**: Update phone, address, and social links in the contact section

### Adding Menu Items

Copy this template in the menu section:

\\\html
<div class=\"menu-item\" data-category=\"food\">
    <div class=\"menu-item-image\">
        <img src=\"images/your-image.png\" alt=\"Item Name\" loading=\"lazy\">
    </div>
    <div class=\"menu-item-content\">
        <h3>Item Name</h3>
        <p>Description of the item</p>
        <span class=\"price\">MAD XX-XX</span>
    </div>
</div>
\\\

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📞 Contact Information

**Small Fish Club**
- 📍 Address: 279 Avenue Mohamed V, 60600 Saidia, Morocco
- 📞 Phone: 0648-225691
- 📷 Instagram: @smallfishclub
- 🗺️ Map Code: 3QQC+37 Saidia

## 📄 License

© 2025 Small Fish Club. All rights reserved.

## 🙏 Credits

- Design & Development: Custom built for Small Fish Club
- Fonts: Google Fonts (Poppins, Playfair Display)
- Icons: Font Awesome
- Images: AI-generated and custom photography

---

**Enjoy your visit to Small Fish Club! 🐟**
