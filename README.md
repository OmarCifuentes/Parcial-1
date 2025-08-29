# ShopLogo - Frontend Project

## Team Members
- [Tu Nombre] - Frontend Developer
- [Nombre del Compañero 2] - Frontend Developer  
- [Nombre del Compañero 3] - Frontend Developer

## Project Description
ShopLogo is a modern, responsive e-commerce website built entirely from scratch using HTML5, CSS3, and vanilla JavaScript. The project demonstrates advanced frontend development skills including Grid Layout, Flexbox, responsive design, and accessibility best practices.

## Features Implemented

### ✅ Core Requirements
- **Grid Layout & Flexbox**: Comprehensive use of CSS Grid and Flexbox for modern layouts
- **5 Separate Pages**: Complete multi-page website structure
- **Responsive Design**: Mobile-first approach with breakpoints for all devices
- **HTML Best Practices**: Semantic HTML, proper metadata, and accessibility (A11y)
- **CSS from Scratch**: No frameworks or libraries - pure custom CSS
- **Modular Architecture**: Shared components loaded dynamically to avoid code duplication

### 🎯 Technical Implementation
- **Semantic HTML5**: Proper use of `<header>`, `<main>`, `<section>`, `<article>`, `<footer>`
- **CSS Custom Properties**: CSS variables for consistent theming
- **Responsive Grid System**: CSS Grid with mobile-first breakpoints
- **Accessibility Features**: ARIA labels, roles, and semantic structure
- **Interactive Components**: Contact forms, Google Maps integration
- **Performance Optimized**: Minimal JavaScript, efficient CSS

### 🔧 Modular Components
- **Shared Footer**: Single footer file referenced by all pages
- **Contact Section**: Reusable contact form and map component
- **Categories Preview**: Modular category navigation component
- **Common JavaScript**: Centralized functionality for dynamic content loading

## File Structure

```
Parcial 1/
├── index.html              # Homepage with dynamic content loading
├── products.html           # Products listing page
├── categories.html         # Category browsing page
├── about.html             # Company information page
├── contact.html           # Contact and support page
├── styles.css             # Complete custom CSS stylesheet
├── common.js              # Shared JavaScript functionality
├── footer.html            # Shared footer component
├── contact-section.html   # Contact section component
├── categories-preview.html # Categories preview component
├── README.md              # Project documentation
├── MAP_INSTRUCTIONS.md    # Google Maps setup guide
└── FrontEnd-Wireframes.pdf # Original project requirements
```

## Setup Instructions

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional but recommended)

### Quick Start
1. **Clone the repository**
   ```bash
   git clone [repository-url]
   cd "Parcial 1"
   ```

2. **View the project**
   - **Option 1**: Open `index.html` directly in your browser
   - **Option 2**: Use a local server for better performance

### Local Development Server

#### Python (Recommended)
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

#### Node.js
```bash
# Install http-server globally
npm install -g http-server

# Run server
http-server -p 8000

# Or use npx
npx http-server -p 8000
```

#### PHP
```bash
php -S localhost:8000
```

#### Ruby
```bash
ruby -run -e httpd . -p 8000
```

3. **Access the website**
   - Open your browser and navigate to `http://localhost:8000`
   - The homepage will load with all components dynamically

## Browser Support
- **Modern Browsers**: Chrome 60+, Firefox 55+, Safari 12+, Edge 79+
- **CSS Grid**: Full support in all modern browsers
- **CSS Custom Properties**: Supported in all modern browsers
- **JavaScript ES6+**: Modern JavaScript features used

## Performance Features
- **Minimal JavaScript**: Lightweight, efficient code
- **CSS Optimization**: Efficient selectors and minimal redundancy
- **Modular Loading**: Components loaded only when needed
- **Responsive Images**: Optimized for different screen sizes

## Accessibility Features
- **Semantic HTML**: Proper heading hierarchy and structure
- **ARIA Labels**: Screen reader friendly navigation
- **Keyboard Navigation**: Full keyboard accessibility
- **Color Contrast**: WCAG compliant color schemes
- **Focus Management**: Clear focus indicators

## Future Enhancements
- **Progressive Web App**: Service workers and offline functionality
- **Advanced Animations**: CSS animations and transitions
- **Form Validation**: Enhanced client-side validation
- **Performance Monitoring**: Core Web Vitals optimization
- **Internationalization**: Multi-language support

## Branch Structure (Recommended)
```
main                    # Production-ready code
├── develop            # Integration branch
├── feature/navbar     # Navigation improvements
├── feature/products   # Product management
├── feature/contact    # Contact form enhancements
└── hotfix/typo       # Quick fixes
```

## Development Guidelines
- **Code Quality**: Follow HTML5 and CSS3 best practices
- **Accessibility**: Maintain WCAG 2.1 AA compliance
- **Performance**: Optimize for Core Web Vitals
- **Testing**: Test across different browsers and devices
- **Documentation**: Keep README and code comments updated

## License
This project is created for educational purposes as part of the Frontend Development course.

---

**Note**: This project demonstrates modern frontend development practices without relying on external frameworks or libraries. All functionality is built from scratch using vanilla web technologies.
