# Images Folder Structure

This folder contains all the images for your photography website. Follow this structure to organize your photos properly.

## 📁 Folder Organization

```
images/
├── hero/                   # Main hero/banner images
├── portfolio/              # Portfolio showcase images
├── about/                  # About section photos
├── thumbnails/             # Smaller versions for faster loading
└── README.md              # This file
```

## 📸 Image Requirements

### Hero Images (`hero/`)
- **Purpose**: Main banner/hero section images
- **Size**: 1920x1080px (16:9 aspect ratio)
- **Format**: JPG or WebP
- **File size**: < 500KB (optimized for web)
- **Naming**: `hero-main.jpg`, `hero-wedding.jpg`, etc.

### Portfolio Images (`portfolio/`)
- **Purpose**: Showcase your best work
- **Size**: 1200x800px (3:2 aspect ratio) 
- **Format**: JPG or WebP
- **File size**: < 300KB each
- **Naming**: `wedding-sarah-john.jpg`, `drone-venue-aerial.jpg`, etc.

### About Images (`about/`)
- **Purpose**: Professional photos of you/your team
- **Size**: 800x600px (4:3 aspect ratio)
- **Format**: JPG or WebP
- **File size**: < 200KB
- **Naming**: `photographer-profile.jpg`, `team-photo.jpg`, etc.

### Thumbnails (`thumbnails/`)
- **Purpose**: Quick-loading preview images
- **Size**: 400x300px (4:3 aspect ratio)
- **Format**: JPG or WebP
- **File size**: < 50KB each
- **Naming**: Same as original with `-thumb` suffix

## 🎨 Image Categories for Portfolio

When adding portfolio images, use these categories to match the website filters:

- **wedding** - Wedding ceremony and reception photos
- **prewedding** - Engagement and pre-wedding shoots
- **birthday** - Birthday party celebrations
- **party** - Events, corporate parties, celebrations
- **drone** - Aerial photography and videography
- **candid** - Natural, unposed moments

## 📝 Example File Names

```
hero/
├── hero-main.jpg                 # Main hero image
└── hero-wedding-couple.jpg       # Alternative hero image

portfolio/
├── wedding-sarah-john-ceremony.jpg
├── wedding-mike-emma-reception.jpg
├── prewedding-alex-kate-beach.jpg
├── drone-venue-aerial-view.jpg
├── birthday-princess-party.jpg
├── party-corporate-event.jpg
└── candid-family-moments.jpg

about/
├── photographer-profile.jpg      # Your professional photo
└── behind-the-scenes.jpg        # Optional: you at work

thumbnails/
├── wedding-sarah-john-ceremony-thumb.jpg
├── drone-venue-aerial-view-thumb.jpg
└── ... (thumbnails for all portfolio images)
```

## 🔧 Image Optimization Tips

1. **Compress images** using tools like:
   - TinyPNG (online)
   - ImageOptim (Mac)
   - GIMP (free)
   - Photoshop (Save for Web)

2. **Use WebP format** when possible for better compression

3. **Maintain aspect ratios** to prevent distortion

4. **Add descriptive alt text** in your HTML

5. **Create responsive images** for different screen sizes

## 🚀 Adding Images to Website

After adding your images, update the HTML in `index.html`:

```html
<!-- Replace hero placeholder -->
<div class="hero-image">
    <img src="images/hero/hero-main.jpg" alt="Professional Wedding Photography">
</div>

<!-- Replace portfolio placeholders -->
<div class="portfolio-item" data-category="wedding">
    <img src="images/portfolio/wedding-sarah-john-ceremony.jpg" 
         alt="Sarah and John Wedding Ceremony">
    <div class="portfolio-overlay">
        <h4>Sarah & John's Wedding</h4>
        <p>Wedding Photography</p>
    </div>
</div>
```

## ✅ Quality Checklist

Before uploading images, ensure:

- [ ] Images are properly compressed for web
- [ ] File sizes are appropriate (see requirements above)
- [ ] Image names are descriptive and web-friendly
- [ ] All images have proper aspect ratios
- [ ] You have rights to use all images
- [ ] Images represent your best work
- [ ] Color correction and editing are complete

## 🎯 Pro Tips

1. **Showcase variety** - Include different styles and scenarios
2. **Tell a story** - Arrange portfolio images thoughtfully  
3. **Update regularly** - Keep your portfolio fresh
4. **Client consent** - Ensure you have permission to display client photos
5. **Backup originals** - Keep high-resolution originals separately

---

**Need help?** Check the main README.md file for more detailed instructions on customizing your photography website.