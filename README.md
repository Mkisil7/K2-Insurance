# K2 Insurance Website

A professional static website for K2 Insurance agency built with pure HTML, CSS, and JavaScript.

## 🏢 About

K2 Insurance is a trusted insurance agency providing comprehensive coverage solutions for individuals, families, and businesses. This website showcases our services, company information, and provides easy access to quotes and contact information.

## 🚀 Features

- **Responsive Design**: Mobile-first approach with clean, professional styling
- **Multiple Pages**: Home, About, Services, Contact, Companies, and FAQ pages
- **Interactive Elements**: FAQ accordion, contact form, mobile navigation
- **SEO Optimized**: Semantic HTML, meta tags, and accessibility features
- **Fast Loading**: Static site with optimized assets
- **Professional Styling**: Deep sea blue color scheme with modern typography

## 📁 Project Structure

```
k2-insurance-site/
├── index.html              # Home page
├── about.html              # About Us page
├── services.html           # Services page
├── contact.html            # Contact page
├── companies.html          # Insurance companies page
├── faq.html               # FAQ page
├── assets/
│   ├── css/
│   │   ├── theme.css      # Color variables and base styles
│   │   └── main.css       # Layout and component styles
│   ├── js/
│   │   └── main.js        # Navigation and interactivity
│   └── img/               # Image assets (placeholders included)
├── .github/
│   └── workflows/
│       └── deploy.yml     # GitHub Actions deployment
└── README.md              # This file
```

## 🛠️ Local Development

### Prerequisites

- A modern web browser
- A local web server (optional, for testing)

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/k2-insurance-site.git
   cd k2-insurance-site
   ```

2. **Open in browser**
   - **Option 1**: Open `index.html` directly in your browser
   - **Option 2**: Use a local server for better testing:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (if you have http-server installed)
     npx http-server
     
     # Using PHP
     php -S localhost:8000
     ```

3. **Navigate to the site**
   - Direct file: Open `index.html` in your browser
   - Local server: Visit `http://localhost:8000`

## 🎨 Customization

### Colors and Theme

Edit `assets/css/theme.css` to customize:
- Color palette (CSS custom properties)
- Typography settings
- Spacing and sizing variables
- Button styles

### Content

- **Text Content**: Edit HTML files directly
- **Images**: Replace placeholder images in `assets/img/`
- **Contact Information**: Update phone numbers, emails, and addresses in all HTML files

### Styling

- **Layout**: Modify `assets/css/main.css` for layout changes
- **Components**: Update card styles, forms, and other components
- **Responsive Design**: Adjust breakpoints and mobile styles

## 📱 Pages Overview

### Home (`index.html`)
- Hero section with call-to-action
- Services overview
- Why choose us section
- Contact information

### About Us (`about.html`)
- Company history and mission
- Team member profiles
- Values and principles
- Why choose K2 Insurance

### Services (`services.html`)
- Auto insurance details
- Home insurance coverage
- Life insurance options
- Business insurance solutions
- Additional services

### Contact (`contact.html`)
- Contact information and office hours
- Quote request form
- Office location details
- Emergency contact information

### Companies (`companies.html`)
- Partner insurance companies
- Carrier relationships
- Financial strength information
- Why partnerships matter

### FAQ (`faq.html`)
- General insurance questions
- Auto insurance FAQ
- Home insurance FAQ
- Life insurance FAQ
- Claims process questions

## 🚀 Deployment

### GitHub Pages (Recommended)

1. **Enable GitHub Pages**
   - Go to repository Settings
   - Navigate to Pages section
   - Select "GitHub Actions" as source

2. **Automatic Deployment**
   - Push changes to `main` branch
   - GitHub Actions will automatically deploy
   - Site will be available at `https://your-username.github.io/k2-insurance-site`

### Manual Deployment

1. **Build** (No build step required - static files)
2. **Upload** all files to your web server
3. **Configure** web server to serve `index.html` as default

### Other Hosting Options

- **Netlify**: Drag and drop the project folder
- **Vercel**: Connect your GitHub repository
- **AWS S3**: Upload files to S3 bucket with static hosting
- **Traditional Web Hosting**: Upload via FTP/SFTP

## 🔧 Configuration

### Contact Form

The contact form currently includes placeholder comments for form handling. To make it functional:

1. **Formspree** (Recommended)
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

2. **Netlify Forms**
   ```html
   <form name="contact" method="POST" data-netlify="true">
   ```

3. **Custom Backend**
   - Update form action to point to your server endpoint
   - Implement server-side form processing

### Analytics

Add Google Analytics or other tracking:

```html
<!-- Add to <head> section of all pages -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🎯 SEO Features

- Semantic HTML structure
- Meta descriptions and keywords
- Open Graph tags for social sharing
- Alt text for images
- Proper heading hierarchy
- Mobile-friendly design
- Fast loading times

## ♿ Accessibility Features

- Semantic HTML landmarks
- ARIA labels for interactive elements
- Keyboard navigation support
- Screen reader friendly
- High contrast color scheme
- Focus indicators

## 📞 Support

For questions about this website or K2 Insurance services:

- **Phone**: (555) 123-4567
- **Email**: info@k2insurance.com
- **Office**: 123 Insurance Street, Suite 100, Anytown, ST 12345

## 📄 License

This project is proprietary to K2 Insurance. All rights reserved.

## 🔄 Updates

To update the website:

1. Make changes to HTML, CSS, or JS files
2. Test locally
3. Commit and push to GitHub
4. GitHub Actions will automatically deploy updates

---

**Built with ❤️ for K2 Insurance**
