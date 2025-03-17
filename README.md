# Dice Simulator

A visually appealing interactive dice rolling simulation built with HTML, CSS, and JavaScript. This project features a sleek dark theme with glowing blue accents and realistic dice rolling animations.

## Features

- **Realistic Dice Simulation**: True-to-life representation of a six-sided die with correctly positioned dots
- **Smooth Rolling Animation**: Dynamic 3D rotation effects that gradually slow down to simulate real dice physics
- **Dark Theme Design**: Eye-friendly dark background with glowing blue accents
- **Responsive Feedback**: Visual and text feedback after each roll
- **Interactive Elements**: Hover effects and state changes for enhanced user experience
- **No Dependencies**: Built with vanilla HTML, CSS, and JavaScript – no external libraries required

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/mnalevanko/dice-simulator.git
   ```

2. Navigate to the project directory:

   ```bash
   cd dice-simulator
   ```

3. Open `index.html` in your browser or use a local server.

## Usage

- Click the "ROLL" button to start the dice rolling animation
- Wait for the animation to complete to see your result
- Roll again as many times as you want
- Hover over the dice to see subtle interaction effects

## Code Structure

The project consists of a single HTML file that includes embedded CSS and JavaScript:

- **HTML**: Creates the basic structure with a container, dice area, button, and result text
- **CSS**: Handles the dark theme styling, animations, and responsive effects
- **JavaScript**: Controls the dice behavior, random number generation, and animations

## Customization

### Changing Colors

To modify the color scheme, adjust these CSS variables in the style section:

```css
/* Background color */
body {
  background-color: #121212;
}

/* Accent color (currently blue) */
.dot {
  background-color: #4fc3f7;
}
button {
  background-color: #4fc3f7;
}

/* Container color */
.container {
  background-color: #1e1e1e;
}
```

### Adjusting Animation Speed

To change how fast the dice rolls, modify these values in the JavaScript:

```javascript
const maxRolls = 15 + Math.floor(Math.random() * 10); // Number of faces shown during roll
const initialSpeed = 60; // Starting speed (lower = faster)
```

## Browser Compatibility

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+
- Opera 50+

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Acknowledgments

- Inspired by classic dice games and modern web design principles

## Contact

Project Link: [https://github.com/mnalevanko/dice-simulator](https://github.com/mnalevanko/dice-simulator)
