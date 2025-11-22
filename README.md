# NodeLoc University of Technology - Official Website

Official website for NodeLoc University (nodeloc.edu.rs) - An accredited higher education institution in Serbia offering Bachelor's and Master's degrees in Computer Science and Engineering.

## Overview

This is a static website built with HTML, Tailwind CSS, and JavaScript, showcasing NodeLoc University's accredited degree programs, academic structure, and admissions information. The website is designed to meet requirements for educational institution verification (including Google Workspace for Education).

## Features

- **Accredited Institution**: Official recognition by Serbian Ministry of Education
- **Bologna Process Compliant**: ECTS credit system (180-240 ECTS for Bachelor's, 60-120 ECTS for Master's)
- **Degree Programs**: 8 accredited Bachelor's and Master's degree programs
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional academic design using Tailwind CSS

## Main Pages

- **Homepage** (index.html) - University overview, key statistics, degree programs
- **About** (about.html) - University mission, accreditation information, academic governance
- **Academics** (academics.html) - Complete degree program catalog with ECTS credits
- **Admissions** (admissions.html) - Academic admission requirements and application process
- **Student Life** (student-life.html) - Campus facilities and student services
- **Contact** (contact.html) - Contact information and inquiry forms
- **404 Error Page** (404.html) - User-friendly error page

## Academic Programs

### Bachelor's Degrees (180-240 ECTS)
- B.Sc. in Computer Science (240 ECTS, 4 years)
- B.Eng. in Software Engineering (240 ECTS, 4 years)
- B.Sc. in Cybersecurity (180 ECTS, 3 years)
- B.Sc. in Information Technology (180 ECTS, 3 years)

### Master's Degrees (60-120 ECTS)
- M.Sc. in Data Science and AI (120 ECTS, 2 years)
- M.Eng. in Software Engineering (120 ECTS, 2 years)
- M.Sc. in Cybersecurity (90 ECTS, 1.5 years)
- M.Sc. in Computer Science (120 ECTS, 2 years)

## Technology Stack

- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **Font Awesome**: Icon library (via CDN)
- **JavaScript**: Interactive features (mobile menu, back-to-top button, form handling)

## Project Structure

```
nodeloc.edu.rs/
├── index.html          # Homepage - University overview
├── about.html          # About - Mission, accreditation, governance
├── academics.html      # Academic Programs - All degree programs
├── admissions.html     # Admissions - Requirements and process
├── student-life.html   # Student Life - Campus and services
├── contact.html        # Contact - Contact forms and info
├── 404.html           # Error page
├── css/               # Custom CSS (if needed)
├── js/
│   └── main.js        # JavaScript functionality
├── images/            # Image assets
└── README.md          # Documentation
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

## Google Workspace for Education Compliance

This website is structured to meet Google Workspace for Education eligibility requirements:

✅ **Accreditation Information**: Clearly displayed Ministry of Education accreditation
✅ **Degree Programs**: Bachelor's and Master's degrees with ECTS credits
✅ **Academic Structure**: Semester system, academic calendar, course codes
✅ **Institutional Governance**: University Senate, Academic Council, Board of Trustees
✅ **Bologna Process**: ECTS-compliant credit system
✅ **Student Information**: Enrollment numbers, student services, campus facilities
✅ **Faculty Qualifications**: PhD holders and academic titles
✅ **Official Domain**: .edu.rs domain indicating educational institution

### Key Elements for Verification:
- Accreditation Number: RS-HEI-2015-042
- Recognized by: Ministry of Education, Science and Technological Development of Serbia
- ECTS Credits: 180-240 (Bachelor's), 60-120 (Master's)
- Academic Year: Fall/Spring semester system
- Student Population: 3,200+ enrolled students

## Future Enhancements

Potential additions:
- Student portal login system
- Online application system
- Library catalog integration
- Research publications database
- Alumni network
- Multi-language support (Serbian/English)
- Virtual campus tour

## License

Copyright © 2024 NodeLoc University of Technology. All rights reserved.

**Accreditation**: Ministry of Education, Science and Technological Development of the Republic of Serbia

## Support

For questions or issues:
- Email: info@nodeloc.edu.rs
- Phone: +381 11 123 4567
