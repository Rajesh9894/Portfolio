# Responsive Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Features a clean design with smooth animations and mobile-friendly navigation.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with smooth animations
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Smooth Scrolling**: Smooth navigation between sections
- **Contact Form**: Functional contact form with validation
- **Skills Showcase**: Grid layout for displaying skills and technologies
- **Project Gallery**: Responsive project cards with hover effects
- **Social Links**: Integration with social media platforms

## Technologies Used

- **HTML5**: Semantic markup and modern HTML features
- **CSS3**: Flexbox, Grid, animations, and responsive design
- **JavaScript**: ES6+ features for interactivity
- **Font Awesome**: Icons for skills and social media
- **Google Fonts**: Inter font family for modern typography

## File Structure

```
Portfolio/
├── index.html      # Main HTML file
├── styles.css      # CSS styles and responsive design
├── script.js       # JavaScript functionality
└── README.md       # Documentation
```

## Customization

### Personal Information
Update the following sections in `index.html`:

1. **Hero Section**:
   ```html
   <h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
   <h2 class="hero-subtitle">Your Profession</h2>
   <p class="hero-description">Your description here...</p>
   ```

2. **About Section**:
   ```html
   <p>Update your about text here...</p>
   <div class="about-stats">
       <div class="stat">
           <h3>50+</h3>
           <p>Projects Completed</p>
       </div>
       <!-- Update stats as needed -->
   </div>
   ```

3. **Skills Section**:
   ```html
   <div class="skill-card">
       <i class="fab fa-html5"></i>
       <h3>Your Skill</h3>
       <p>Skill description</p>
   </div>
   ```

4. **Projects Section**:
   ```html
   <div class="project-card">
       <div class="project-image">
           <img src="your-image-url" alt="Project Name">
       </div>
       <div class="project-content">
           <h3>Project Name</h3>
           <p>Project description</p>
           <div class="project-tech">
               <span>Tech 1</span>
               <span>Tech 2</span>
           </div>
           <div class="project-links">
               <a href="#" class="project-link">Live Demo</a>
               <a href="#" class="project-link">GitHub</a>
           </div>
       </div>
   </div>
   ```

5. **Contact Section**:
   ```html
   <div class="contact-item">
       <i class="fas fa-envelope"></i>
       <span>your.email@example.com</span>
   </div>
   <div class="contact-item">
       <i class="fas fa-phone"></i>
       <span>+1 (555) 123-4567</span>
   </div>
   <div class="contact-item">
       <i class="fas fa-map-marker-alt"></i>
       <span>Your Location</span>
   </div>
   ```

### Styling Customization

Update the color scheme in `styles.css`:

```css
:root {
    --primary-color: #4f46e5;
    --primary-hover: #4338ca;
    --secondary-color: #a5b4fc;
    --background-color: #f9f9f9;
    --text-color: #333;
}
```

### Adding New Sections

To add a new section:

1. Add the HTML structure in `index.html`
2. Add corresponding CSS styles in `styles.css`
3. Add any JavaScript functionality in `script.js`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Features

- **Lazy Loading**: Images load with fade-in effect
- **Smooth Animations**: CSS transitions and JavaScript animations
- **Optimized CSS**: Efficient styling with minimal redundancy
- **Mobile-First**: Responsive design approach

## Getting Started

1. Clone or download the project files
2. Open `index.html` in a web browser
3. Customize the content to match your personal information
4. Replace placeholder images with your actual project images
5. Update social media links and contact information

## Deployment

The portfolio can be deployed to:
- GitHub Pages
- Netlify
- Vercel
- Any static hosting service

Simply upload the files to your hosting platform of choice.

## License

This project is open source and available under the MIT License.

## Contributing

Feel free to submit issues and enhancement requests!
