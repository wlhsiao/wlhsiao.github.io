# Kimberly Hsiao - Personal Website

A modern, responsive personal website for Kimberly Hsiao, a Computer Science PhD graduate from UT Austin specializing in image generation and computer vision research.

## Features

- **Modern Design**: Clean, professional layout with smooth animations
- **Responsive**: Fully responsive design that works on all devices
- **Interactive**: Smooth scrolling, hover effects, and mobile navigation
- **Professional Sections**: About, Research, Publications, and Contact
- **Contact Form**: Functional contact form with validation
- **SEO Optimized**: Proper meta tags and semantic HTML

## Sections

### Hero Section
- Eye-catching gradient background
- Professional introduction
- Call-to-action buttons
- Profile placeholder (can be replaced with actual photo)

### About Section
- Personal introduction
- Education history
- Research areas with skill tags
- Professional background

### Research Section
- Four main research areas with icons
- Hover effects and animations
- Focus on image generation expertise

### Publications Section
- Academic publications with years
- Links to papers and code (placeholder)
- Professional formatting

### Contact Section
- Contact information with icons
- Functional contact form
- Professional contact details

## Customization

### Personal Information
Update the following in `index.html`:

1. **Contact Information** (lines 280-295):
   ```html
   <span>kimberly.hsiao@utexas.edu</span>
   <span>linkedin.com/in/kimberly-hsiao</span>
   <span>github.com/kimberlyhsiao</span>
   ```

2. **Publications** (lines 200-250):
   - Replace placeholder publications with actual papers
   - Update authors, venues, and links

3. **Research Areas** (lines 150-170):
   - Modify research descriptions to match actual work
   - Update skill tags as needed

### Styling
The website uses a modern color scheme:
- Primary Blue: `#4a90e2`
- Gradient: `#667eea` to `#764ba2`
- Text: `#2d3748` (dark), `#4a5568` (medium), `#718096` (light)

### Adding a Profile Photo
Replace the profile placeholder in the hero section:
```html
<div class="profile-placeholder">
    <img src="path/to/your/photo.jpg" alt="Kimberly Hsiao">
</div>
```

And update the CSS:
```css
.profile-placeholder img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 50%;
}
```

## File Structure

```
kimberly_hsiao_website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Interactive features and animations
- **Font Awesome**: Icons
- **Google Fonts**: Inter font family

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Deployment

The website can be deployed to any static hosting service:

1. **GitHub Pages**: Push to a GitHub repository and enable Pages
2. **Netlify**: Drag and drop the folder
3. **Vercel**: Connect your GitHub repository
4. **Traditional hosting**: Upload files to any web server

## Performance

- Optimized images and fonts
- Minimal JavaScript
- Efficient CSS animations
- Fast loading times

## Accessibility

- Semantic HTML structure
- Proper heading hierarchy
- Alt text for images
- Keyboard navigation support
- High contrast colors

## Future Enhancements

- Add a blog section for research updates
- Integrate with academic databases for automatic publication updates
- Add a projects showcase section
- Implement dark mode toggle
- Add more interactive elements

## Contact

For questions about this website template or to request modifications, please contact the developer.

---

*This website is designed to showcase Kimberly Hsiao's academic and research achievements in a professional, modern format suitable for job market applications and networking.*