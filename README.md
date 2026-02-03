# Areena Salon Website 💇‍♀️

A professional static website for Areena Salon featuring modern design, responsive layout, and clean HTML/CSS architecture. Built with performance and accessibility in mind.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Muhammad-Anique/areena-salon)

## 🌟 Features

- **Responsive Design**: Mobile-first approach with seamless tablet and desktop experiences
- **Modern UI/UX**: Clean, elegant design with professional salon aesthetics
- **Performance Optimized**: Fast loading times with optimized CSS and images
- **Accessibility Compliant**: WCAG guidelines followed for inclusive design
- **SEO Friendly**: Proper meta tags and semantic HTML structure
- **Cross-Browser Compatible**: Works across all modern browsers

## 🚀 Live Demo

Visit the live website: [Areena Salon Website](https://areena-salon.vercel.app)

## 📁 Project Structure

```
areena-salon/
├── index.html              # Main HTML file
├── styles.css              # CSS stylesheet with responsive design
├── assets/                 # Static assets directory
│   └── images/            # Image files
│       └── .gitkeep       # Directory placeholder
├── vercel.json            # Vercel deployment configuration
├── .gitignore             # Git ignore rules
└── README.md              # Project documentation
```

## 🎨 Design System

### Color Palette
- **Primary**: `#8B4B8C` (Elegant Purple)
- **Secondary**: `#D4AF37` (Luxury Gold)
- **Accent**: `#F7E7CE` (Warm Cream)
- **Neutral**: Gray scale from `#F9FAFB` to `#111827`

### Typography
- **Primary Font**: Playfair Display (Serif) - For headings
- **Secondary Font**: Inter (Sans-serif) - For body text

### Spacing System
- **XS**: 0.25rem
- **SM**: 0.5rem
- **MD**: 1rem
- **LG**: 1.5rem
- **XL**: 2rem
- **2XL**: 3rem
- **3XL**: 4rem

## 🛠️ Tech Stack

- **HTML5**: Semantic markup with accessibility features
- **CSS3**: Modern CSS with Grid, Flexbox, and Custom Properties
- **Vanilla JavaScript**: Minimal JS for mobile menu and smooth scrolling
- **Vercel**: Static site hosting and deployment
- **Git**: Version control

## 📱 Responsive Breakpoints

- **Mobile**: `<= 480px`
- **Tablet**: `481px - 768px`
- **Desktop**: `>= 769px`

## 🚀 Quick Start

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/Muhammad-Anique/areena-salon.git
   cd areena-salon
   ```

2. **Open in browser**
   - Simply open `index.html` in your preferred browser
   - Or use a local server (recommended):
   ```bash
   # Using Python
   python -m http.server 3000
   
   # Using Node.js (if you have it installed)
   npx serve .
   ```

3. **View the website**
   - Open `http://localhost:3000` in your browser

### Deployment to Vercel

1. **Deploy directly from GitHub**
   - Visit [Vercel](https://vercel.com)
   - Import your GitHub repository
   - Vercel will automatically detect it as a static site

2. **Deploy with Vercel CLI**
   ```bash
   npm i -g vercel
   vercel
   ```

## 📝 Customization Guide

### Adding Images

1. Add your images to the `assets/images/` directory
2. Update the image references in `index.html`:
   - `hero-salon.jpg` (recommended: 800x500px)
   - `about-salon.jpg` (recommended: 600x400px)

### Updating Content

- **Salon Name**: Update the `<title>` tag and navigation brand
- **Contact Information**: Modify the footer section
- **Services**: Edit the services grid in the HTML
- **Business Hours**: Update the footer hours section

### Styling Changes

All styles are centralized in `styles.css`:
- **Colors**: Update CSS custom properties in `:root`
- **Fonts**: Change the Google Fonts imports in HTML
- **Spacing**: Modify spacing variables in `:root`

## 🎯 Performance Features

- **Optimized CSS**: Mobile-first responsive design
- **Semantic HTML**: Proper document structure
- **Font Optimization**: Preconnect to Google Fonts
- **Image Optimization**: Responsive images with proper sizing
- **Caching**: Vercel configuration for optimal caching

## ♿ Accessibility Features

- **Semantic HTML**: Proper heading hierarchy and landmarks
- **Keyboard Navigation**: Focus states for interactive elements
- **Screen Reader Support**: Proper ARIA labels and alt text
- **Color Contrast**: WCAG AA compliant color ratios
- **Reduced Motion**: Respects user motion preferences

## 🔧 Browser Support

- **Chrome**: Latest 2 versions
- **Firefox**: Latest 2 versions
- **Safari**: Latest 2 versions
- **Edge**: Latest 2 versions

## 📈 SEO Optimization

- **Meta Tags**: Comprehensive meta information
- **Open Graph**: Social media sharing optimization
- **Structured Data**: JSON-LD schema markup ready
- **Sitemap**: Can be easily generated for larger sites

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

Muhammad Anique - [Website](https://www.muhammadanique.com/)

Project Link: [https://github.com/Muhammad-Anique/areena-salon](https://github.com/Muhammad-Anique/areena-salon)

## 🙏 Acknowledgments

- Design inspiration from modern salon websites
- Google Fonts for typography
- Vercel for hosting platform
- Modern CSS techniques and best practices

---

**Built with ❤️ by Muhammad Anique**