# NodeLoc Educational Institution Website

Official website for NodeLoc (nodeloc.edu.rs) - A leading computer science education institution in Serbia.

## Overview

This is a static website built with HTML, Tailwind CSS, and JavaScript, showcasing NodeLoc's educational programs, faculty, and admissions information.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design using Tailwind CSS
- **7 Main Pages**:
  - Homepage (index.html)
  - About Us (about.html)
  - Courses (courses.html)
  - Faculty (faculty.html)
  - Admissions (admissions.html)
  - Contact (contact.html)
  - 404 Error Page (404.html)

## Technology Stack

- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **Font Awesome**: Icon library (via CDN)
- **JavaScript**: Interactive features (mobile menu, back-to-top button, form handling)

## Project Structure

```
nodeloc.edu.rs/
├── index.html          # Homepage
├── about.html          # About page
├── courses.html        # Courses catalog
├── faculty.html        # Faculty team
├── admissions.html     # Admissions info
├── contact.html        # Contact page
├── 404.html           # Error page
├── css/               # Custom CSS (if needed)
├── js/
│   └── main.js        # JavaScript functionality
├── images/            # Image assets
└── README.md          # This file
```

## How to Use

1. **Local Development**: Simply open `index.html` in a web browser
2. **Deployment**: Upload all files to your web server or hosting service

### Recommended Hosting Options:

- **Static Hosting**: Netlify, Vercel, GitHub Pages
- **Traditional Hosting**: Any web server with HTML support
- **CDN**: Cloudflare Pages, AWS S3 + CloudFront

## Customization

### Update Content:
- Edit the HTML files directly to change text, images, or structure
- All pages use consistent navigation and footer components

### Change Colors:
- The website uses Tailwind's blue color scheme (blue-600, blue-700, etc.)
- Modify the color classes in HTML to change the theme

### Add Images:
- Place images in the `images/` folder
- Update the `<img>` tags or background styles to reference your images

### Update Contact Information:
- Edit contact details in the footer (present in all pages)
- Update the contact page with your actual address, phone, and email

## Contact Form

The contact form currently uses JavaScript to prevent default submission and shows an alert. To make it functional:

1. Set up a backend service (PHP, Node.js, etc.)
2. Or use a form service like Formspree, Netlify Forms, or EmailJS
3. Update the form action and submission handler in `js/main.js`

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- **Lightweight**: Minimal external dependencies
- **Fast Loading**: CDN-hosted resources
- **SEO Optimized**: Semantic HTML and meta tags

## Future Enhancements

Potential additions:
- Student portal
- Online course enrollment system
- Blog/News section
- Image gallery
- Testimonials section
- Multi-language support (Serbian/English)

## License

Copyright © 2024 NodeLoc Educational Institution. All rights reserved.

## Support

For questions or issues:
- Email: info@nodeloc.edu.rs
- Phone: +381 11 123 4567
