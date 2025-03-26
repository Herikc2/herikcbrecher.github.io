# Personal Portfolio Website

This repository contains the source code for Herikc Brecher's personal portfolio website, a responsive single-page web application built to showcase professional experience, skills, and projects.

## Architecture

The website follows a traditional static web architecture with client-side rendering:

- **Single-page Application (SPA)** - All content is loaded on a single HTML page with smooth scrolling between sections
- **Responsive Design** - Adapts to various screen sizes and devices
- **HTML5/CSS3/JavaScript** - Core technologies used for structure, styling, and interactivity
- **No Backend** - Purely static site with no server-side processing

## Folder Structure

```
herikcbrecher.github.io/
├── css/                  # Stylesheet files
│   ├── base.css          # Base styling and reset
│   ├── font-awesome/     # Font Awesome icon library
│   ├── fonts.css         # Font definitions
│   ├── main.css          # Main styling for the website
│   ├── micons/           # Custom icon fonts
│   ├── slidebar.css      # Styling for sidebar navigation
│   └── vendor.css        # Third-party CSS libraries
├── fonts/                # Font files
├── images/               # Image assets
│   └── portfolio/        # Project screenshots and images
│       └── modals/       # Full-size images for modal popups
├── js/                   # JavaScript files
│   ├── jquery-3.5.1.min.js       # jQuery library
│   ├── jquery-migrate-1.4.1.min.js # jQuery migrate plugin
│   ├── main.js           # Custom JavaScript functionality
│   ├── modernizr.js      # Feature detection library
│   ├── pace.min.js       # Page load progress bar
│   ├── plugins.js        # jQuery plugins and extensions
│   └── slidebar.js       # Slidebar navigation functionality
├── pdf/                  # PDF documents (resumes, reports, etc.)
├── _config.yml           # GitHub Pages configuration
├── CNAME                 # Custom domain configuration
├── favicon.png           # Website favicon
├── index.html            # Main HTML file
├── LICENSE               # License file
└── README.md             # Project documentation (this file)
```

## Technical Aspects

### Frontend Technologies

- **HTML5**: Semantic markup for content structure
- **CSS3**: Modern styling features including:
  - Flexbox and Grid layouts
  - CSS animations and transitions
  - Media queries for responsive design
- **JavaScript/jQuery**: For interactive elements and dynamic content
  - Smooth scrolling
  - Portfolio modals
  - Form validation
  - Carousel sliders
  - Animation effects

### Libraries and Frameworks

- **jQuery**: JavaScript library for DOM manipulation
- **Modernizr**: Feature detection for browser compatibility
- **Pace.js**: Page load progress indicator
- **Owl Carousel**: Touch-enabled jQuery plugin for responsive carousel sliders
- **Font Awesome**: Icon library for social media and UI elements

### Responsive Design

The website implements a fully responsive design approach that adapts to various device sizes including:
- Desktop computers
- Tablets
- Mobile phones

Media queries and fluid layouts ensure optimal viewing experience across all devices.

### Performance Considerations

- Minified CSS and JavaScript files
- Optimized image assets
- Asynchronous script loading
- CSS sprite sheets for icons

### Deployment

The website is deployed using GitHub Pages, providing:
- Version control through Git
- Automatic deployment on commit to main branch
- Custom domain support

## Usage

To run this project locally:

1. Clone the repository:
   ```
   git clone https://github.com/herikcbrecher/herikcbrecher.github.io.git
   ```

2. Open `index.html` in your browser

3. No build tools or server setup required - the website is completely static.

## Browser Compatibility

The website is compatible with all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

IE8 and IE9 are supported through conditional comments and fallbacks. 