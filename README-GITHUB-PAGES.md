# LLG Media Center - GitHub Pages Landing Page

This directory contains the landing page for LLG Media Center, designed to be hosted on GitHub Pages.

## 🚀 Features

- **Modern Responsive Design**: Built with Tailwind CSS for optimal viewing on all devices
- **Single Page Application**: Smooth scrolling navigation with interactive elements
- **SEO Optimized**: Meta tags, structured data, and semantic HTML
- **Fast Loading**: Optimized assets and minimal dependencies
- **Accessibility**: WCAG compliant with proper ARIA labels and keyboard navigation

## 📁 File Structure

```
├── index.html              # Main landing page
├── 404.html                # Custom 404 error page
├── .github/
│   └── workflows/
│       └── deploy.yml      # GitHub Pages deployment workflow
└── README-GITHUB-PAGES.md  # This file
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and modern web standards
- **Tailwind CSS**: Utility-first CSS framework for styling
- **Font Awesome**: Icon library for UI elements
- **Vanilla JavaScript**: Interactive features and animations
- **GitHub Actions**: Automated deployment pipeline

## 🌐 Deployment

### Automatic Deployment (Recommended)

The site is configured for automatic deployment to GitHub Pages via GitHub Actions:

1. Push changes to the `main` branch
2. GitHub Actions will automatically build and deploy the site
3. Visit `https://ahmed19maher9.github.io/llg-mc/` to view the live site

### Manual Deployment

To deploy manually:

1. Go to repository Settings
2. Navigate to Pages section
3. Select source as "Deploy from a branch"
4. Choose `main` branch and `/ (root)` folder
5. Save and wait for deployment

## 🎨 Customization

### Colors and Branding

The primary color scheme uses purple gradients. To customize:

```css
/* Update these CSS variables in index.html */
.hero-gradient {
    background: linear-gradient(135deg, #your-color-1 0%, #your-color-2 50%, #your-color-3 100%);
}
```

### Content Updates

Key sections to customize:

- **Hero Section**: Update the main value proposition and app screenshot
- **Features**: Modify feature descriptions and icons
- **Pricing**: Update pricing tiers and feature lists
- **Download**: Update system requirements and installation instructions

### Adding New Sections

1. Add a new section in the HTML body
2. Update the navigation menu with the new link
3. Add corresponding styles if needed
4. Update the JavaScript for smooth scrolling

## 📱 Responsive Design

The site is fully responsive with breakpoints:

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🚀 Performance Optimization

- **Lazy Loading**: Images load as needed
- **Minified Assets**: CSS and JS are optimized
- **CDN Delivery**: External resources served from fast CDNs
- **Caching**: Proper cache headers for static assets

## 🔍 SEO Features

- **Meta Tags**: Complete Open Graph and Twitter Card support
- **Structured Data**: JSON-LD for better search engine understanding
- **Semantic HTML**: Proper heading hierarchy and landmark elements
- **Alt Text**: All images have descriptive alt attributes

## 🌍 Browser Support

- **Modern Browsers**: Chrome, Firefox, Safari, Edge (latest versions)
- **Mobile Browsers**: iOS Safari, Chrome Mobile, Samsung Internet
- **Progressive Enhancement**: Works with JavaScript disabled

## 🐛 Troubleshooting

### Common Issues

1. **GitHub Pages 404 Error**
   - Ensure the repository name matches the expected URL
   - Check that GitHub Pages is enabled in repository settings
   - Verify the deployment workflow completed successfully

2. **Styles Not Loading**
   - Check that Tailwind CSS CDN is accessible
   - Verify no CSS syntax errors in custom styles
   - Clear browser cache and reload

3. **JavaScript Errors**
   - Check browser console for error messages
   - Verify all external scripts are loading correctly
   - Test with browser dev tools

### Debug Mode

To enable debug mode, add `?debug=true` to the URL. This will:

- Add visual outlines to all elements
- Log navigation events to console
- Display performance metrics

## 📈 Analytics

To add analytics:

1. Update the `<head>` section with your tracking code
2. Add event tracking for download buttons
3. Monitor page performance and user behavior

## 🤝 Contributing

To contribute to the landing page:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally
5. Submit a pull request

## 📄 License

This landing page is licensed under the same AGPL v3 license as the main LLG Media Center project.

---

**LLG Media Center** - Your comprehensive media solution for video, audio, books, and web content.
