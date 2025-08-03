# LeafLogic - AI-Powered Plant Care Robot Website

A modern, responsive website for LeafLogic, showcasing the Botani AI-powered plant care robot. Built with vanilla HTML, CSS, and JavaScript.

## 🌱 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic content
- **Accessibility**: WCAG compliant with keyboard navigation and screen reader support
- **Performance Optimized**: Fast loading with optimized assets and lazy loading
- **Cross-browser Compatible**: Works on all modern browsers

## 📁 Project Structure

```
leaflogic-website/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # All styles and animations
├── js/
│   └── main.js         # Interactive functionality
├── images/             # Website images and assets
└── README.md          # This file
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, but recommended)

### Installation

1. **Download the files**
   - All website files are in the `leaflogic-website` folder
   - Copy the entire folder to your desired location

2. **Set up a local server** (recommended)
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have it installed)
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

3. **Open in browser**
   - Navigate to `http://localhost:8000` (if using a server)
   - Or simply double-click `index.html` to open directly

## 🎨 Customization

### Colors
The website uses CSS custom properties for easy color customization. Edit the `:root` section in `css/styles.css`:

```css
:root {
    --primary: #10b981;      /* Main brand color */
    --accent: #f59e0b;       /* Accent color */
    --background: #ffffff;   /* Background color */
    --foreground: #1f2937;   /* Text color */
    /* ... more colors */
}
```

### Content
- **Text Content**: Edit the HTML directly in `index.html`
- **Images**: Replace images in the `images/` folder
- **Styling**: Modify `css/styles.css` for layout and design changes
- **Functionality**: Update `js/main.js` for interactive features

### Adding New Sections
1. Add the HTML structure to `index.html`
2. Add corresponding styles to `css/styles.css`
3. Add any JavaScript functionality to `js/main.js`

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🌐 Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 📈 Performance

The website is optimized for performance with:
- Minified CSS and JavaScript
- Optimized images
- Lazy loading for images
- Efficient animations
- Minimal external dependencies

## 🔧 Development

### Adding New Features

1. **New Page**: Create a new HTML file and link it in the navigation
2. **New Component**: Add HTML structure and corresponding CSS/JS
3. **New Animation**: Add CSS keyframes and JavaScript triggers

### Code Style

- **HTML**: Semantic HTML5 with proper accessibility attributes
- **CSS**: BEM methodology with CSS custom properties
- **JavaScript**: ES6+ with modern browser APIs

## 📧 Contact Information

- **Email**: hello@leaflogic.ai
- **Phone**: +1 (555) 123-4567
- **Address**: University Innovation Lab, Tech Campus

## 🚀 Deployment

### GitHub Pages
1. Create a new GitHub repository
2. Upload all website files
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop the `leaflogic-website` folder to Netlify
2. Your site will be deployed instantly
3. Custom domain can be added in settings

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Navigate to project folder
3. Run `vercel` and follow prompts

### Traditional Hosting
1. Upload all files to your web server
2. Ensure `index.html` is in the root directory
3. Configure server to serve static files

## 🔒 Security

- No sensitive data is stored locally
- All external links open in new tabs
- Form submissions are handled securely
- HTTPS recommended for production

## 📊 Analytics

To add Google Analytics:
1. Get your tracking ID from Google Analytics
2. Add the tracking code to the `<head>` section of `index.html`
3. Update the tracking ID in the code

## 🐛 Troubleshooting

### Common Issues

1. **Images not loading**
   - Check file paths in `images/` folder
   - Ensure image files exist and are named correctly

2. **Styles not applying**
   - Check if `css/styles.css` is linked correctly
   - Clear browser cache

3. **JavaScript not working**
   - Check browser console for errors
   - Ensure `js/main.js` is linked correctly

4. **Mobile menu not working**
   - Check if Lucide icons are loading
   - Verify JavaScript is enabled

### Debug Mode

Add this to the browser console to enable debug mode:
```javascript
localStorage.setItem('debug', 'true');
```

## 📝 License

This project is proprietary to LeafLogic. All rights reserved.

## 🤝 Contributing

For internal team members:
1. Create a feature branch
2. Make your changes
3. Test thoroughly
4. Submit a pull request

## 📞 Support

For technical support or questions:
- Email: hello@leaflogic.ai
- Create an issue in the repository
- Check the troubleshooting section above

---

**Made with ❤️ by the LeafLogic Team**

*Revolutionizing indoor gardening with AI-powered automation* 