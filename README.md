# Peaceful Monster Website

A modern, responsive website built with HTML, CSS, and JavaScript, designed to be deployed on GitHub Pages.

## Features

- 🎨 Modern and responsive design
- 📱 Mobile-friendly navigation
- ✨ Smooth animations and transitions
- 🎯 Interactive elements
- 📧 Contact form with validation
- 🚀 Optimized for performance
- 🌐 Ready for GitHub Pages deployment

## File Structure

```
Peacfulmonster.website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── README.md           # This file
└── .gitattributes      # Git attributes
```

## Getting Started

### Local Development

1. Clone or download this repository
2. Open `index.html` in your web browser
3. The website should load with all features working

### Deploying to GitHub Pages

#### Method 1: Using GitHub Repository

1. **Create a new repository on GitHub**
   - Go to [GitHub](https://github.com)
   - Click "New repository"
   - Name it `yourusername.github.io` (replace `yourusername` with your actual GitHub username)
   - Make it public
   - Don't initialize with README (since we already have one)

2. **Push your code to GitHub**
   ```bash
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click "Settings"
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Your website will be available at:**
   `https://yourusername.github.io`

#### Method 2: Using a Custom Repository Name

1. **Create a repository with any name**
   - Follow the same steps as above, but use any repository name you want

2. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Save

3. **Your website will be available at:**
   `https://yourusername.github.io/repository-name`

## Customization

### Changing Content

- **Title and Brand**: Update the `<title>` tag and "Peaceful Monster" text in `index.html`
- **Hero Section**: Modify the hero title, subtitle, and buttons in the hero section
- **About Section**: Update the about text and statistics
- **Services**: Add, remove, or modify service cards
- **Contact Information**: Update email, phone, and location details
- **Social Links**: Replace the placeholder social media links with your actual profiles

### Styling

- **Colors**: The main color scheme uses purple (`#6366f1`) and indigo (`#8b5cf6`)
- **Fonts**: The website uses Inter font from Google Fonts
- **Layout**: The design is responsive and uses CSS Grid and Flexbox

### Adding New Sections

1. Add the HTML structure in `index.html`
2. Add corresponding CSS styles in `styles.css`
3. Add any JavaScript functionality in `script.js`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Features

- Optimized images and icons using Font Awesome
- Minimal JavaScript for fast loading
- CSS animations for smooth interactions
- Responsive design for all devices

## Troubleshooting

### Common Issues

1. **Website not loading on GitHub Pages**
   - Make sure the repository is public
   - Check that GitHub Pages is enabled in repository settings
   - Wait a few minutes for the first deployment

2. **Styles not loading**
   - Check that `styles.css` is in the same directory as `index.html`
   - Verify the file path in the HTML link tag

3. **JavaScript not working**
   - Check that `script.js` is in the same directory as `index.html`
   - Open browser developer tools to check for errors

### Getting Help

If you encounter any issues:
1. Check the browser's developer console for error messages
2. Verify all files are properly committed and pushed to GitHub
3. Ensure GitHub Pages is properly configured

## License

This project is open source and available under the [MIT License](LICENSE).

## Contributing

Feel free to fork this project and customize it for your own needs. If you make improvements, consider sharing them with the community!

---

**Happy coding! 🚀** 