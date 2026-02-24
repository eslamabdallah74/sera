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

## 🚀 Quick Start

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A web server (Apache, Nginx, or any static hosting service)

### Installation

1. Clone or download this repository
2. Place all files in your web server's public directory
3. Open `nasab-story.html` in your browser

```bash
# Using a simple Python server
python -m http.server 8000

# Using Node.js http-server
npx http-server -p 8000
```

Then visit: `http://localhost:8000/nasab-story.html`

## 📁 Project Structure

```
.
├── nasab-story.html          # Main HTML file
├── favicon.svg              # SVG favicon
├── manifest.json            # PWA manifest
├── browserconfig.xml        # Windows tile configuration
├── robots.txt               # Search engine directives
├── sitemap.xml              # XML sitemap
├── SEO-SETUP-GUIDE.md       # SEO setup instructions
└── README.md                # This file
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

### Updating URLs

Replace all placeholder URLs in `nasab-story.html`:

```html
<!-- Replace with your actual domain -->
https://yourwebsite.com/nasab-story.html
https://yourwebsite.com/images/og-image.jpg
https://yourwebsite.com/images/twitter-image.jpg
https://yourwebsite.com/logo.png
```

### Updating Twitter Handle

```html
<meta name="twitter:site" content="@yourusername">
<meta name="twitter:creator" content="@yourusername">
```

### Creating Favicon Images

Use the provided `favicon.svg` as a base to generate other formats:

**Option 1: Online Generator**
1. Visit [RealFaviconGenerator](https://realfavicongenerator.net/)
2. Upload `favicon.svg`
3. Download all generated files
4. Place them in your root directory

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

### Required Favicon Files

```
favicon.ico
favicon-16x16.png
favicon-32x32.png
favicon-96x96.png
favicon.svg
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
- Image (1200x630px recommended)
- Locale (Arabic + English)
- Site name

### Twitter Cards

Full Twitter Card support:
- Card type: summary_large_image
- URL, title, description, image
- Site and creator handles

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
- Mobile-specific chapNav positioning
- PWA manifest for app-like experience
- Optimized font loading

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

### Static Hosting

Deploy to any static hosting service:

- **Netlify**: Drag and drop the folder
- **Vercel**: Connect your repository
- **GitHub Pages**: Push to a repository
- **Cloudflare Pages**: Connect your repository
- **AWS S3**: Upload to a bucket

### Custom Domain

1. Update all URLs in `nasab-story.html`
2. Update `sitemap.xml` with your domain
3. Update `manifest.json` with your domain
4. Configure DNS for your custom domain

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

---

**Made with ❤️ for the noble lineage of Prophet Muhammad ﷺ**

> "إِنَّ اللَّهَ اصْطَفَى آدَمَ وَنُوحًا وَآلَ إِبْرَاهِيمَ وَآلَ عِمْرَانَ عَلَى الْعَالَمِينَ"
> 
> "Indeed, Allah chose Adam and Noah and the family of Abraham and the family of 'Imran over the worlds"
> — Quran 3:33
