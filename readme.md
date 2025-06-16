# Sketchfab Screenshot Tool

A web-based tool for capturing high-resolution screenshots of 3D models from Sketchfab, recreating the functionality of the discontinued Sketchfab Labs Screenshots experiment.

🔗 **[Live Demo](https://github.com/LaurieAnnis/Sketchfab-Screenshot-Tool)** 

## Features

- 📸 **High-Resolution Screenshots** - Capture images up to 4096×4096 pixels
- 🎯 **Size Presets** - Quick selection for common resolutions (1024², 1920×1080, 2048², 4096²)
- 🔄 **Transparent Backgrounds** - Option to capture with transparent backgrounds
- ⚙️ **Post-Processing Controls** - Toggle visual effects on/off
- 📹 **Camera Controls** - Reset camera position and auto-rotate functionality
- ℹ️ **Model Information** - Display model name, author, and license details
- 📱 **Responsive Design** - Works on both desktop and mobile devices

## How to Use

1. **Enter Model URL**: Paste any Sketchfab model URL into the input field
   - Supports various URL formats: `sketchfab.com/3d-models/...`, `sketchfab.com/models/...`
2. **Configure Settings**: 
   - Choose screenshot resolution using presets or custom dimensions
   - Enable transparent background or post-processing effects
3. **Take Screenshot**: Click the "Take Screenshot" button to capture and auto-download
4. **Camera Controls**: Use reset camera or auto-rotate as needed

## Supported URL Formats

The tool accepts Sketchfab URLs in these formats:
- `https://sketchfab.com/3d-models/model-name-[32-character-id]`
- `https://sketchfab.com/models/[32-character-id]`
- `https://sketchfab.com/3d-models/[32-character-id]`

## Technical Details

- Built using the official **Sketchfab Viewer API v1.12.1**
- Pure HTML, CSS, and JavaScript - no build process required
- Uses modern browser APIs for file downloads
- Fully compliant with Sketchfab's Terms of Service

## Installation & Deployment

### GitHub Pages (Recommended)

1. Fork or clone this repository
2. Enable GitHub Pages in repository settings
3. Access your tool at `https://yourusername.github.io/repository-name`

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sketchfab-screenshot-tool.git
   cd sketchfab-screenshot-tool
   ```

2. Serve the files using any local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

3. Open `http://localhost:8000` in your browser

## Browser Compatibility

- **Chrome**: ✅ Fully supported
- **Firefox**: ✅ Fully supported  
- **Safari**: ✅ Fully supported
- **Edge**: ✅ Fully supported

*Note: Requires a modern browser with support for ES6+ JavaScript features*

## Legal & Attribution

This tool uses the **Sketchfab Viewer API** and is fully compliant with Sketchfab's Terms of Service:

- **Models and viewer technology** are provided by [Sketchfab](https://sketchfab.com)
- **Model licenses** vary by creator - check individual model pages for specific licensing
- **Tool respects** all Sketchfab API usage guidelines and attribution requirements

## Limitations

- Maximum screenshot resolution: 4096×4096 pixels (Sketchfab API limit)
- Transparent backgrounds require model reload to take effect
- Some models may have download/viewing restrictions based on their license
- API rate limits may apply for excessive usage

## Contributing

Contributions are welcome! Please feel free to:

1. **Report bugs** by opening an issue
2. **Suggest features** via the issues tab
3. **Submit pull requests** with improvements

### Development Guidelines

- Follow existing code style and structure
- Test with multiple Sketchfab models before submitting
- Ensure compliance with Sketchfab's Terms of Service
- Update documentation as needed

## Changelog

### v1.0.0 (Initial Release)
- ✨ Basic model loading and screenshot functionality
- ✨ Size presets and custom dimensions
- ✨ Transparent background support
- ✨ Post-processing controls
- ✨ Camera reset and auto-rotate
- ✨ Model information display
- ✨ Responsive design

## Support

If you encounter issues:

1. **Check the browser console** for error messages
2. **Verify the Sketchfab URL** is correct and publicly accessible
3. **Try a different model** to isolate the issue
4. **Open an issue** on GitHub with details about the problem

## Acknowledgments

- **Sketchfab Team** - For providing the excellent Viewer API
- **Original Sketchfab Labs** - For the inspiration from the discontinued Screenshots experiment
- **3D Community** - For sharing amazing models on Sketchfab

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**⚠️ Disclaimer**: This is an independent tool that uses Sketchfab's public API. It is not affiliated with or endorsed by Sketchfab, Inc.
