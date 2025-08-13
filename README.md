# Artyx Marketing Website

A professional, responsive marketing website for the Artyx iOS app featuring AI-powered background replacement technology.

## Overview

This website promotes the Artyx iOS app, showcasing its FLUX.1 Kontext Pro technology for perfect identity-preserving background replacement. The site includes comprehensive information about features, pricing, privacy, and support.

## Design System

The website follows the Artyx iOS app's design system:

- **Colors**: Primary blue (#007AFF), secondary purple (#AF52DE)
- **Typography**: iOS system font stack with semantic weights
- **Spacing**: 4pt grid system (4px, 8px, 12px, 16px, 20px, 24px, 32px)
- **Border Radius**: 6px-16px ranges
- **Components**: iOS-style cards with subtle shadows

## Features

- ✅ Fully responsive design (mobile-first)
- ✅ Dark mode support
- ✅ iOS-style animations and interactions
- ✅ Professional marketing copy
- ✅ SEO optimized
- ✅ Accessibility compliant
- ✅ Fast loading performance
- ✅ Modular CSS architecture

## Pages

1. **Home (index.html)** - Hero section, features, how it works, pricing, download
2. **Privacy Policy (privacy.html)** - Comprehensive privacy information
3. **Terms of Use (terms.html)** - Legal terms and conditions
4. **Contact/Support (contact.html)** - Contact form, FAQ, support options

## File Structure

```
app-website/
├── index.html              # Home page
├── privacy.html             # Privacy policy
├── terms.html              # Terms of use  
├── contact.html            # Contact & support
├── css/
│   ├── style.css          # Main stylesheet (imports)
│   ├── base.css           # Design tokens & base styles
│   ├── components.css     # Component styles
│   ├── layout.css         # Layout & grids
│   └── animations.css     # Animations & transitions
├── js/
│   └── main.js            # JavaScript functionality
├── images/                # Placeholder for images
└── README.md              # This file
```

## CSS Architecture

The CSS is modularly organized:

- **base.css**: Design tokens, CSS variables, typography, base elements
- **components.css**: Buttons, cards, forms, reusable components
- **layout.css**: Navigation, footer, grids, page layouts
- **animations.css**: Transitions, hover effects, loading states
- **style.css**: Main file that imports all modules + page-specific styles

## Key Components

### Design Tokens
```css
--color-primary: #007AFF;
--color-secondary: #AF52DE;
--gradient-primary: linear-gradient(135deg, #007AFF 0%, #AF52DE 100%);
--spacing-lg: 1rem; /* 16px - 4pt grid */
--radius-lg: 12px;
--font-family: -apple-system, BlinkMacSystemFont, 'SF Pro Display', system-ui;
```

### Button System
- `.btn-primary` - Gradient primary button
- `.btn-secondary` - Secondary outlined button  
- `.btn-large` - Larger touch targets
- `.btn-outline` - Transparent with border

### Card Components
- `.feature-card` - Feature showcase cards
- `.pricing-card` - Subscription tier cards
- `.contact-card` - Contact method cards

## JavaScript Features

- Mobile navigation toggle
- Smooth scrolling for anchor links
- Contact form validation and submission
- FAQ accordion functionality
- Scroll-based animations
- Performance monitoring

## Browser Support

- iOS Safari 14+
- Chrome 90+
- Firefox 88+
- Edge 90+
- Safari 14+

## Performance

- Optimized for Core Web Vitals
- Minimal JavaScript dependencies
- Efficient CSS with modular architecture
- Responsive images with proper sizing
- Preloaded critical resources

## SEO Features

- Semantic HTML structure
- Open Graph meta tags
- Structured data markup ready
- Optimized page titles and descriptions
- Fast loading times
- Mobile-first responsive design

## Accessibility

- WCAG 2.1 AA compliant
- Keyboard navigation support
- Screen reader friendly
- High contrast mode support
- Reduced motion preferences
- Semantic markup

## Development

### Local Development

1. Clone the repository
2. Open `index.html` in a browser or use a local server
3. For live reloading, use a simple HTTP server:

```bash
# Python 3
python -m http.server 8000

# Node.js (if you have npx)
npx serve .

# PHP
php -S localhost:8000
```

### Making Changes

1. Edit HTML files directly for content changes
2. Modify CSS files in the `/css` directory
3. Update JavaScript in `/js/main.js`
4. Test across different devices and browsers

### CSS Development

The modular CSS architecture makes it easy to:
- Add new components in `components.css`
- Modify layout in `layout.css`
- Add animations in `animations.css`
- Update design tokens in `base.css`

## Deployment

### Static Hosting (Recommended)

Deploy to any static hosting provider:

**Netlify:**
1. Connect GitHub repository
2. Set build command: (none)
3. Set publish directory: `/app-website`
4. Deploy

**Vercel:**
1. Import project from GitHub
2. Set root directory: `app-website`
3. Deploy

**GitHub Pages:**
1. Enable GitHub Pages in repository settings
2. Set source to `main` branch
3. Set folder to `/app-website`

**AWS S3 + CloudFront:**
1. Create S3 bucket
2. Upload files to bucket
3. Configure CloudFront distribution
4. Set custom domain (optional)

### Domain Configuration

1. Purchase domain (e.g., artyx.app)
2. Configure DNS to point to hosting provider
3. Set up SSL certificate
4. Configure redirects if needed

### CDN Setup (Optional)

For better performance:
1. Set up CloudFlare or similar CDN
2. Configure caching rules
3. Enable compression
4. Optimize images

## Customization

### Updating Content

**Home Page:**
- Modify hero section in `index.html`
- Update feature descriptions
- Change pricing information
- Update download links

**Design:**
- Modify CSS variables in `base.css`
- Update gradients and colors
- Adjust spacing and typography

**Images:**
- Add images to `/images` directory
- Update image references in HTML
- Optimize for web (WebP format recommended)

### Adding New Pages

1. Create new HTML file
2. Copy navigation and footer from existing pages
3. Add page-specific styles if needed
4. Update navigation links

## Contact Information

For questions about this website:
- Email: support@artyx.app
- Technical issues: bugs@artyx.app

## License

This website code is proprietary to Artyx. Unauthorized copying or distribution is prohibited.

---

**Built with ❤️ for the Artyx iOS app launch**