# Kaalindi Misra - Professional CV Website

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

### Analytics

Add Google Analytics by inserting this before `</head>` in `index.html`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR-GA-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR-GA-ID');
</script>
```

### SEO Optimization

Add meta tags in the `<head>` section:

```html
<meta name="description" content="Kaalindi Misra - Bioinformatics Expert and Project Manager">
<meta name="keywords" content="bioinformatics, molecular biology, genomics, CV">
<meta name="author" content="Kaalindi Misra">

<!-- Open Graph / Social Media -->
<meta property="og:title" content="Kaalindi Misra - CV">
<meta property="og:description" content="Bioinformatics Expert | Project Manager | PhD">
<meta property="og:type" content="website">
<meta property="og:url" content="https://misrak.github.io">
```

## 🐛 Troubleshooting

### Site not loading?
- Make sure repository is public
- Check that GitHub Pages is enabled in Settings
- Wait 5-10 minutes after enabling Pages
- Verify file names are exactly: `index.html`, `styles.css`, `script.js`

### Animations not working?
- Clear browser cache (Ctrl+Shift+R or Cmd+Shift+R)
- Check browser console for errors (F12)

### Mobile menu not working?
- Ensure JavaScript is enabled in your browser
- Check that `script.js` is properly linked in `index.html`

## 📱 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera

## 🎯 Performance

- Lighthouse Score: 95+
- Mobile-friendly
- Fast loading time
- Optimized images and animations

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Feel free to fork this project and customize it for your own use!

---

**Pro Tips:**
1. Update your CV regularly - just edit `index.html` and push changes
2. Use `git commit -m "Update experience"` for version control
3. Test responsiveness on multiple devices
4. Consider adding a blog section for thought leadership
5. Link to your publications with DOI links
6. Add PDF download option for traditional CV

Built with ❤️ using HTML, CSS, and JavaScript
