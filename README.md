# النسب النبوي الشريف · رحلة عبر الأجداد

> An interactive journey through the noble lineage of Prophet Muhammad ﷺ

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Language](https://img.shields.io/badge/language-Arabic-red.svg)

## 📖 Overview

This is an interactive web experience that presents the noble lineage (النسب النبوي الشريف) of Prophet Muhammad ﷺ in a visually stunning and engaging format. The journey spans from Prophet Ibrahim (Abraham) عليه السلام through generations of ancestors, culminating in the birth of the final Prophet ﷺ.

### ✨ Features

- **Immersive Design**: Elegant Arabic typography with parchment and dark themes
- **Interactive Navigation**: Chapter-based navigation with smooth scrolling
- **Visual Storytelling**: Family tree visualization and artwork frames
- **Responsive Layout**: Fully responsive design for all devices
- **SEO Optimized**: Complete meta tags, Open Graph, Twitter Cards, and structured data
- **PWA Ready**: Progressive Web App support for app-like experience
- **Accessibility**: RTL (Right-to-Left) support for Arabic content
- **Mouse Drag**: Drag to scroll horizontally through governance cards

## 🚀 Live Demo

Visit the live site: [https://eslamabdallah74.github.io/sera/](https://eslamabdallah74.github.io/sera/)

## 📁 Project Structure

```
.
├── index.html               # Main HTML file (renamed from nasab-story.html)
├── favicon.svg             # SVG favicon with gold design
├── og-image.svg            # Open Graph social media image
├── manifest.json           # PWA manifest
├── browserconfig.xml       # Windows tile configuration
├── robots.txt             # Search engine directives
├── sitemap.xml            # XML sitemap
├── SEO-SETUP-GUIDE.md    # SEO setup instructions
└── README.md              # This file
```

## 🎨 Design System

### Color Palette

| Color Name | Hex Code | Usage |
|------------|----------|-------|
| Ink | `#0C0A06` | Background, dark sections |
| Parchment | `#F5ECD7` | Light backgrounds |
| Gold | `#B8860B` | Primary accent, borders |
| Gold Light | `#D4A843` | Secondary accent |
| Gold Extra Light | `#F0CC70` | Highlights, text |
| Red | `#8B1A1A` | Accent color |
| Teal | `#1A4A3A` | Secondary accent |

### Typography

- **Primary**: 'Scheherazade New' - Headings and Arabic text
- **Secondary**: 'Amiri' - Italic text and quotes
- **Tertiary**: 'Cairo' - UI elements and body text

## 🔧 Configuration

### GitHub Pages Setup

The site is already configured for GitHub Pages:

1. Repository: `eslamabdallah74/sera`
2. URL: `https://eslamabdallah74.github.io/sera/`
3. Main file: `index.html`

### Adding Additional Favicon Sizes

The main `favicon.svg` is created. To generate additional favicon sizes:

**Option 1: Online Generator**
1. Visit [RealFaviconGenerator](https://realfavicongenerator.net/)
2. Upload `favicon.svg`
3. Download all generated files
4. Place them in your repository root

**Option 2: Command Line (ImageMagick)**
```bash
convert favicon.svg -resize 16x16 favicon-16x16.png
convert favicon.svg -resize 32x32 favicon-32x32.png
convert favicon.svg -resize 96x96 favicon-96x96.png
convert favicon.svg -resize 180x180 apple-icon-180x180.png
convert favicon.svg -resize 192x192 android-icon-192x192.png
convert favicon.svg -resize 512x512 android-icon-512x512.png
convert favicon.svg -resize 32x32 favicon.ico
```

### Required Favicon Files (Optional)

```
favicon.ico
favicon-16x16.png
favicon-32x32.png
favicon-96x96.png
favicon.svg (already created)
apple-icon-57x57.png
apple-icon-60x60.png
apple-icon-72x72.png
apple-icon-76x76.png
apple-icon-114x114.png
apple-icon-120x120.png
apple-icon-144x144.png
apple-icon-152x152.png
apple-icon-180x180.png
android-icon-192x192.png
android-icon-512x512.png
mstile-70x70.png
mstile-144x144.png
mstile-150x150.png
mstile-310x310.png
mstile-310x150.png
```

## 🔍 SEO Features

### Meta Tags

- **Title**: Optimized with keywords
- **Description**: Compelling 160+ character description
- **Keywords**: Relevant Arabic and English terms
- **Robots**: Proper indexing directives
- **Language**: Arabic (ar)

### Open Graph Tags

Complete Facebook/LinkedIn sharing support with:
- Type, URL, title, description
- Image (SVG format)
- Locale (Arabic + English)
- Site name

### Twitter Cards

Full Twitter Card support:
- Card type: summary_large_image
- URL, title, description, image
- SVG image format

### Structured Data (JSON-LD)

Three types of schema markup:

1. **WebPage**: General page information
2. **Article**: Content-specific markup
3. **BreadcrumbList**: Navigation structure
4. **Person**: Detailed ancestor information

### Additional SEO Elements

- Canonical URL
- Sitemap.xml
- Robots.txt
- PWA manifest
- Theme color
- Mobile optimization

## 📱 Mobile Optimization

The site is fully responsive with:

- Responsive viewport meta tag
- Touch-friendly navigation
- Mobile-specific chapNav positioning (fixed to right edge)
- PWA manifest for app-like experience
- Optimized font loading
- Mouse drag support for horizontal scrolling

## 🧪 Testing

### SEO Testing Tools

- **Meta Tags**: [metatags.io](https://metatags.io/)
- **Structured Data**: [Google Rich Results Test](https://search.google.com/test/rich-results)
- **Twitter Cards**: [Twitter Card Validator](https://cards-dev.twitter.com/validator)
- **Facebook Sharing**: [Facebook Sharing Debugger](https://developers.facebook.com/tools/debug/)
- **Favicon**: [RealFaviconGenerator Checker](https://realfavicongenerator.net/favicon_checker)

### Browser Testing

Test on:
- Chrome (Desktop & Mobile)
- Firefox (Desktop & Mobile)
- Safari (Desktop & Mobile)
- Edge (Desktop & Mobile)

## 🚀 Deployment

### GitHub Pages (Already Deployed)

The site is already deployed at: [https://eslamabdallah74.github.io/sera/](https://eslamabdallah74.github.io/sera/)

To update:
1. Make changes to files
2. Commit and push to GitHub
3. GitHub Pages will automatically deploy

### Custom Domain

To use a custom domain:

1. Update all URLs in `index.html`
2. Update `sitemap.xml` with your domain
3. Update `manifest.json` with your domain
4. Configure DNS for your custom domain
5. Update GitHub Pages settings

## 📊 Performance Optimization

### Image Optimization

- Compress images before uploading
- Use WebP format when possible
- Implement lazy loading
- Use CDN for faster delivery

### Code Optimization

- Minify HTML, CSS, and JavaScript
- Enable Gzip compression
- Use browser caching
- Implement CDN

### Recommended Tools

- **Image Compression**: [TinyPNG](https://tinypng.com/), [Squoosh](https://squoosh.app/)
- **Minification**: [HTMLMinifier](https://kangax.github.io/html-minifier/)
- **Performance**: [Google PageSpeed Insights](https://pagespeed.web.dev/)

## 🎯 Interactive Features

### Mouse Drag Scrolling

The governance cards section (`.gov-scroll`) supports mouse drag scrolling:

- Click and drag left/right to scroll
- Visual feedback with cursor changes
- Smooth scrolling experience
- Touch-friendly for mobile devices

### Chapter Navigation

- Fixed navigation dots on the right side
- Click to jump to specific chapters
- Hover shows chapter labels
- Active state indication

### Family Tree

- Interactive family tree visualization
- Click on nodes to see details
- Animated hover effects
- Color-coded relationships

## 🤝 Contributing

Contributions are welcome! Please follow these guidelines:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Design inspired by traditional Islamic art and calligraphy
- Fonts from Google Fonts (Scheherazade New, Amiri, Cairo)
- Built with modern web standards

## 📞 Support

For questions, issues, or suggestions:

- Open an issue on GitHub
- Contact: [your-email@example.com]

## 🔗 Resources

- [Google SEO Starter Guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide)
- [Open Graph Protocol](https://ogp.me/)
- [Twitter Card Documentation](https://developer.twitter.com/en/docs/twitter-for-websites/cards/overview/abouts-cards)
- [Schema.org](https://schema.org/)
- [PWA Best Practices](https://web.dev/progressive-web-apps/)

## 📸 Screenshots

The site features:

- Elegant dark and parchment alternating themes
- Gold accent colors throughout
- Arabic calligraphy and typography
- Interactive family tree visualization
- Governance system cards with drag-to-scroll
- Smooth animations and transitions

---

**Made with ❤️ for the noble lineage of Prophet Muhammad ﷺ**

> "إِنَّ اللَّهَ اصْطَفَى آدَمَ وَنُوحًا وَآلَ إِبْرَاهِيمَ وَآلَ عِمْرَانَ عَلَى الْعَالَمِينَ"
> 
> "Indeed, Allah chose Adam and Noah and the family of Abraham and the family of 'Imran over the worlds"
> — Quran 3:33
