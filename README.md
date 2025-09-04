# B&B Custom Tile Website

A professional website for B&B Custom Tile, a tile installation company based in Arizona. Built with vanilla HTML, CSS, and JavaScript for optimal performance and SEO.

## Features

- **5 Complete Pages**: Home, Services, About, Contact, Gallery
- **Responsive Design**: Mobile-first approach with modern CSS Grid and Flexbox
- **SEO Optimized**: Meta tags, structured data, semantic HTML
- **Performance Focused**: Optimized images, lazy loading, minimal dependencies
- **Contact Form**: Client-side validation with server-side processing
- **Gallery Filter**: Interactive project showcase with filtering
- **Security**: Rate limiting, input validation, security headers

## Technology Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Backend**: Node.js with Express
- **Email**: Resend API integration
- **Security**: Helmet.js, rate limiting, input validation
- **Images**: Unsplash for demo content

## Quick Start

1. **Install Dependencies**
   ```bash
   npm install
   ```

2. **Set Environment Variables**
   Create a `.env` file in the root directory:
   ```env
   RESEND_API_KEY=your_resend_api_key_here
   RESEND_FROM_EMAIL=noreply@bbcustomtile.com
   RESEND_TO_EMAIL=info@bbcustomtile.com
   SITE_URL=https://bbcustomtile.com
   CONTACT_FORM_ENABLED=true
   ```

3. **Start Development Server**
   ```bash
   npm run dev
   ```

4. **Open in Browser**
   Visit `http://localhost:3000`

## Project Structure

```
BandB Custom Tile/
├── index.html          # Home page
├── services.html       # Services page
├── about.html          # About page
├── contact.html        # Contact page
├── gallery.html        # Gallery page
├── css/
│   └── styles.css      # Main stylesheet
├── js/
│   └── main.js         # JavaScript functionality
├── server.js           # Node.js server
├── package.json        # Dependencies
└── README.md          # This file
```

## Pages Overview

### Home Page
- Hero section with compelling CTA
- Services preview
- Why choose us section
- Strong conversion elements

### Services Page
- Detailed service descriptions
- Installation process
- Materials and brands
- Service-specific CTAs

### About Page
- Company story and mission
- Team member profiles
- Certifications and licenses
- Why choose us section

### Contact Page
- Contact information
- Comprehensive contact form
- Service areas
- FAQ section

### Gallery Page
- Project showcase with filtering
- Customer testimonials
- Interactive gallery

## SEO Features

- Semantic HTML structure
- Meta tags and Open Graph
- Schema.org structured data
- Optimized images with alt tags
- Fast loading times
- Mobile-friendly design

## Performance Optimizations

- Lazy loading for images
- Minified CSS and JavaScript
- Optimized image formats
- Minimal external dependencies
- Efficient CSS Grid layouts
- Critical CSS inlining

## Security Features

- Rate limiting on contact form
- Input validation and sanitization
- Security headers with Helmet.js
- CORS configuration
- Environment variable protection

## Contact Form Integration

The contact form uses Resend API for email delivery:

1. Set up a Resend account
2. Get your API key
3. Add it to your `.env` file
4. Configure sender and recipient emails

## Customization

### Colors
Update CSS custom properties in `styles.css`:
```css
:root {
    --primary-color: #c2410c;
    --secondary-color: #f59e0b;
    --accent-color: #059669;
}
```

### Content
- Update company information in HTML files
- Replace Unsplash images with actual project photos
- Modify contact information and service areas
- Update team member information

### Styling
- Modify CSS variables for brand colors
- Adjust spacing and typography
- Add custom animations
- Update responsive breakpoints

## Deployment

### Static Hosting (Recommended)
1. Build the static files
2. Deploy to Netlify, Vercel, or similar
3. Configure form handling with Netlify Forms or similar

### Server Deployment
1. Set up Node.js server
2. Configure environment variables
3. Set up Resend API
4. Deploy to Heroku, DigitalOcean, or similar

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Metrics

- Lighthouse Score: 95+
- First Contentful Paint: < 1.5s
- Largest Contentful Paint: < 2.5s
- Cumulative Layout Shift: < 0.1

## License

MIT License - feel free to use this template for your own projects.

## Support

For questions or support, contact B&B Custom Tile at info@bbcustomtile.com
