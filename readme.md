# Battery Monitor

A clean, minimalist web application that displays real-time battery information for devices supporting the Battery Status API. Built with vanilla JavaScript and CSS.

Online Demo: https://steveseguin.github.io/charging/

![Preview](https://github.com/user-attachments/assets/95642ac9-05b2-43e2-8c1e-c2c132b1150a)

## Features

- Real-time battery level visualization
- Charging status indicator with animation
- Low battery warning indicator
- Dark theme interface
- Responsive design
- No dependencies required

## Installation

1. Clone the repository
```bash
git clone https://github.com/steveseguin/battery-monitor.git
```

2. Open `index.html` in a web browser

That's it! No build process or dependencies needed.

## Usage

The application will automatically detect and display your device's battery information if the Battery Status API is supported by your browser.

The interface shows:
- Current battery percentage
- Visual battery level indicator
- Charging status with animated indicator
- Low battery warning (red indicator when below 20%)

## Browser Support

The Battery Status API is supported in:
- Chrome 38+
- Firefox 31+
- Opera 25+
- Android Browser 4.4+
- Chrome for Android 38+

Note: Safari and iOS browsers do not support the Battery Status API.

## Development

The entire application is contained in a single HTML file with embedded CSS and JavaScript. To modify:

1. Open `index.html` in your preferred editor
2. CSS styles are in the `<style>` section
3. JavaScript code is in the `<script>` section

## License

MIT

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Acknowledgments

- Built using the [Battery Status API](https://developer.mozilla.org/en-US/docs/Web/API/Battery_Status_API)
