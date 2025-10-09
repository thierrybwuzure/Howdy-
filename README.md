# Howdy! - Thierry Bwuzure's Portfolio

A modern, responsive portfolio website showcasing web development projects and skills. Built with vanilla HTML, CSS, and designed with a focus on user experience and clean aesthetics.

## Features

- **Modern UI/UX**: Clean, professional design with smooth animations
- **Performance Optimized**: Fast loading with optimized images and CSS
- **Contact Form**: Contact form with validation
- **SEO Friendly**: Proper meta tags and semantic HTML structure

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla
- **Styling**: Custom CSS with CSS Grid and Flexbox
- **Typography**: Google Fonts (Poppins)
- **Icons & Images**: Custom logo and project screenshots
- **Version Control**: Git

## Project Structure

```
Howdy!/
├── index.html              # Main portfolio page
├── contact.html            # Contact form page
├── styles.css              # Main stylesheet
├── images/                 # Image assets
│   ├── TB transparent.png  # Logo variants
│   ├── portrait.JPG        # Profile photo
│   ├── profile_picture_*   # Additional profile images
│   └── *.png/*.jpg         # Project screenshots
└── js/                     # JavaScript files (future expansion)
```

## Design

The portfolio follows a modern, minimalist design approach with:

- **Color Palette**:

  - Light tones: Off-white (#fffaf0), Gold (#ffe7af), Bisque (#ffe4c4)
  - Blue spectrum: Light Blue (#3498db), Earth Blue (#287ab8), Deep Blue (#11466e)
  - Dark tones: Charcoal (#272727), Midnight (#343434)

- **Typography**: Poppins font family for clean, modern readability
- **Layout**: CSS Grid and Flexbox for responsive layouts
- **Animations**: Subtle fade-in effects and hover transitions

## Getting Started

### Prerequisites

- A modern web browser
- Local web server (recommended for contact form functionality)

## 🔧 Customization

### Adding New Projects

1. Add project images to the `images/` directory
2. Update the projects section in `index.html`:
   ```html
   <div class="project">
     <img src="images/your-project.png" alt="Project Name" />
     <h3 class="project-title">Your Project</h3>
     <p class="project-description">Project description...</p>
   </div>
   ```

### Updating Contact Information

Modify the contact details in `contact.html`:

```html
<p><a href="mailto:your.email@example.com">your.email@example.com</a></p>
```

### Color Customization

Update CSS custom properties in `styles.css`:

```css
:root {
  --white: #fffaf0;
  --gold: #ffe7af;
  --deep-blue: #11466e;
  /* Add your custom colors */
}
```

## Performance Optimizations

- **Images**: Optimized file sizes and formats
- **CSS**: Minified and organized for fast loading
- **Fonts**: Preconnected to Google Fonts for faster loading
- **Caching**: Proper cache headers for static assets

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

This project is open source and available under the [MIT License](LICENSE).

## Contributing

While this is a personal portfolio, suggestions and improvements are welcome!

## Contact

**Thierry Bwuzure**

- Email: bwuzure@gmail.com
- LinkedIn: [thierrybwuzure](https://www.linkedin.com/in/thierrybwuzure/)
- GitHub: [thierrybwuzure](https://github.com/thierrybwuzure)

---

_Built with ❤️ by Thierry Bwuzure_
