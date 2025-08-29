# ShopLogo - Frontend Project

## Team Members
- Omar Cifuentes - Frontend Developer
- Jonathan Castellano - Frontend Developer  


## Acceptance Criteria

### ✅ Grid Layout
- **CSS Grid**: Implemented throughout the project for main layouts
- **Grid Areas**: Used for complex layouts like the Home & Garden products section
- **Responsive Grid**: Adapts to different screen sizes

### ✅ Flexbox
- **Navigation**: Main navigation uses flexbox for horizontal alignment
- **Footer**: Footer columns use flexbox for proper spacing
- **Form Elements**: Contact form uses flexbox for layout
- **Button Groups**: Icon buttons and social media icons use flexbox

### ✅ 5 Pages
1. **`index.html`** - Homepage with hero section, featured products, categories, and contact
2. **`products.html`** - Complete products listing page
3. **`categories.html`** - Category browsing with product examples
4. **`about.html`** - Company information, careers, news, and legal policies
5. **`contact.html`** - Contact form, interactive Google Maps, help center, and returns

### ✅ Responsive (Mobile & Desktop)
- **Mobile-First Approach**: CSS designed for mobile devices first
- **Breakpoints**: 
  - Desktop: 1200px+
  - Tablet: 980px - 1199px
  - Mobile: 560px - 979px
  - Small Mobile: <560px
- **Flexible Grids**: All layouts adapt to screen size
- **Touch-Friendly**: Buttons and navigation optimized for mobile

### ✅ HTML Best Practices
- **Semantic HTML**: Proper use of `<header>`, `<main>`, `<section>`, `<article>`, `<footer>`
- **Metadata**: Complete meta tags for SEO and accessibility
- **A11y (Accessibility)**:
  - ARIA labels and roles
  - Proper heading hierarchy
  - Alt text for images
  - Keyboard navigation support
  - Screen reader friendly

### ✅ CSS from Scratch
- **No Frameworks**: Built entirely without Bootstrap, Tailwind, or any CSS libraries
- **Custom CSS**: All styles written from scratch
- **CSS Variables**: Custom properties for consistent theming
- **Modern CSS**: Uses latest CSS features like Grid, Flexbox, and custom properties

## Resources Used

### ✅ Iconfinder
- **Shopping Cart Icon**: Custom SVG icon for the topbar
- **Social Media Icons**: Facebook, Twitter/X, LinkedIn SVG icons
- **Category Icons**: Emoji-based icons for product categories

### ✅ Google Fonts
- **Inter Font Family**: Modern, readable font with multiple weights (400, 500, 600, 700, 800)
- **Performance Optimized**: Preconnect and proper loading

## Project Structure

```
Parcial 1/
├── index.html              # Homepage
├── products.html           # Products listing
├── categories.html         # Category browsing
├── about.html             # Company information
├── contact.html           # Contact and support
├── styles.css             # Complete custom CSS
├── README.md              # Project documentation
├── MAP_INSTRUCTIONS.md    # Google Maps setup guide
└── FrontEnd-Wireframes.pdf # Original project requirements
```

## Branch Structure

### Required Branch Setup
```
main                    # Shared common branch (production)
├── develop            # Shared development branch
├── feature/team1      # Team member 1 branch
├── feature/team2      # Team member 2 branch
└── feature/team3      # Team member 3 branch
```

### Branch Guidelines
- **Maximum 3 team members**
- **Each member has their own feature branch**
- **Shared common branch for integration**
- **Submit only the repository URL**

## Setup Instructions

### Quick Start
1. **Clone the repository**
   ```bash
   git clone [repository-url]
   cd "Parcial 1"
   ```

2. **View the project**
   - Open `index.html` directly in your browser
   - Or use a local server for better performance

### Local Development Server

#### Python
```bash
python -m http.server 8000
```

#### Node.js
```bash
npx http-server -p 8000
```

3. **Access the website**
   - Navigate to `http://localhost:8000`
   - Test all 5 pages and responsive design

## Technical Implementation

### CSS Grid Examples
```css
/* Main layout grid */
.container {
  display: grid;
  grid-template-columns: repeat(12, 1fr);
  gap: 20px;
}

/* Products grid */
.products-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
}

/* Special Home & Garden layout */
#home .products-grid {
  grid-template-columns: repeat(2, 1fr);
  grid-template-areas:
    "chair pot"
    "lamp lamp";
}
```

### Flexbox Examples
```css
/* Navigation */
.nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

/* Footer columns */
.footer-top {
  display: flex;
  gap: 40px;
}

/* Social media icons */
.socials {
  display: flex;
  gap: 15px;
}
```

### Responsive Breakpoints
```css
/* Tablet */
@media (max-width: 980px) {
  .container { padding: 0 20px; }
}

/* Mobile */
@media (max-width: 560px) {
  .products-grid { grid-template-columns: 1fr; }
}
```

## Features

### Interactive Elements
- **Google Maps Integration**: Real, interactive map in contact page
- **Contact Form**: Functional contact form with proper validation
- **Navigation**: Smooth navigation between all 5 pages
- **Responsive Images**: Optimized for all screen sizes

### Accessibility Features
- **Semantic Structure**: Proper HTML5 semantic elements
- **ARIA Support**: Labels, roles, and descriptions
- **Keyboard Navigation**: Full keyboard accessibility
- **Color Contrast**: WCAG compliant design
- **Screen Reader Support**: Proper heading hierarchy and labels

## Browser Support
- **Modern Browsers**: Chrome 60+, Firefox 55+, Safari 12+, Edge 79+
- **CSS Grid**: Full support in all modern browsers
- **CSS Flexbox**: Full support in all modern browsers
- **CSS Custom Properties**: Supported in all modern browsers

## Performance
- **No External Dependencies**: Pure HTML/CSS implementation
- **Optimized CSS**: Efficient selectors and minimal redundancy
- **Fast Loading**: No framework overhead
- **Responsive Images**: Optimized for different screen sizes

## Future Enhancements
- **Progressive Web App**: Service workers and offline functionality
- **Advanced Animations**: CSS animations and transitions
- **Form Validation**: Enhanced client-side validation
- **Performance Monitoring**: Core Web Vitals optimization

## Development Guidelines
- **Code Quality**: Follow HTML5 and CSS3 best practices
- **Accessibility**: Maintain WCAG 2.1 AA compliance
- **Performance**: Optimize for Core Web Vitals
- **Testing**: Test across different browsers and devices
- **Documentation**: Keep README updated

## License
This project is created for educational purposes as part of the Frontend Development course.

---

**Note**: This project demonstrates modern frontend development practices without relying on external frameworks or libraries. All functionality is built from scratch using vanilla HTML and CSS with Grid Layout and Flexbox.
