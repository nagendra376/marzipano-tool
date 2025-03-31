# Marzipano Tool

A browser-based tool for creating 360° virtual tours. Process panoramas and export a web application powered by the Marzipano viewer.

## Features

- Process panoramic images directly in the browser
- Support for equirectangular and cube face formats
- Add info hotspots and link hotspots
- Set custom initial views
- Export complete web application
- No server-side processing - all work done locally
- Customizable through HTML, CSS, and JavaScript

## File Requirements

- **Supported Formats:**
  - Sphere (equirectangular) images
  - Cube face images
- **Image Specifications:**
  - Equirectangular aspect ratio must be 2:1
  - Cube faces must use suffixes: _b, _d, _f, _r, _t, _u
  - JPEG or TIFF format
  - Maximum sphere size: 23000x11500 pixels
  - Maximum cube size: 16384x16384 pixels

## Usage

1. **Adding Panoramas:**
   - Drag and drop files onto the window
   - Or use the "Select files" button
   - Files are processed locally, not uploaded to any server

2. **Editing:**
   - Rename panoramas
   - Set initial viewing angles
   - Add information hotspots
   - Create links between panoramas

3. **Exporting:**
   - Click "Export" to generate a web application
   - Download includes all necessary files
   - Customize further by editing the exported code

## Local Development

1. Clone the repository:
```bash
git clone [repository-url]
cd marzipano-tool
```

2. Open `index.html` in a modern web browser

## Deployment

### Vercel Deployment

1. Install Vercel CLI:
```bash
npm install -g vercel
```

2. Deploy:
```bash
vercel
```

### Netlify Deployment

1. Install Netlify CLI:
```bash
npm install -g netlify-cli
```

2. Deploy:
```bash
netlify deploy --prod
```

## Browser Support

- Google Chrome (latest version)
- Mozilla Firefox (latest version)
- Requires WebGL support
- Requires little-endian system

## Credits

- Marzipano Viewer: [https://www.marzipano.net](https://www.marzipano.net)
- Original development by Google Inc.

## Libraries Used

- Knockout.js
- Hammer.js
- FileSaver.js
- Sortable

## License

This project includes multiple open-source components:
- Marzipano Tool: Copyright 2016 Google Inc.
- Various components under MIT license
- See LICENSES.txt for detailed licensing information

## Support

For issues and feature requests, please create an issue in the repository.

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request
