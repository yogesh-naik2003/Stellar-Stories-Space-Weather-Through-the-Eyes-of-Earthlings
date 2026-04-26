# 🌟 Stellar Stories: Space Weather Through the Eyes of Earthlings

A cinematic, interactive storytelling website that brings the wonders of space weather phenomena to life through immersive visual experiences.

![Project Status](https://img.shields.io/badge/status-active-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34C26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

---

## 📖 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage Guide](#usage-guide)
- [Technologies](#technologies)
- [Customization](#customization)
- [Browser Support](#browser-support)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

---

## 🎯 Overview

**Stellar Stories** is a single-page, interactive storytelling website that explores the fascinating phenomena of space weather. The project presents three compelling chapters:

- **Aurora** - The mesmerizing dance of the Northern and Southern Lights
- **CME (Coronal Mass Ejection)** - Powerful bursts of energy from the Sun
- **Tricky Tech** - How space weather affects our technology and daily lives

This website combines cinematic visuals, responsive design, and smooth interactions to create an educational yet engaging experience for users of all ages interested in astronomy and space science.

---

## ✨ Features

### Core Features
- 📺 **Three Interactive Chapters** - Each with high-quality descriptive imagery and corresponding video content
- 🎬 **Local Video Playback** - Smooth, efficient video playback directly from your server
- 🌌 **Cinematic Background** - Full-screen background video with elegant dark overlay ensuring text readability
- 📱 **Responsive Design** - Seamlessly adapts to desktop, tablet, and mobile devices
- ✨ **Smooth Interactions** - Beautiful hover effects and CSS transitions for enhanced user experience
- 🔘 **Video Controls** - Easy-to-use close button for managing video playback
- ⚙️ **Auto-Loop Background** - Background video continuously loops for uninterrupted atmosphere
- 🎨 **Modern UI** - Clean, intuitive interface designed for optimal user engagement

---

## 📁 Project Structure

```
stellar-stories/
│
├── README.md                    # Project documentation (this file)
├── index.html                   # Main HTML file - entry point of the website
├── styles.css                   # CSS styling and responsive layouts
├── script.js                    # JavaScript for interactivity
│
├── images/                      # Chapter thumbnail images
│   ├── aurora.jpg               # Aurora chapter thumbnail
│   ├── cme.jpg                  # CME chapter thumbnail
│   └── trickytech.jpg           # Tricky Tech chapter thumbnail
│
└── videos/                      # Video content directory
    ├── aurora.mp4               # Aurora chapter video
    ├── cme.mp4                  # CME chapter video
    ├── trickytech.mp4           # Tricky Tech chapter video
    └── bg.mp4                   # Homepage background video
```

---

## 🚀 Installation

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, Safari)
- A code editor (VS Code, Sublime Text, etc.) - optional for customization
- Local server (optional, but recommended for testing videos locally)

### Step-by-Step Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yogesh-naik2003/Stellar-Stories-Space-Weather-Through-the-Eyes-of-Earthlings.git
   cd Stellar-Stories-Space-Weather-Through-the-Eyes-of-Earthlings
   ```

2. **Verify Folder Structure**
   Ensure the following directory structure is maintained:
   - All images in the `images/` folder
   - All videos in the `videos/` folder
   - HTML, CSS, and JS files in the root directory

3. **Add Media Files** (if not included)
   - Place your chapter videos and images in their respective folders
   - Ensure filename consistency with HTML references

4. **Open in Browser**
   - Simply double-click `index.html`, or
   - Use a local server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Python 2
     python -m SimpleHTTPServer 8000
     
     # Using Node.js (with http-server installed)
     npx http-server
     ```
   - Navigate to `http://localhost:8000` in your browser

---

## 📚 Usage Guide

### Playing Chapter Videos
1. The homepage displays three chapter cards with thumbnail images
2. Hover over any chapter card to see smooth scaling and shadow effects
3. Click on a chapter card to start playing its corresponding video
4. The video player will appear below the chapter container with autoplay enabled

### Controlling Videos
- **Play a Chapter**: Click on any chapter thumbnail
- **Close Video**: Click the "Close Video" button to hide the player
- **Background Video**: Plays automatically on page load and loops indefinitely

### Navigation Tips
- The background video creates an immersive atmosphere while exploring chapters
- All transitions are smooth for a premium viewing experience
- Mobile users can tap on chapter cards just like desktop users

---

## 🛠️ Technologies

### Frontend Stack
| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic page structure, video embedding, form elements |
| **CSS3** | Styling, animations, hover effects, responsive layouts, overlay effects |
| **JavaScript (ES6+)** | Video playback control, event handling, DOM manipulation, smooth scrolling |

### Key Techniques Used
- **CSS Grid/Flexbox** - For responsive layouts
- **CSS Animations** - For smooth transitions and hover effects
- **Video API** - Native HTML5 video element manipulation
- **Event Listeners** - For interactive user interactions
- **Media Queries** - For mobile responsiveness

---

## 🎨 Customization

### Replacing Videos
1. Add your new video files to the `videos/` folder
2. Open `index.html` with a text editor
3. Locate the video `src` attributes:
   ```html
   <video src="videos/aurora.mp4"></video>
   ```
4. Update the filename to match your new video
5. Save and refresh your browser

### Changing Chapter Images
1. Replace image files in the `images/` folder
2. Ensure new images have the same filename, or update `<img src>` tags in HTML
3. Keep images at consistent dimensions for best visual results

### Styling Adjustments
The `styles.css` file contains customizable properties:
- **Colors**: Update background colors, text colors, overlay opacity
- **Transitions**: Modify hover animation speed (currently `0.3s`)
- **Shadows**: Adjust box-shadow values for different depth effects
- **Font**: Change typography to match your branding
- **Layout**: Modify grid templates for different chapter card arrangements

Example CSS customization:
```css
.chapter-card {
    transition: all 0.3s ease;  /* Change duration here */
    box-shadow: 0 10px 30px rgba(0,0,0,0.3);  /* Adjust shadow */
}
```

### Adding New Chapters
1. Duplicate a chapter card in the HTML
2. Update the image and video references
3. Modify the chapter title and description
4. Add corresponding CSS styling if needed

---

## 🌐 Browser Support

| Browser | Desktop | Mobile |
|---------|---------|--------|
| Chrome | ✅ Fully Supported | ✅ Fully Supported |
| Firefox | ✅ Fully Supported | ✅ Fully Supported |
| Safari | ✅ Fully Supported | ⚠️ Limited (autoplay restrictions) |
| Edge | ✅ Fully Supported | ✅ Fully Supported |
| Opera | ✅ Fully Supported | ✅ Fully Supported |
| IE 11 | ❌ Not Supported | - |

### Mobile Considerations
- Background video may not autoplay on some mobile devices due to browser security policies
- Muted autoplay is required for iOS Safari
- Touch interactions work seamlessly on all modern mobile browsers
- Videos are optimized for various network speeds

---

## 🔮 Future Enhancements

### Planned Features
- [ ] **Animated Transitions** - Smoother transitions when switching between videos
- [ ] **Lightbox Modal** - Display videos in a professional lightbox popup for a more cinematic effect
- [ ] **Audio Integration** - Background music and ambient sounds for immersive storytelling
- [ ] **Cloud Hosting** - Host videos on CDN (YouTube, Vimeo, AWS S3) for faster streaming
- [ ] **Interactive Elements** - Click-sensitive hotspots within videos
- [ ] **Analytics** - Track user engagement and chapter popularity
- [ ] **Multiple Languages** - Localization for international audiences
- [ ] **Social Sharing** - Easy sharing options for chapters
- [ ] **Dark/Light Mode** - Theme toggle for user preferences
- [ ] **Accessibility Features** - Captions, audio descriptions, keyboard navigation

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request with a clear description

Please ensure your contributions:
- Follow the existing code style
- Include meaningful commit messages
- Test across different browsers and devices
- Update documentation as needed

---

## 📄 License

This project is licensed under the **MIT License** - see the LICENSE file for details.

### MIT License Summary
You are free to:
- ✅ Use, copy, modify, merge, publish, distribute, and sublicense the code
- ✅ Use this project for personal and commercial purposes

Under the condition:
- ⚖️ Include the original license and copyright notice

---

## 📧 Contact & Support

For questions, suggestions, or issues:
- **GitHub Issues**: [Open an issue](https://github.com/yogesh-naik2003/Stellar-Stories-Space-Weather-Through-the-Eyes-of-Earthlings/issues)
- **Author**: [@yogesh-naik2003](https://github.com/yogesh-naik2003)

---

## 🙏 Acknowledgments

- Space weather data and educational insights from NASA and NOAA
- Icon and badge resources from Shields.io and various open-source communities
- Special thanks to all contributors and users who provide feedback

---

## 📊 Project Statistics

- **Language**: HTML5, CSS3, JavaScript
- **Repository**: [Stellar-Stories-Space-Weather-Through-the-Eyes-of-Earthlings](https://github.com/yogesh-naik2003/Stellar-Stories-Space-Weather-Through-the-Eyes-of-Earthlings)
- **Last Updated**: 2026
- **Repository ID**: 1070013599

---

**⭐ If you find this project helpful, please consider giving it a star on GitHub!**

---

*Made with ❤️ by [Yogesh Naik](https://github.com/yogesh-naik2003)*
