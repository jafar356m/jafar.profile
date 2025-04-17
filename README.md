# Personal Profile Website

A modern, responsive static website template for a personal portfolio.

## Features

- Clean and modern design
- Fully responsive layout
- Smooth scrolling navigation
- Skills showcase with animated progress bars
- Project portfolio gallery
- Contact form
- Social media links

## Technologies Used

- HTML5
- CSS3 with custom variables
- Vanilla JavaScript
- Font Awesome icons

## Getting Started

1. Clone or download this repository
2. Open `index.html` in your browser to view the website
3. Customize the content in the HTML file with your own information
4. Modify the styles in `css/styles.css` to match your preferences
5. Update the JavaScript functionality in `js/main.js` if needed

## Customization

### Changing Colors

The color scheme can be easily modified by changing the CSS variables in the `:root` selector in the `styles.css` file:

```css
:root {
    --primary-color: #3498db;
    --secondary-color: #2ecc71;
    --dark-color: #2c3e50;
    --light-color: #ecf0f1;
    /* ... other variables ... */
}
```

### Adding Projects

To add more projects to the portfolio section, duplicate the project card HTML structure in the `index.html` file:

```html
<div class="project-card">
    <div class="project-img">
        <img src="path/to/image.jpg" alt="Project Name">
    </div>
    <div class="project-info">
        <h3>Project Name</h3>
        <p>Project description goes here...</p>
        <div class="project-tags">
            <span>Tag 1</span>
            <span>Tag 2</span>
            <span>Tag 3</span>
        </div>
        <div class="project-links">
            <a href="#"><i class="fas fa-external-link-alt"></i> Live</a>
            <a href="#"><i class="fab fa-github"></i> Code</a>
        </div>
    </div>
</div>
```

## License

This template is free to use for personal and commercial projects. Attribution is appreciated but not required.

## Credits

- Placeholder images provided by [Placeholder.com](https://placeholder.com/)
- Icons from [Font Awesome](https://fontawesome.com/) 