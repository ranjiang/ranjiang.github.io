# Ran Jiang - Personal Website

A modern, responsive personal website built with HTML, Tailwind CSS, and vanilla JavaScript. Hosted on GitHub Pages.

## Features

- 🎨 Modern, clean design with smooth animations
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Fast loading with CDN-based Tailwind CSS
- 🎯 SEO-friendly with proper meta tags
- 🔗 Easy to customize and extend

## Sections

- **Home**: Introduction and hero section
- **Expertise**: Key areas of focus and skills
- **Blog**: Recent posts and articles
- **Contact**: Social links and contact information

## Deployment to GitHub Pages

This repository is already set up for GitHub Pages. To deploy:

1. Push your changes to the `main` branch (or your default branch)
2. Go to your repository settings on GitHub
3. Navigate to **Settings** → **Pages**
4. Under **Source**, select your branch (usually `main`) and folder (`/ (root)`)
5. Click **Save**
6. Your site will be live at `https://ranjiang.github.io` within a few minutes

## Project Structure

```
ranjiang.github.io/
├── index.html          # Main website file (required at root for GitHub Pages)
├── README.md           # Project documentation
├── package.json        # Node.js dependencies (optional)
├── .gitignore          # Git ignore rules
├── assets/             # Static assets
│   ├── images/         # Images, photos, graphics
│   ├── css/            # Custom CSS files (if needed)
│   └── js/             # JavaScript files (if needed)
├── config/             # Configuration files
│   ├── vite.config.ts  # Vite build config
│   └── postcss.config.mjs # PostCSS config
└── src/                # Source files (if using build tools)
```

## Customization

### Update Personal Information

Edit `index.html` and update:
- Name and bio in the hero section
- Social media links in the footer
- Email address in the contact section
- Profile image (replace the placeholder div with your image)

### Add Your Profile Image

1. Place your image in `assets/images/` (e.g., `assets/images/profile.jpg`)
2. Replace the profile image placeholder in `index.html`:
```html
<div class="w-32 h-32 rounded-full profile-img">
    RJ
</div>
```

With:
```html
<img 
    src="assets/images/profile.jpg" 
    alt="Ran Jiang" 
    class="w-32 h-32 rounded-full object-cover"
>
```

### Update Social Links

Edit the footer section and update the `href` attributes with your actual social media profiles.

## Local Development

Simply open `index.html` in your browser or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## License

This project is open source and available under the MIT License.