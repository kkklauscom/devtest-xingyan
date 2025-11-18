# Dog Sitting Service Website

A responsive website for a dog sitting service, featuring a modern design with hero banner and service cards.

## Project Overview

This project is a responsive website implementation for a dog sitting service. The design includes a hero section with call-to-action and a services section showcasing three main services: Dog Walking, Dog Boarding, and Dog Sitting.

## Features

- **Responsive Design**: Fully responsive layout supporting multiple screen sizes
  - Mobile: 375px
  - Tablet Tall: 726px
  - Tablet Wide: 1024px
  - Desktop: 1440px

- **Hero Section**: 
  - Full-width banner image with overlay gradient
  - White text content with call-to-action button
  - Decorative wave SVG at the bottom

- **Services Section**:
  - "Our Services" introduction
  - Three service cards with images and descriptions
  - Responsive card layouts (vertical on mobile, horizontal on tablet, three-column grid on desktop)

## Technology Stack

- **HTML5**: Semantic markup
- **CSS3**: Pure CSS implementation with CSS Custom Properties (variables)
- **Google Fonts**: Quicksand font family (weights: 500, 700)
- **Normalize.css**: Cross-browser CSS reset

## Design System

### Colors
- Primary Orange: `#e67627`
- Primary Dark: `#c45a0f`
- Primary Light: `#f08535`
- Text Color: `#333333`
- Text Light: `#999999`
- Background Light: `#f5f5f5`
- White: `#ffffff`

### Typography
- Font Family: Quicksand (Google Fonts)
- Font Weights: 500 (regular), 700 (bold)

### Spacing
- Consistent spacing system using CSS variables
- Responsive spacing adjustments across breakpoints

## File Structure

```
├── index.html          # Main HTML file
├── styles.css          # Main stylesheet with responsive design
├── normalize.css       # CSS reset
├── assets/
│   ├── main-banner.png
│   ├── banner-wave.svg
│   ├── card-image-walking.png
│   ├── card-image-boarding.png
│   └── card-image-sitting.png
└── README.md          # Project documentation
```

## Responsive Breakpoints

### Mobile (≤375px)
- Vertical card layout
- Optimized hero image positioning
- Compact spacing

### Tablet Tall (376px - 900px)
- Horizontal card layout (image left, text right)
- Hero content positioned at 50% height
- Reduced banner wave scale

### Tablet Wide (901px - 1200px)
- Horizontal card layout maintained
- White background for services section
- Larger typography

### Desktop (≥1201px)
- Three-column card grid layout
- Vertical card structure (image top, text bottom)
- Centered hero content with max-width constraint
- Enhanced spacing and typography

## Running the Project

### Option 1: Direct Browser Opening
Simply open `index.html` in your web browser.

### Option 2: Local Server (Recommended)
For better testing and to avoid CORS issues:

**Using Python:**
```bash
python3 -m http.server 8000
```
Then visit `http://localhost:8000`

**Using Node.js:**
```bash
npx http-server -p 8000
```

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Notes

- All styling is implemented using pure CSS (no JavaScript frameworks)
- CSS Custom Properties are used for maintainable theming
- Responsive images use `object-fit: cover` for consistent display
- Flexbox is used for layout management
- Media queries handle all responsive breakpoints

## Original Brief

A client requested updates to their dog sitting website. The design needed to be responsive across different screen sizes with designs for mobile, tablet, and desktop views.
