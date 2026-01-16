# Vasista Behara - DevOps Portfolio

A professional, dark-themed portfolio website built with Jekyll and hosted on GitHub Pages.

## 🚀 Quick Start

### Deploy to GitHub Pages

1. **Push to GitHub:**
   ```bash
   git add .
   git commit -m "Add portfolio website"
   git push origin claude
   ```

2. **Enable GitHub Pages:**
   - Go to repository Settings → Pages
   - Under "Build and deployment", select **GitHub Actions**
   - The site will automatically build and deploy

3. **Access your site:**
   - URL: `https://vasistabehara.github.io`

### Local Development (Requires Ruby 3.0+)

```bash
# Install dependencies
bundle install

# Serve locally
bundle exec jekyll serve

# Open http://localhost:4000
```

> **Note:** If you have Ruby 2.6.x, the local build may not work. GitHub Pages will use its own Ruby 3.x environment, so just push and let the Actions workflow build it.

## 📁 Project Structure

```
├── _config.yml           # Jekyll configuration
├── _layouts/
│   └── default.html      # Base HTML template
├── assets/
│   └── css/
│       └── style.css     # Dark theme styling
├── index.html            # Main portfolio content
├── Gemfile               # Ruby dependencies
├── .github/
│   └── workflows/
│       └── jekyll.yml    # GitHub Actions deployment
└── resume                # Source resume file
```

## ✨ Features

- **Single-page portfolio** with smooth scroll navigation
- **Dark/contrast theme** with cyan accent colors
- **AWS & GCP certification badges** from Credly
- **Responsive design** for all devices
- **GitHub stats integration**
- **Animated sections** with fade-in effects
- **SEO optimized** with meta tags

## 🎨 Customization

### Colors
Edit CSS variables in `assets/css/style.css`:
```css
:root {
  --accent-primary: #06b6d4;    /* Main accent color */
  --bg-primary: #0a0f1a;        /* Background color */
}
```

### Content
Update `index.html` to modify any section content.

## 📄 License

MIT License - Feel free to use this template for your own portfolio!