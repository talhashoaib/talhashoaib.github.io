# Talha Shoaib - Portfolio Website

A modern, responsive portfolio website showcasing my experience as a Ruby on Rails Engineer.

## 🚀 Quick Start

### Deploying to GitHub Pages (Free Hosting)

1. **Create a GitHub Repository**
   - Go to [GitHub](https://github.com) and sign in
   - Click the "+" icon in the top right and select "New repository"
   - Name it `[your-username].github.io` (e.g., `talhashoaib27.github.io`)
   - Make sure it's set to "Public"
   - Don't initialize with README (we already have one)
   - Click "Create repository"

2. **Upload Your Portfolio Files**
   
   Option A: Using GitHub Web Interface
   - Click "uploading an existing file" on the repository page
   - Drag and drop all files from the `talha-portfolio` folder
   - Write a commit message like "Initial portfolio upload"
   - Click "Commit changes"

   Option B: Using Git Commands
   ```bash
   cd talha-portfolio
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/[your-username]/[your-username].github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click "Settings" tab
   - Scroll down to "Pages" section in the left sidebar
   - Under "Source", select "Deploy from a branch"
   - Under "Branch", select "main" and "/ (root)"
   - Click "Save"

4. **Access Your Live Website**
   - Your site will be available at: `https://[your-username].github.io`
   - It may take a few minutes (up to 10) for the site to go live
   - Check the "Actions" tab in your repository to see deployment status

## 📁 Project Structure

```
talha-portfolio/
├── index.html          # Main HTML file
├── css/
│   └── style.css      # Styling
├── js/
│   └── script.js      # Interactive features
├── images/            # Images folder (currently empty)
└── README.md          # This file
```

## 🎨 Customization

### Update Personal Information
Edit `index.html` to update:
- Name and title
- Professional summary
- Work experience
- Projects
- Contact information

### Change Colors
Edit `css/style.css` and modify the CSS variables at the top:
```css
:root {
    --primary-color: #dc2626;    /* Red - change to your preferred color */
    --secondary-color: #1e293b;   /* Dark blue */
    /* ... other colors ... */
}
```

### Add Your Photo
1. Add your professional photo to the `images/` folder
2. Update the HTML to include an `<img>` tag where needed

### Add More Projects
In `index.html`, find the projects section and add new project cards following the existing pattern.

## 🔧 Features

- ✅ Fully responsive design
- ✅ Smooth scrolling navigation
- ✅ Mobile-friendly hamburger menu
- ✅ Typing animation effect
- ✅ Scroll animations
- ✅ Modern, clean design
- ✅ Fast loading
- ✅ SEO friendly

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🤝 Need Help?

If you encounter any issues:
1. Check that all files are uploaded correctly
2. Ensure GitHub Pages is enabled in settings
3. Clear your browser cache if changes don't appear
4. Wait a few minutes for GitHub Pages to deploy

## 📄 License

This portfolio template is free to use. Feel free to customize it for your needs!

---

Built with ❤️ using HTML, CSS, and JavaScript