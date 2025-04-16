# Show My Name - Website

A simple splash page for the Show My Name mobile application, containing the privacy policy and contact information.

## Pages

- Home page with app title and navigation buttons
- Privacy Policy page with the complete privacy policy
- Contact Us page with a contact form

## Deployment Instructions

This site is designed to be deployed on Netlify:

1. Create a new site on Netlify
2. Connect to your Git repository
3. Set the build settings:
   - Build command: (leave blank, as this is a static site)
   - Publish directory: `/`
4. Deploy the site

### Form Configuration

The contact form uses Formspree. To set it up:

1. Create an account on [Formspree](https://formspree.io/)
2. Create a new form and get your form endpoint
3. Replace `your-formspree-endpoint` in the `contact.html` file with your actual endpoint

## Custom Domain Setup

The site is designed to use `http://ShowMyName.app` as the domain. To set this up:

1. Purchase the domain (if not already owned)
2. Configure your DNS settings to point to Netlify
3. Add the custom domain in your Netlify site settings

## Development

This is a simple static site with HTML, CSS, and minimal JavaScript. To develop locally:

1. Clone the repository
2. Make changes to the HTML, CSS, or JavaScript files
3. Open the HTML files in your browser to preview changes
4. Deploy to Netlify when ready

## Colors

The site uses a dark theme with the following colors:
- Black: #000
- White: #fff
- Teal: #029579
- Coral: #f03154 