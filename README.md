# Asheville Wanderlust Website

A modern, responsive website for the Asheville Wanderlust Society, built with HTML, CSS, and Tailwind CSS. The site showcases our community events and provides easy access to our WhatsApp group and monthly meetups.

## Features

- Mobile-responsive design
- SEO optimized with meta tags and sitemap
- Modern UI with Tailwind CSS
- Social media sharing cards (Twitter, Facebook)
- Dynamic copyright year
- Clean URLs
- Image optimization and preloading
- Past events timeline
- External links open in new tabs

## Setup

1. Install dependencies:
```bash
npm install
```

2. Start development server:
```bash
npm run dev
```

3. Build for production:
```bash
npm run build
```

## Project Structure

- `index.html` - Main landing page
- `past-events.html` - Timeline of past community events
- `src/input.css` - Source CSS file with Tailwind directives
- `dist/output.css` - Generated CSS file (created after build)
- `public/assets/` - Static assets directory
  - `images/` - Image assets including header image
- `tailwind.config.js` - Tailwind configuration
- `postcss.config.js` - PostCSS configuration
- `vercel.json` - Vercel deployment configuration
- `robots.txt` - Search engine crawler instructions
- `sitemap.xml` - Site structure for search engines

## Development

The development server will watch for changes in your HTML and CSS files and automatically rebuild the Tailwind CSS file. Simply run `npm run dev` and start editing!

## Deployment

The site is configured for deployment on Vercel with:
- Clean URLs (no .html extension needed)
- Proper static asset serving
- SEO optimization
- Social media preview cards

## SEO Features

- Comprehensive meta tags
- Open Graph tags for social sharing
- Twitter Card support
- Sitemap.xml for search engines
- Robots.txt configuration
- Canonical URLs
- Semantic HTML structure

## Browser Support

The site is built with modern web standards and should work in all modern browsers. Features include:
- Responsive images
- Flexbox layouts
- CSS Grid
- Resource preloading
- Security best practices (noopener, noreferrer)
