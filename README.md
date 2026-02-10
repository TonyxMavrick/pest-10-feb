# ShieldX Pest Control - Static Website

This folder contains the complete static HTML, CSS, and JavaScript version of the ShieldX Pest Control website.

## Files Structure

```
/public/
├── index.html          # Home page with hero, services, testimonials
├── services.html       # Detailed services information
├── about.html          # About us, mission, values
├── contact.html        # Contact form, map, contact information
├── terms.html          # Terms & Conditions
├── privacy.html        # Privacy Policy
├── 404.html            # 404 Error page
├── styles.css          # All CSS styling (responsive, yellow-black theme)
├── main.js             # JavaScript for mobile menu, forms, navigation
└── README.md           # This file
```

## Features

### Design
- **Yellow-Black Theme**: Professional branding with yellow (#facc15) and black colors
- **Fully Responsive**: Mobile-first design that works on all devices
- **SEO Optimized**: Proper meta tags, semantic HTML, and structured content
- **Fast Loading**: Minimal dependencies, optimized CSS and JS

### Pages

1. **Home (index.html)**
   - Hero section with CTA buttons
   - About ShieldX section
   - Services grid (7 services)
   - Why Choose Us benefits
   - How It Works (4 steps)
   - Customer testimonials
   - Final CTA section

2. **Services (services.html)**
   - Detailed service descriptions
   - Features and treatment processes
   - Safety information
   - Residential vs Commercial sections

3. **About (about.html)**
   - Company mission
   - Core values
   - Team information
   - Environmental responsibility

4. **Contact (contact.html)**
   - Contact form with validation
   - Phone, email, address information
   - Google Maps integration
   - Service areas list

5. **Terms & Privacy**
   - Legal information
   - Professional formatting
   - Easy to read sections

6. **404 Page**
   - User-friendly error page
   - Navigation options
   - Contact information

### Interactive Features (JavaScript)

- **Mobile Menu**: Hamburger menu for mobile devices
- **Active Navigation**: Highlights current page in navigation
- **Contact Form**: Form submission with toast notifications
- **Smooth Scrolling**: Smooth scroll for anchor links

### Contact Information

- **Phone**: +1-564-483-2938
- **Email**: control@ShieldXPestControl.com
- **Address**: 90 Waverly Pl, New York, NY 10003, USA

## How to Use

1. **Local Development**:
   - Simply open any `.html` file in a web browser
   - All files are interconnected with relative links

2. **Deploy to Web Server**:
   - Upload all files to your web server's root directory
   - Ensure `index.html` is set as the default/home page
   - Configure 404 redirects to `404.html` if supported

3. **Customization**:
   - Edit `styles.css` for design changes
   - Modify color variables at the top of CSS file
   - Update contact information in all HTML files
   - Replace images URLs in hero sections with your own

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- No external dependencies (except Google Maps)
- Minimal CSS and JavaScript
- Optimized for fast page load
- Mobile-responsive images

## Notes

- Google Maps API key: Uses default embedded map (consider adding your own API key for production)
- Form submissions: Currently shows toast notification (integrate with backend for actual submissions)
- Images: Using Unsplash URLs (consider hosting your own images for production)

## Maintenance

To update content:
1. Open the relevant HTML file in a text editor
2. Locate the section you want to modify
3. Update text, images, or links
4. Save and test in browser

For styling changes:
1. Open `styles.css`
2. Find the relevant class or selector
3. Modify properties
4. Save and refresh browser to see changes

## License

© 2026 ShieldX Pest Control. All rights reserved.
