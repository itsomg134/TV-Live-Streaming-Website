# TV Live Streaming Website

A modern, responsive web application for browsing and watching live TV channels. Built with vanilla HTML, CSS, and JavaScript.

![TV Live Streaming Preview](https://placehold.co/800x450/0b0d11/e50914?text=TV+Live+Streaming+Demo)

## Features

- **Live Channel Browsing** – Browse through a grid of available TV channels with live status indicators
- **Video Playback Controls** – Play, pause, seek, volume control, and fullscreen support
- **Keyboard Shortcuts** – Press the spacebar to play/pause the current stream
- **Responsive Design** – Optimized for desktop, tablet, and mobile devices
- **Visual Feedback** – Active channel highlighting, live badges, and smooth hover animations
- **Channel Information** – Display channel name, category, and logo with the current stream

## Technologies Used

- **HTML5** – Semantic markup
- **CSS3** – Modern styling with Flexbox and Grid
- **JavaScript (ES6)** – Dynamic content and interactivity
- **Font Awesome 6** – Icon library
- **HTML5 Video API** – Video playback controls

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/tv-live-streaming.git
   cd tv-live-streaming
   ```

2. **Open the application**
   - Simply open `index.html` in your preferred web browser
   - Or use a local development server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using VS Code Live Server extension
     # Right-click on index.html and select "Open with Live Server"
     ```

3. **Start streaming** – Browse channels and click on any to start watching!

## Project Structure

```
tv-live-streaming/
├── index.html          # Main HTML file with embedded CSS and JavaScript
├── README.md           # Project documentation
└── assets/             # (Optional) Additional assets
    └── videos/         # Video files
```

## 🔧 Configuration

### Adding New Channels

To add new channels, modify the `channels` array in the JavaScript section of `index.html`:

```javascript
const channels = [
    { 
        id: 7,
        name: 'Channel Name',
        category: 'Category',
        logo: 'URL_TO_LOGO_IMAGE',
        videoSrc: 'URL_TO_VIDEO_STREAM',
        poster: 'URL_TO_POSTER_IMAGE'
    },
    // Add more channels...
];
```

### Customizing the Player

You can customize the video player by modifying the CSS variables and styles in the `<style>` section:

```css
:root {
    --primary-color: #e50914;
    --background-dark: #0b0d11;
    --card-background: #191d26;
    /* Add your custom variables */
}
```

## Usage

### Basic Controls

| Control | Action |
|---------|--------|
| **Play/Pause Button** | Toggle video playback |
| **Click on Video** | Toggle video playback |
| **Spacebar** | Toggle video playback |
| **Progress Bar** | Click to seek to specific time |
| **Volume Icon** | Toggle mute/unmute |
| **Fullscreen Icon** | Enter/exit fullscreen mode |
| **Channel Cards** | Click to switch to that channel |

### Keyboard Shortcuts

- `Space` – Play/Pause
- `F` – Fullscreen (not implemented, but you can add it)
- `M` – Mute/Unmute (not implemented, but you can add it)

## Browser Support

| Chrome | Firefox | Safari | Edge | Opera |
|--------|---------|--------|------|-------|
| ✅     | ✅      | ✅     | ✅   | ✅    |

*Requires HTML5 video support and modern ES6 features.*

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🐛 Known Issues

- Video sources are currently using placeholder URLs – replace with actual stream URLs
- Autoplay may be blocked by browsers – user interaction is required
- Some video formats may not be supported across all browsers

## 📝 Future Enhancements

- [ ] Add channel categories filter
- [ ] Implement search functionality
- [ ] Add EPG (Electronic Program Guide)
- [ ] Support for multiple video resolutions
- [ ] Add Chromecast support
- [ ] Implement user authentication
- [ ] Add favorite channels feature
- [ ] Real-time channel status updates

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👏 Credits

- Icons by [Font Awesome](https://fontawesome.com/)
- Video sample from [W3Schools](https://www.w3schools.com/html/mov_bbb.mp4)
- Placeholder images from [Placehold.co](https://placehold.co/)

## 📧 Contact

Your Name – [@yourtwitter](https://twitter.com/yourtwitter) – email@example.com

Project Link: [https://github.com/yourusername/tv-live-streaming](https://github.com/yourusername/tv-live-streaming)

---

**Note**: Replace placeholder URLs and contact information with your actual details before deploying. This application is designed for demonstration purposes and requires real video streams to function as a production service.
