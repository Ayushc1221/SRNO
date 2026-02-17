# SRNO Website - Setup & Instructions

## Overview

This is a professional website for Social Research Network Organisation (SRNO) built with HTML5, CSS3, and JavaScript. The website is responsive and includes all sections mentioned in your design requirements.

## File Structure

```
Website/
├── index.html              (Main website file)
├── css/
│   └── style.css          (Complete styling)
├── js/
│   └── script.js          (Interactive functionality)
├──  content/SRNO Logo.jpeg         (Your logo file)
├── Client Logos/          (Directory for client logos)
└── Photos for Website/    (Directory for gallery images)
```

## Features Included

### 1. **Responsive Navigation Bar**

- Sticky header with logo and menu
- Mobile hamburger menu
- Smooth navigation links
- Active link highlighting

### 2. **Hero Section**

- Full-width background (ready for your image)
- Prominent tagline overlay
- Call-to-action button
- Statistics box showing key achievements

### 3. **Know More Section**

- Mission statement
- Vision statement
- Organization overview

### 4. **Services Section**

- Research
- Consultancy
- Capacity Building
- Intervention Implementation Support

### 5. **Research Services Details**

- Quantitative Surveys
- Qualitative Surveys
- Technical Expertise

### 6. **Key Strengths**

- Empaneled Experts
- Trained Field Team
- Technological Expertise
- Quality Commitment

### 7. **Clients Logo Slider**

- Swiper carousel for client logos
- Auto-play functionality
- Navigation controls
- Responsive design

### 8. **Gallery Section**

- Grid layout for images
- Hover effects
- Placeholder for your images

### 9. **Team Section**

- Advisors
- Founder
- Consultants
- Data Experts
- Card-based layout with hover effects

### 10. **Projects Section**

- Tabbed interface for different project categories
- Public Health
- Livelihood
- Agriculture
- Nutrition
- Education
- Sanitation

### 11. **Contact Section**

- Office information
- Contact form
- Map ready (you can add)

### 12. **Footer**

- Quick links
- Social media links
- Company info

## How to Add Your Content

### 1. **Logo**

- Replace ` content/SRNO Logo.jpeg` with your logo file
- Keep the same filename or update the path in `index.html`

### 2. **Hero Image**

- Add your full-page achievement image
- Update the `.hero-background` background image in `css/style.css`:

```css
.hero-background {
  background-image: url("../Photos for Website/your-image.jpg");
  background-size: cover;
  background-position: center;
}
```

### 3. **Client Logos**

- Place all client logo images in the `Client Logos/` folder
- Update the image paths in the swiper slides section

### 4. **Gallery Images**

- Place your gallery images in `Photos for Website/` folder
- Replace the image placeholders in the gallery section

### 5. **Team Photos**

- Add team member photos
- Update the `.team-placeholder` styling to include actual images:

```css
.team-placeholder {
  background-image: url("../path-to-image.jpg");
  background-size: cover;
  background-position: center;
}
```

## Color Scheme

The website uses a professional color palette:

- **Primary Blue**: #1a5490
- **Secondary Blue**: #2c7ab8
- **Accent Orange**: #f39c12
- **Dark Text**: #2c3e50
- **Light Background**: #f8f9fa

You can customize these in `css/style.css` by modifying the CSS variables in `:root`

## Taglines Included

The current tagline is: "Pioneering Excellence in Survey, Research, and Capacity Building"

To change it, edit the `.hero-title` text in `index.html` to one of your preferred options:

- Leading the Way in Survey, Research, and Capacity Building
- Capacity to Thrive, Research to Revive
- Enabling the way, for research and survey

## Responsive Design

The website is fully responsive with breakpoints for:

- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (480px - 767px)
- Small Mobile (below 480px)

## External Libraries Used

1. **Font Awesome 6.4** - For icons
2. **Swiper 10** - For carousel functionality

These are loaded from CDN, so no installation needed.

## How to Use

1. **Open the website**: Simply open `index.html` in any modern web browser
2. **Test on mobile**: Use browser developer tools (F12) to test responsive design
3. **Update content**: Edit `index.html` for text content
4. **Update styling**: Modify `css/style.css` for colors and layouts
5. **Add interactivity**: Extend `js/script.js` for additional functionality

## Browser Compatibility

Works on:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Notes

- All blank sections (images, logos) are marked with placeholder boxes
- The form submits locally (you'll need to add backend functionality for actual email sending)
- Statistics numbers (215+, 25+, 1000+) can be updated in the HTML
- All content is easy to find and update in the index.html file

## Contact Form Integration

To make the contact form send emails, you'll need to:

1. Use a backend service (PHP, Node.js, etc.)
2. Use a third-party service like Formspree, EmailJS, or similar
3. Currently, it just shows a thank you message

## Future Enhancements

Consider adding:

- Blog section
- Case studies page
- Testimonials section
- Events/News updates
- Search functionality
- Multi-language support

---

**Ready to customize!** All sections are clearly labeled and easy to modify.
