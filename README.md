# Stream Background Generator

An Electron-based application for creating beautiful, animated backgrounds for streaming and virtual meetings. Generate dynamic backgrounds with customizable dots, strings, particles, and gradients.

![Stream Background Generator Screenshot](docs/screenshot.png)

## 🤖 AI-Powered Development

This application was developed entirely using AI assistance (Claude 3.5 Sonnet) through pair programming. The AI helped with:
- Application architecture and design
- Code implementation
- Bug fixes and optimizations
- Documentation

## ✨ Features

- Real-time animated backgrounds
- Multiple animation types:
  - Pulsing dots
  - Wave patterns
  - Swaying motion
  - Spiral effects
  - Bouncing elements
  - Ripple patterns
- Customizable elements:
  - Dot size, spacing, and color
  - String connections with adjustable properties
  - Floating particles with various behaviors
  - Dynamic gradient backgrounds
- Multiple aspect ratio support (16:9, 9:16, 1:1, Twitter banner)
- High-quality capture mode
- Preview window for streaming software integration
- FPS counter for performance monitoring

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher)
- [npm](https://www.npmjs.com/) (usually comes with Node.js)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/cartcodes/background-generator.git
cd background-generator
```

2. Install dependencies:
```bash
npm install
```

3. Start the application:
```bash
npm start
```

### Building for Distribution

To create distributable packages:
```bash
npm run build
```

This will create platform-specific packages in the `dist` directory.

## 🎮 Usage

1. Launch the application
2. Customize your background using the control panel on the left
3. Click "Start Capture" to open a preview window
4. In your streaming software (OBS, etc.):
   - Add a "Window Capture" source
   - Select the "Stream Preview" window
   - Use as your background or virtual camera input

## 🛠️ Development

The application is built with:
- Electron
- HTML5 Canvas
- Modern JavaScript
- CSS3 with custom properties

### Project Structure

```
background-generator/
├── main.js           # Electron main process
├── dot.html          # Main application interface
├── package.json      # Project configuration
└── README.md        # Documentation
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 🙏 Acknowledgments

- Developed with AI assistance (Claude 3.5 Sonnet)
- Built with Electron and modern web technologies
- Inspired by the streaming community's needs 