# RedStore - E-Commerce Website

A modern, responsive e-commerce website built with HTML, CSS, and modern web standards. RedStore is a fitness and lifestyle product store with a clean, professional design.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Responsive Design](#responsive-design)
- [Browser Compatibility](#browser-compatibility)
- [Author](#author)
- [License](#license)

## Features

✨ **Key Features:**

- **Modern Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Clean Navigation** - Intuitive navbar with links to all sections
- **Featured Products** - Showcase of premium fitness and lifestyle products
- **Product Categories** - Organized product categories for easy browsing
- **Customer Reviews** - Testimonials section with customer ratings
- **Exclusive Offers** - Special product highlight (Smart Band 4)
- **Newsletter Signup** - Email subscription form for updates
- **Social Media Integration** - Links to social media profiles
- **Accessible** - Built with accessibility best practices (ARIA labels, semantic HTML)
- **Smooth Animations** - Hover effects and transitions for better UX
- **Professional Footer** - Complete footer with company info and links

## Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with Flexbox and gradients
- **Bootstrap Icons** - Icon library for ratings and social media
- **Google Fonts** - Poppins font family for typography
- **FontAwesome** - Additional icon support
- **Responsive Design** - Mobile-first approach with media queries

## Project Structure

```
E-Commerce/
├── index.html          # Main HTML file
├── style.css           # Stylesheet with responsive design
├── README.md           # Project documentation
└── images/             # Product images and assets
    ├── logo.png
    ├── cart.png
    ├── category-1.jpg through category-3.jpg
    ├── product-1.jpg through product-12.jpg
    ├── exclusive.png
    ├── image1.png
    ├── user-1.png through user-3.png
    └── img-credit.txt
```

## Getting Started

### Prerequisites

- A modern web browser
- A code editor (VS Code, Sublime Text, etc.) - optional
- No server or dependencies required

### Installation

1. **Clone or download** the project files
2. **Navigate** to the project directory
3. **Open** `index.html` in your web browser
4. **Enjoy** browsing the website!

### Running Locally

Simply open `index.html` in your browser:

```bash
# On Windows
start index.html

# On macOS
open index.html

# On Linux
xdg-open index.html
```

Or drag and drop `index.html` into your browser window.

## Responsive Design

The website is fully responsive and optimized for:

| Device | Breakpoint | Layout |
|--------|-----------|--------|
| **Desktop** | > 768px | 4-column products, full navbar |
| **Tablet** | 600px - 768px | 2-column products, adapted layout |
| **Mobile** | < 600px | 1-column products, stacked layout |
| **Extra Small** | < 400px | Optimized for small screens |

### Features on Different Screens

- **Desktop**: Full navigation, multi-column layout, all features visible
- **Tablet**: Compact navigation, 2-column grid for products
- **Mobile**: Touch-friendly buttons, single column layout, optimized spacing
- **Extra Small**: Minimal padding, readable font sizes, fast loading

## Browser Compatibility

✅ Tested and supported on:

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile browsers (Chrome, Safari, Firefox Mobile)

## Features Explained

### Navigation
- Sticky navbar with logo and menu links
- Cart icon for shopping cart access
- Responsive menu for mobile devices

### Product Display
- **Featured Products Section** - 4 premium products with ratings and prices
- **Latest Products Section** - 12 new arrivals with detailed information
- **Product Cards** - Include image, name, description, 5-star rating, and price
- **Hover Effects** - Smooth animations on product hover

### Additional Sections

- **Categories** - Visual category showcase with images
- **Exclusive Offer** - Featured product (Smart Band 4) with description
- **Customer Testimonials** - 3 customer reviews with ratings
- **Newsletter** - Subscribe for updates and special offers
- **Footer** - Company info, quick links, social media, and copyright

## Accessibility

The website follows web accessibility best practices:

- ✓ Semantic HTML5 elements
- ✓ ARIA labels for interactive elements
- ✓ Descriptive alt text for images
- ✓ Proper heading hierarchy
- ✓ Color contrast compliance
- ✓ Keyboard navigation support
- ✓ Screen reader friendly

## Customization

### Changing Colors

Update the primary color in `style.css`:

```css
/* Find and replace #ff523b with your color */
.btn, .title::after, .ratings { color: #ff523b; }
```

### Adding Products

Edit the product cards in `index.html`:

```html
<div class="col-4">
    <img src="images/product-X.jpg" alt="Product Name">
    <h4>Product Title</h4>
    <p>Product Description</p>
    <div class="ratings" aria-label="4 out of 5 stars">
        <i class="bi bi-star-fill"></i>
        <!-- Add stars -->
    </div>
    <p>$Price</p>
</div>
```

### Updating Text

Simply edit the text content in `index.html`:
- Company name/tagline
- Product descriptions
- Customer testimonials
- Footer information

## Performance Tips

- Images are optimized for web
- CSS is minified and organized
- No external JavaScript dependencies
- Fast loading time
- Smooth animations using CSS transitions

## Future Enhancements

Potential features for future versions:

- [ ] Product filtering and search
- [ ] Shopping cart functionality
- [ ] Product detail pages
- [ ] User authentication
- [ ] Payment integration
- [ ] Backend database
- [ ] Admin dashboard
- [ ] Customer reviews system

## Troubleshooting

### Images Not Loading

- Check that the `images/` folder is in the same directory as `index.html`
- Verify image file names match exactly (case-sensitive)
- Ensure image files exist in the images folder

### Styles Not Applied

- Clear browser cache (Ctrl+Shift+Delete)
- Ensure `style.css` is in the same directory as `index.html`
- Check that CSS file path is correct in HTML

### Responsive Issues

- Test in different browsers
- Use browser DevTools (F12) to test different screen sizes
- Check that viewport meta tag is present in HTML head

## Resources

- [MDN Web Docs](https://developer.mozilla.org/) - HTML/CSS Reference
- [Bootstrap Icons](https://icons.getbootstrap.com/) - Icon Library
- [Google Fonts](https://fonts.google.com/) - Font Library
- [CSS Tricks](https://css-tricks.com/) - CSS Tutorials

## Author

**Aryan Gupta**

- Portfolio: [Your Portfolio Link]
- LinkedIn: [Your LinkedIn]
- GitHub: [Your GitHub]
- Email: [Your Email]

## License

This project is open source and available under the [MIT License](LICENSE).

## Contributing

Contributions are welcome! Feel free to:

1. Fork the project
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## Feedback

Have suggestions or found a bug? 

- Create an issue on GitHub
- Send an email with feedback
- Share your ideas for improvements

---

**Made with ❤️ by Aryan Gupta**

Last updated: January 8, 2026
