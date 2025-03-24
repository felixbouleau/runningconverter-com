# Runningconverter.com

A stupidly simple website to convert running paces and race times, available on https://www.runningconverter.com/.

## About

This is a lightweight web application that helps runners convert between different pace units (min/km and min/mile) and calculate times for various race distances (5K, 10K, half marathon, and marathon).

## Local Development

### Prerequisites

- [Node.js](https://nodejs.org/) (latest LTS recommended)
- npm (comes with Node.js)

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/felixbouleau/runningconverter-com.git
   cd runningconverter-com
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

### Development

This is a static HTML/CSS/JS site that uses Tailwind CSS and DaisyUI for styling:

1. To build the CSS:
   ```bash
   npx tailwindcss -o styles.css --minify --watch
   ```

2. To serve the site locally, you can use any static file server. For example:
   ```bash
   # Using npx and serve (no installation required)
   npx serve
   
   # Or if you have Python installed
   python -m http.server
   ```

3. Open your browser and navigate to the local server address (typically http://localhost:3000 or http://localhost:8000).

### Deployment

The site is static HTML, CSS, and JavaScript, so it can be deployed to any static hosting service like GitHub Pages, Netlify, Vercel, or a traditional web host.

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

Pardon my ugly JavaScript.