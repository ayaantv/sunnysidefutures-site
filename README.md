# Sunnyside Futures LLC Website

A clean, modern real estate landing page for Sunnyside Futures LLC, a Florida-based long-term rental and real estate investment company.

## Features

- **Hero Section**: Introduction to Sunnyside Futures with company tagline
- **Featured Property**: Detailed listing for 3102 Mindfulness Dr, Clermont, FL
- **Community Highlights**: Information about the Wellness Ridge community
- **About Section**: Company background and mission
- **Contact Form**: Netlify Forms integration for lead capture

## Tech Stack

- Static HTML/CSS/JavaScript
- Responsive design (mobile-friendly)
- Netlify Forms for contact submissions
- Google Fonts (Poppins)
- Unsplash images (royalty-free)

## Local Development

```bash
# Using Netlify CLI
netlify dev
```

This will start a local development server at http://localhost:8888

## Deployment

The site is automatically deployed to Netlify when changes are pushed to the main branch.

## Contact Form

The contact form uses Netlify Forms with a honeypot field for spam prevention. Form submissions can be viewed in the Netlify dashboard under **Forms**.

## Customization

- **Colors**: Edit the CSS variables in `styles.css` (documented at the top of the file)
- **Content**: Edit text directly in `index.html`
- **Images**: Replace Unsplash URLs with your own images

## File Structure

```
/
├── index.html      # Main HTML page with all sections
├── styles.css      # All CSS styles including responsive design
├── script.js       # JavaScript for mobile nav and interactions
├── netlify.toml    # Netlify configuration
└── README.md       # This file
```
