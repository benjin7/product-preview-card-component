# Product Preview Card Component

![Design preview for the Product preview card component coding challenge](./design/desktop-preview.jpg)

A responsive product preview card component built with HTML and CSS, showcasing a luxury perfume product with a clean, modern design.

## 🎯 Features

- **Responsive Design** - Adapts seamlessly from desktop to mobile screens
- **Optimal Layout** - Displays perfectly on devices of all sizes (desktop: 2-column grid, mobile: single column)
- **Responsive Images** - Uses the `<picture>` element to serve different images based on screen size
- **Interactive Elements** - Hover states on the "Add to Cart" button with smooth color transitions
- **Accessibility** - Semantic HTML and proper alt text for images
- **Modern Styling** - Custom color palette and elegant typography using Google Fonts (Fraunces and Montserrat)

## 📱 Responsive Breakpoints

- **Desktop** (641px+): 2-column grid layout with image on left, content on right
- **Mobile** (≤640px): Single column layout with image on top, content below

### Mobile Image Optimization

The component uses the HTML5 `<picture>` element to serve:
- `image-product-desktop.jpg` - High-resolution image for desktop screens
- `image-product-mobile.jpg` - Optimized image for mobile screens (≤640px)

## 🎨 Design Details

### Colors
- Primary Green: `hsl(158, 36%, 37%)`
- Dark Green (hover): `hsl(158, 42%, 18%)`
- Text: `hsl(228, 12%, 48%)`
- Headings: `hsl(212, 21%, 14%)`
- Background: `hsl(30, 38%, 92%)`

### Typography
- **Headings**: Fraunces (700, 900 weights)
- **Body**: Montserrat (400, 500, 700 weights)

## 📂 Project Structure

```
product-preview-card-component-main/
├── index.html           # Main HTML file
├── style.css            # Stylesheet with responsive design
├── style-guide.md       # Design specifications
├── README.md           # This file
├── design/             # Design mockups
│   └── desktop-preview.jpg
└── images/             # Optimized assets
    ├── image-product-desktop.jpg
    ├── image-product-mobile.jpg
    ├── icon-cart.svg
    └── favicon-32x32.png
```

## ✨ Built With

- HTML5
- CSS3 (Flexbox & CSS Grid)
- Google Fonts
- Responsive Design (Media Queries)

## 📝 Notes

- The component includes a cart icon SVG that appears before the button text on hover
- All styling is contained in a single `style.css` file
- Uses CSS Grid for the 2-column desktop layout
- Mobile layout gracefully transitions to a single-column design

## 🔗 Resources

- [Frontend Mentor](https://www.frontendmentor.io)
- [Google Fonts](https://fonts.google.com)
- [MDN Web Docs - Picture Element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/picture)


