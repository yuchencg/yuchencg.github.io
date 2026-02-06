# Portfolio Website for GitHub Pages

A clean, professional portfolio website template inspired by academic portfolio designs. Features sections for About, Blog, Portfolio/Art Gallery, and CV.

## 🚀 Quick Start

### 1. Set Up GitHub Pages

1. Create a new repository on GitHub named `username.github.io` (replace `username` with your GitHub username)
2. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/username/username.github.io.git
   cd username.github.io
   ```

3. Copy all the files from this template into your repository

4. Push to GitHub:
   ```bash
   git add .
   git commit -m "Initial portfolio setup"
   git push origin main
   ```

5. Enable GitHub Pages:
   - Go to your repository on GitHub
   - Click "Settings" → "Pages"
   - Under "Source", select "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder
   - Click "Save"

6. Your site will be live at `https://username.github.io` in a few minutes!

## 📁 File Structure

```
username.github.io/
├── index.html              # About/Home page
├── blog.html               # Blog listing page
├── portfolio.html          # Portfolio/Art gallery
├── cv.html                 # CV page
├── styles.css              # All styling
├── script.js               # JavaScript for interactions
├── blog-posts/
│   ├── post1.html         # Individual blog post template
│   ├── post2.html         # (create more as needed)
│   └── post3.html
├── images/
│   ├── profile.jpg        # Your profile photo
│   ├── project1.jpg       # Portfolio images
│   ├── project2.jpg
│   └── ...
├── documents/
│   └── cv.pdf             # Downloadable CV
└── README.md              # This file
```

## ✏️ Customization Guide

### 1. Update Your Information

**index.html (About page):**
- Replace "Your Name" with your actual name
- Update the bio sections with your information
- Add your email and social media links
- Replace placeholder text with your background

**blog.html:**
- Update blog post titles and excerpts
- Create corresponding HTML files in `blog-posts/` folder

**portfolio.html:**
- Update project titles and descriptions
- Replace image placeholders with your work

**cv.html:**
- Fill in your education, experience, publications
- Update skills and achievements

### 2. Add Your Images

Create an `images/` folder and add:
- `profile.jpg` - Your professional photo (recommended: 400-800px wide)
- `project1.jpg`, `project2.jpg`, etc. - Portfolio images
- Any blog post images

Supported formats: JPG, PNG, WebP

### 3. Customize Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #1a1a1a;      /* Main text color */
    --accent-color: #2c5282;       /* Links and accents */
    --background-color: #ffffff;   /* Page background */
    /* ... more variables */
}
```

### 4. Add Blog Posts

1. Copy `blog-posts/post1.html` as a template
2. Update the content, title, and date
3. Add a link to it in `blog.html`
4. Add images to `images/` folder if needed

### 5. Add Portfolio Projects

In `portfolio.html`, duplicate the `.portfolio-item` div:

```html
<div class="portfolio-item">
    <div class="portfolio-image">
        <img src="images/your-project.jpg" alt="Project name">
    </div>
    <div class="portfolio-info">
        <h3>Project Title</h3>
        <p class="portfolio-category">Category: Type</p>
        <p>Description of your project...</p>
    </div>
</div>
```

## 🎨 Features

- **Responsive Design**: Works on desktop, tablet, and mobile
- **Clean Layout**: Professional, academic-style design
- **Easy Navigation**: Sticky header with smooth scrolling
- **Mobile Menu**: Hamburger menu for mobile devices
- **Fade Animations**: Smooth scroll animations
- **SEO Friendly**: Semantic HTML structure

## 📱 Mobile Optimization

The site is fully responsive with:
- Collapsible mobile navigation menu
- Optimized layouts for all screen sizes
- Touch-friendly buttons and links
- Readable typography on small screens

## 🔧 Advanced Customization

### Change Fonts

Add custom fonts using Google Fonts. In the `<head>` of your HTML files:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Your+Font&display=swap" rel="stylesheet">
```

Then update the CSS:

```css
body {
    font-family: 'Your Font', sans-serif;
}
```

### Add Google Analytics

Add this before the closing `</head>` tag:

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

### Add a Contact Form

Consider using:
- [Formspree](https://formspree.io/) - Free contact forms
- [Netlify Forms](https://www.netlify.com/products/forms/) - If hosting on Netlify
- [Google Forms](https://www.google.com/forms/) - Embed a form

## 🐛 Troubleshooting

**Site not showing up?**
- Wait 5-10 minutes after first push
- Check Settings → Pages to ensure it's enabled
- Ensure your repository is named `username.github.io`

**Images not loading?**
- Check file paths are correct (case-sensitive)
- Ensure images are in the correct folder
- Try hard refresh: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)

**CSS not applying?**
- Clear browser cache
- Check that `styles.css` is in the root directory
- Verify the `<link>` tag in HTML is correct

## 📝 Content Tips

### Writing Good Blog Posts
- Use clear, descriptive titles
- Break content into short paragraphs
- Add relevant images
- Include subheadings for longer posts
- Proofread before publishing

### Showcasing Portfolio Work
- Use high-quality images (but optimize file size)
- Write clear descriptions of each project
- Mention tools/technologies used
- Link to live demos or GitHub repos if applicable

### CV Best Practices
- Keep formatting consistent
- Use reverse chronological order
- Include PDF download link
- Update regularly

## 🚀 Going Further

### Custom Domain
1. Buy a domain from a registrar (Namecheap, Google Domains, etc.)
2. In GitHub repo settings, add your custom domain
3. Configure DNS settings with your registrar
4. Wait for DNS propagation (up to 24-48 hours)

### Add More Features
- Comments section (Disqus, utterances)
- Search functionality
- Dark mode toggle
- RSS feed for blog
- Social media sharing buttons

## 📚 Resources

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Markdown Guide](https://www.markdownguide.org/)
- [HTML & CSS Tutorial](https://www.w3schools.com/)
- [Web Accessibility Guidelines](https://www.w3.org/WAI/WCAG21/quickref/)

## 📄 License

This template is free to use for your personal portfolio. No attribution required.

## 🤝 Support

If you encounter issues:
1. Check the GitHub Pages documentation
2. Verify all file paths are correct
3. Ensure your repository is public
4. Check browser console for errors (F12)

---

**Good luck with your portfolio! 🎉**
