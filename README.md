# CaptureLife Photography Website

A modern, responsive photography website designed for wedding, pre-wedding, birthday, party, drone, and candid photography services.

## 🌟 Features

### Photography Services Showcase
- **Wedding Photography** - Complete wedding day coverage
- **Pre-Wedding Shoots** - Romantic engagement sessions
- **Birthday Celebrations** - Fun party photography
- **Party & Event Photography** - Corporate and social events
- **Drone Photography** (Featured Specialty) - Aerial perspectives
- **Candid Photography** - Natural, unposed moments

### Modern Design & UX
- ✨ Beautiful modern design with golden color scheme
- 📱 Fully responsive (mobile, tablet, desktop)
- 🎨 Smooth animations and hover effects
- 🚀 Fast loading and optimized performance
- 🎯 Professional typography with Google Fonts

### Interactive Features
- 🔍 Portfolio filtering by photography type
- 📧 Contact form with validation
- 📱 Mobile-friendly navigation
- 🖼️ Gallery modal for portfolio items
- ⬆️ Scroll-to-top button
- 📬 Notification system for form feedback

### Technical Features
- 🎭 CSS Grid and Flexbox layouts
- 🎨 CSS Custom Properties (CSS Variables)
- 📱 Mobile-first responsive design
- ⚡ Vanilla JavaScript (no dependencies)
- 🎬 Scroll animations with Intersection Observer
- 🌟 Modern browser features (CSS backdrop-filter, etc.)

## 🚀 Quick Start

1. **Download/Clone the files**
   ```bash
   # If using git
   git clone <repository-url>
   
   # Or download the files manually
   ```

2. **Open the website**
   - Simply open `index.html` in your web browser
   - Or use a local server for development:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

3. **View your website**
   - Open `http://localhost:8000` in your browser (if using local server)
   - Or just double-click `index.html`

## 📁 File Structure

```
photography-website/
├── index.html          # Main HTML file
├── styles.css          # All CSS styling
├── script.js           # JavaScript functionality
├── README.md           # This file
└── images/             # (Create this folder for your photos)
    ├── hero/
    ├── portfolio/
    ├── about/
    └── thumbnails/
```

## 🎨 Customization Guide

### 1. Update Business Information

**Replace placeholder content in `index.html`:**

```html
<!-- Update business name -->
<h2>Your Business Name</h2>

<!-- Update contact information -->
<p>+1 (555) 123-4567</p>
<p>hello@yourbusiness.com</p>
<p>Your City, State</p>

<!-- Update social media links -->
<a href="https://instagram.com/yourbusiness">
```

### 2. Color Scheme

**Modify colors in `styles.css`:**

```css
:root {
    --primary-color: #D4AF37;     /* Change main gold color */
    --secondary-color: #2C2C2C;   /* Change dark color */
    --accent-color: #8B6914;      /* Change accent color */
}
```

### 3. Add Your Photos

**Create folder structure:**
```
images/
├── hero-image.jpg              # Main hero image (1920x1080)
├── about-photo.jpg             # Your professional photo (800x600)
├── portfolio/
│   ├── wedding-1.jpg           # Portfolio images (1200x800)
│   ├── wedding-2.jpg
│   ├── drone-1.jpg
│   ├── prewedding-1.jpg
│   ├── birthday-1.jpg
│   ├── party-1.jpg
│   └── candid-1.jpg
└── thumbnails/
    ├── wedding-1-thumb.jpg     # Smaller versions (400x300)
    └── ...
```

**Replace placeholder images in HTML:**

```html
<!-- Replace hero placeholder -->
<div class="hero-image">
    <img src="images/hero-image.jpg" alt="Professional Wedding Photography">
</div>

<!-- Replace portfolio placeholders -->
<div class="portfolio-item" data-category="wedding">
    <img src="images/portfolio/wedding-1.jpg" alt="Wedding Photography">
    <div class="portfolio-overlay">
        <h4>Sarah & John's Wedding</h4>
        <p>Wedding Photography</p>
    </div>
</div>
```

### 4. Update Services

**Modify service descriptions in `index.html`:**

```html
<div class="service-card">
    <div class="service-icon">
        <i class="fas fa-heart"></i>
    </div>
    <h3>Your Service Name</h3>
    <p>Your service description...</p>
    <ul class="service-features">
        <li>Your feature 1</li>
        <li>Your feature 2</li>
        <!-- Add more features -->
    </ul>
</div>
```

## 📸 Adding Real Portfolio Images

### Recommended Image Sizes
- **Hero Image**: 1920x1080px (landscape)
- **Portfolio Images**: 1200x800px (4:3 aspect ratio)
- **Thumbnails**: 400x300px (for faster loading)
- **About Photo**: 800x600px (professional headshot)

### Image Optimization Tips
1. **Compress images** for web (70-80% quality)
2. **Use WebP format** for better compression
3. **Create responsive images** with multiple sizes
4. **Add lazy loading** for better performance

### Example: Adding a Wedding Photo

```html
<div class="portfolio-item" data-category="wedding">
    <img src="images/portfolio/sarah-john-wedding.jpg" 
         alt="Sarah and John's Wedding - Outdoor Ceremony"
         loading="lazy">
    <div class="portfolio-overlay">
        <h4>Sarah & John's Wedding</h4>
        <p>Garden Wedding Ceremony</p>
    </div>
</div>
```

## 🎯 SEO Optimization

### 1. Update Meta Tags

```html
<title>Your Business Name - Wedding & Event Photography</title>
<meta name="description" content="Professional wedding, event, and drone photography in Your City. Capturing your special moments with creativity and passion.">
<meta name="keywords" content="wedding photography, drone photography, event photography, your city">
```

### 2. Add Structured Data

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "ProfessionalService",
  "name": "Your Business Name",
  "description": "Professional photography services",
  "telephone": "+1-555-123-4567",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "Your Address",
    "addressLocality": "Your City",
    "addressRegion": "Your State",
    "postalCode": "Your ZIP"
  }
}
</script>
```

## 📱 Mobile Optimization

The website is already mobile-optimized with:
- Responsive grid layouts
- Touch-friendly navigation
- Optimized images
- Fast loading times
- Mobile-first CSS approach

## 🔧 Advanced Customization

### Adding New Sections

```html
<!-- Example: Testimonials Section -->
<section class="testimonials">
    <div class="container">
        <div class="section-header">
            <h2>What Our Clients Say</h2>
        </div>
        <!-- Add testimonial content -->
    </div>
</section>
```

### Custom Animations

```css
/* Add custom animations */
@keyframes yourCustomAnimation {
    from { opacity: 0; transform: scale(0.8); }
    to { opacity: 1; transform: scale(1); }
}

.your-element {
    animation: yourCustomAnimation 0.6s ease-out;
}
```

## 🌐 Deployment

### Option 1: Static Hosting (Recommended)
- **Netlify**: Drag and drop your files
- **Vercel**: Connect your Git repository
- **GitHub Pages**: Host directly from GitHub
- **AWS S3**: Static website hosting

### Option 2: Traditional Web Hosting
- Upload files via FTP to your web host
- Point domain to your hosting directory

## 📞 Support & Customization

### Common Tasks
1. **Changing colors**: Edit CSS variables in `styles.css`
2. **Adding pages**: Create new HTML files and link them
3. **Contact form**: Implement backend processing
4. **SEO**: Add meta tags and structured data
5. **Analytics**: Add Google Analytics or similar

### Browser Support
- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ⚠️ IE 11 (limited support)

## 📋 Checklist for Launch

- [ ] Replace all placeholder text with your content
- [ ] Add your professional photos
- [ ] Update contact information
- [ ] Test contact form
- [ ] Check mobile responsiveness
- [ ] Optimize images for web
- [ ] Add Google Analytics
- [ ] Set up domain and hosting
- [ ] Test on different browsers
- [ ] Submit to search engines

## 🏆 Best Practices

1. **Keep images under 500KB** for fast loading
2. **Update content regularly** to improve SEO
3. **Use descriptive alt text** for all images
4. **Monitor site speed** with tools like PageSpeed Insights
5. **Backup your website** regularly
6. **Keep contact information current**

## 🎉 Ready to Launch!

Your professional photography website is ready to showcase your amazing work and attract new clients. Remember to add your real photos and customize the content to match your brand.

**Happy photographing! 📸**