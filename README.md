# Social Sisters Collective Website

A beautiful, build-free static website for Social Sisters Collective, a party decoration company based in Oregon. Features a modern, minimal, feminine design with a nude color palette.

## 🎨 Design Features

- **Modern nude color palette** with carefully selected CSS variables
- **Responsive design** that works on all devices
- **Smooth scrolling** navigation with anchor links
- **Accessible** with proper focus states and semantic HTML
- **SEO optimized** with meta tags and JSON-LD structured data
- **Form handling** with validation and demo mode

## 📁 File Structure

```
/
├── index.html              # Main HTML file
├── assets/
│   ├── styles.css          # All CSS styles
│   ├── app.js             # JavaScript functionality
│   ├── hero.jpg           # Hero section image
│   ├── g1.jpg             # Gallery image 1
│   ├── g2.jpg             # Gallery image 2
│   ├── g3.jpg             # Gallery image 3
│   └── g4.jpg             # Gallery image 4
└── README.md              # This file
```

## 🖼️ Replacing Images

The website currently uses Unsplash placeholder images. To replace them with your own:

1. **Hero Image** (`assets/hero.jpg`):
   - Recommended size: 1920x1080px or larger
   - Format: JPG or WebP
   - Should show elegant party decoration with nude/neutral tones

2. **Gallery Images** (`assets/g1.jpg` through `assets/g4.jpg`):
   - Recommended size: 800x600px or larger
   - Format: JPG or WebP
   - Should showcase your best work with consistent styling

3. **Service Card Images** (currently using Unsplash URLs):
   - Update the `src` attributes in `index.html` for each service card
   - Or save images locally and update paths

## 📧 Setting Up Form Submission

The contact form is currently set to demo mode. To enable real form submission:

1. **Sign up for Formspree** (recommended):
   - Go to [formspree.io](https://formspree.io)
   - Create a new form
   - Copy your form ID
   - Replace `your-id` in the form action URL in `index.html`

2. **Alternative form services**:
   - Netlify Forms (if deploying to Netlify)
   - EmailJS for client-side email sending
   - Custom backend endpoint

3. **Update the form action**:
   ```html
   <!-- Change this line in index.html -->
   <form class="contact-form" action="https://formspree.io/f/YOUR-ACTUAL-ID" method="POST">
   ```

## 🚀 Deployment Options

### Option 1: Netlify (Recommended)
1. Drag and drop the entire folder to [netlify.com/drop](https://netlify.com/drop)
2. Your site will be live instantly
3. Optional: Connect to GitHub for automatic deployments

### Option 2: Vercel
1. Go to [vercel.com](https://vercel.com)
2. Import your project or drag and drop
3. Deploy as a static site

### Option 3: GitHub Pages
1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select source branch and deploy

### Option 4: Any Static Host
- Upload all files to any web hosting service
- No build process required - just upload and go!

## 🎨 Customization

### Colors
All colors are defined as CSS variables in `assets/styles.css`:
```css
:root {
    --bg: #FAF7F4;           /* Background */
    --nude-100: #F7EFEA;     /* Light nude */
    --nude-200: #EEDFD8;     /* Medium nude */
    --nude-300: #E2CFC4;     /* Darker nude */
    --nude-400: #D6BEB1;     /* Darkest nude */
    --accent: #C69C8D;       /* Accent color */
    --accent-700: #B78574;   /* Darker accent */
    --ink: #2E2A27;          /* Text color */
    --white: #FFFFFF;        /* White */
}
```

### Typography
- **Headings**: Playfair Display (Google Fonts)
- **Body text**: Inter (Google Fonts)

### Content Updates
- Edit text content directly in `index.html`
- Update contact information in the footer
- Modify service descriptions and pricing in their respective sections

## 📱 Mobile Optimization

The website is fully responsive with breakpoints at:
- **Desktop**: 1200px and above
- **Tablet**: 920px - 1199px
- **Mobile**: 640px - 919px
- **Small Mobile**: Below 640px

## ♿ Accessibility Features

- Semantic HTML structure
- Proper heading hierarchy
- Alt text on all images
- Focus states for keyboard navigation
- ARIA labels where needed
- Color contrast compliance

## 🔍 SEO Features

- Meta descriptions and Open Graph tags
- JSON-LD structured data for LocalBusiness
- Semantic HTML markup
- Optimized images with alt text
- Fast loading times

## 🛠️ Browser Support

- Chrome/Edge: Full support
- Firefox: Full support
- Safari: Full support
- Mobile browsers: Full support
- Internet Explorer: Not supported (uses modern CSS features)

## 📞 Support

For questions about this website template or customization help, contact the developer or refer to the code comments in each file.

---

**Social Sisters Collective** - Creating beautiful, inclusive party experiences across Oregon with our signature nude aesthetic and attention to detail.
