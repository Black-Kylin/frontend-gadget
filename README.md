# Flight Information Display

A modern, elegant flight information display component built with HTML, CSS, and JavaScript. This project creates a visually appealing card that shows real-time flight progress between airports with a dynamic progress bar animation.

## Features

- Clean, modern dark-themed UI design
- Real-time flight progress tracking
- Animated progress bar
- Responsive layout
- Time zone difference display
- ETA countdown

## Preview

The display shows:
- Origin and destination airports (PVG → LHR)
- Local times for both cities
- ETA in destination time
- Time remaining until arrival
- Visual progress bar
- Time zone difference

## Installation

1. Clone this repository or download the files
2. Open `flight.html` in a modern web browser

## Usage

The component is self-contained in a single HTML file with embedded CSS and JavaScript. To use it:

```html
<!-- Include the entire flight.html file in your project -->
<!-- Or copy the relevant sections into your existing HTML -->
<div class="flight-card">
  <!-- Flight information content -->
</div>
```

## Customization

The component uses CSS variables and classes that can be easily customized:

- `.flight-card`: Main container styling
- `.airports`: Airport code display
- `.info`: City names and local times
- `.eta`: Estimated arrival time
- `.progress-bar`: Flight progress indicator

## Browser Support

Works in all modern browsers that support:
- CSS Flexbox
- CSS Gradients
- requestAnimationFrame API

## Development

The project includes configuration files for consistent code style:
- `.eslintrc.json` for JavaScript linting
- `.prettierrc` for code formatting

## License

MIT License - feel free to use and modify as needed.