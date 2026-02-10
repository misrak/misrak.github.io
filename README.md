# Kaalindi Misra - Professional CV Website

This repository hosts my Curriculum Vitae

A modern, interactive, and responsive CV website built with HTML, CSS, and JavaScript. Features smooth animations, scroll effects, and a clean professional design.

## 🌟 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Animations**: Scroll-triggered animations and transitions
- **Interactive Navigation**: Smooth scrolling and active link highlighting
- **Publication Filtering**: Filter publications by journal/conference
- **Modern UI**: Clean, professional design with gradient accents
- **Performance Optimized**: Fast loading and smooth scrolling
- **Mobile Menu**: Responsive navigation for mobile devices

## 📁 File Structure

```
cv-website/
│
├── index.html          # Main HTML structure
├── styles.css          # All styling and animations
├── script.js           # Interactive features
└── README.md           # This file
```

## 🎨 Customization

### Change Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;      /* Main blue color */
    --secondary-color: #7c3aed;    /* Purple accent */
    --accent-color: #06b6d4;       /* Cyan accent */
    --dark: #0f172a;               /* Dark text */
}
```

### Modify Content

Edit `index.html` to update:
- Personal information
- Experience details
- Education
- Publications
- Skills
- Contact information

### Add/Remove Sections

Simply add or remove `<section>` blocks in `index.html` and update the navigation links accordingly.

## 🔧 Advanced Features

### Custom Domain

To use a custom domain (e.g., `www.yourname.com`):

1. Create a file named `CNAME` in your repository
2. Add your domain name to it (e.g., `www.yourname.com`)
3. Configure your domain's DNS settings to point to GitHub Pages:
   - Add an A record pointing to: `185.199.108.153`
   - Add a CNAME record from `www` to `your-username.github.io`

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Feel free to fork this project and customize it for your own use!

---

Built with ❤️ using HTML, CSS, and JavaScript
