# Aesthetic Coming Soon Page

This is a modern, interactive coming soon page featuring a glass-morphism design, animated particles, and elegant form interactions. The page is built with pure HTML, CSS, and JavaScript, requiring no external libraries or frameworks.

## Features

The page incorporates several sophisticated design elements:

A dynamic particle background system creates a subtle, animated atmosphere that responds to the viewport size. The particles float gracefully across the screen with varying sizes and opacity levels.

The central glass card component showcases advanced CSS effects including backdrop filters, dynamic glows, and smooth animations. It features a 3D floating animation that adds depth to the design.

The subscription form implements modern interaction design with animated focus states, loading feedback, and success animations. The email input and submit button both feature carefully crafted hover and active states.

For typography, the design uses Space Grotesk and Inter fonts to achieve a premium, contemporary feel. Text elements include gradient animations and thoughtful spacing for optimal readability.

## Setup Instructions

1. Download all the files and open `index.html` in a modern web browser. No server setup is required as this is a static page.

2. To customize the countdown date, locate the following line in the JavaScript section:
```javascript
const countdownDate = new Date().getTime() + 30 * 24 * 60 * 60 * 1000;
```
Modify this to your desired launch date.

3. To change the notification email collection endpoint, update the form submission event listener in the JavaScript section:
```javascript
document.querySelector('.subscribe-form').addEventListener('submit', (e) => {
    // Add your email collection logic here
});
```

## Browser Support

The page is optimized for modern browsers that support:
- CSS backdrop-filter
- CSS custom properties
- Modern JavaScript (ES6+)
- Canvas API

For older browsers, the design gracefully degrades while maintaining functionality.

## Mobile Optimization

The page is fully responsive and includes specific optimizations for mobile devices:
- Adjusted typography scales
- Refined touch targets
- Optimized animation performance
- Restructured layout for smaller screens

## Customization

To modify the color scheme, look for these CSS variables in the style section:
```css
background: linear-gradient(135deg, 
    #000000 0%, 
    #1a1a1a 50%,
    #262626 100%);
```

To adjust the particle system, modify these values in the JavaScript:
```javascript
const particles = Array.from({ length: 70 }, () => new Particle());
```

## Performance Notes

The page implements several performance optimizations:
- Hardware-accelerated animations
- Optimized particle system
- Efficient CSS transforms
- Controlled animation counts

## Footer Attribution

The footer includes the required attribution: "made with 🤍 by nishantawasthi"

## License

Feel free to use and modify this code while maintaining the footer attribution.

For questions or customization help, please reach out to the original creator.
