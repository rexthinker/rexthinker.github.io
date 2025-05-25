# Rex-Thinker Project Website

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://rexthinker.github.io)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

A modern, interactive academic paper website for **"Rex-Thinker: Grounded Object Referring via Chain-of-Thought Reasoning"**. This project showcases cutting-edge research in AI reasoning with an elegant, responsive web interface featuring dynamic demonstrations and interactive examples.

## 🌟 Features

### 🎨 Modern Design
- **Dark theme** with gradient backgrounds and glassmorphism effects
- **Responsive design** that works on all devices
- **Smooth animations** and transitions
- **Professional typography** with custom font styling

### 🚀 Interactive Components
- **Live Reasoning Demo**: Watch Rex-Thinker analyze images step-by-step with typewriter effects
- **Auto-scrolling Carousel**: Showcases multiple examples with hover-to-pause functionality
- **Modal Dialogs**: Detailed reasoning processes with formatted text and images
- **Progress Indicators**: Visual feedback for processing states
- **Terminal Interface**: Code-like output styling for AI responses

### 📱 Technical Features
- **Pure HTML/CSS/JavaScript** - No frameworks required
- **Font Awesome Icons** for consistent iconography
- **Custom CSS animations** for enhanced user experience
- **Semantic HTML structure** for accessibility
- **Optimized performance** with efficient asset loading

## 🛠️ Setup & Installation

### Quick Start
1. **Clone the repository**:
   ```bash
   git clone https://github.com/IDEA-Research/rexthinker.github.io.git
   cd rexthinker.github.io
   ```

2. **Serve locally** (choose one method):
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

3. **Open in browser**: Navigate to `http://localhost:8000`

### GitHub Pages Deployment
This site is designed to work seamlessly with GitHub Pages:

1. Fork this repository
2. Go to Settings → Pages
3. Select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Your site will be available at `https://yourusername.github.io/rexthinker.github.io`

## 📂 Project Structure

```
rexthinker.github.io/
├── index.html              # Main HTML file
├── styles.css              # All CSS styles and animations
├── assets/                 # Image assets
│   ├── original_*.jpg      # Original images for examples
│   ├── box_hint*.jpg       # Box hint visualizations
│   ├── answer_*.jpg        # Final answer visualizations
│   ├── grounded_object_referring.jpg
│   ├── data_engine.jpg
│   └── two_stage.jpg
├── README.md               # This file
└── LICENSE                 # License file
```

## 🎯 Customization Guide

### Updating Paper Information
Edit the header section in `index.html`:

```html
<h1 class="paper-title">Your Paper Title</h1>
<div class="authors">
    <!-- Update author information -->
</div>
```

### Adding New Examples
1. **Add images** to the `assets/` folder
2. **Update the carousel** in `index.html`:
   ```html
   <div class="showcase-item">
       <div class="showcase-preview">
           <div class="image-container">
               <img src="assets/your_image.jpg" alt="Description">
           </div>
           <div class="text-preview">
               <p>Your question text</p>
           </div>
       </div>
   </div>
   ```
3. **Add corresponding modal** with reasoning process

### Modifying the Demo
Update the examples array in the JavaScript section:

```javascript
this.examples = [
    {
        originalImage: 'assets/your_original.jpg',
        boxHintImage: 'assets/your_hint.jpg',
        resultImage: 'assets/your_result.jpg',
        question: 'Your question',
        response: 'Your AI response with <think> tags'
    }
    // Add more examples...
];
```

### Styling Customization
Key CSS variables to modify in `styles.css`:

```css
/* Color scheme */
--primary-color: #3498db;
--secondary-color: #9b59b6;
--background-gradient: linear-gradient(135deg, #1a1a1a 0%, #2c3e50 100%);

/* Typography */
--main-font: 'Arial', sans-serif;
--code-font: 'Consolas', 'Monaco', 'Courier New', monospace;
```

## 🔧 Technical Details

### Performance Optimizations
- **Lazy loading** for images
- **CSS animations** with GPU acceleration
- **Efficient DOM manipulation** in JavaScript
- **Optimized asset delivery**

### Browser Compatibility
- ✅ Chrome 70+
- ✅ Firefox 65+
- ✅ Safari 12+
- ✅ Edge 79+

### Accessibility Features
- **Semantic HTML** structure
- **ARIA labels** for interactive elements
- **Keyboard navigation** support
- **Screen reader** friendly content

## 🚀 Advanced Features

### Auto-Scrolling Carousel
The carousel features:
- **Seamless infinite scrolling**
- **Mouse hover pause functionality**
- **Manual navigation with arrow buttons**
- **Smooth transitions** with easing

### Modal System
- **Multiple modal support**
- **Click outside to close**
- **Escape key handling**
- **Responsive layout** for different screen sizes

### Dynamic Demo
- **Typewriter effect** for text animation
- **Progress bar** with multiple stages
- **Image transitions** with fade effects
- **Processing indicators** with CSS animations

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch: `git checkout -b feature/amazing-feature`
3. **Commit** your changes: `git commit -m 'Add amazing feature'`
4. **Push** to the branch: `git push origin feature/amazing-feature`
5. **Open** a Pull Request

### Development Guidelines
- Follow existing code style and formatting
- Test on multiple browsers and devices
- Optimize images before adding to assets
- Document any new features or modifications

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Font Awesome** for providing excellent icons
- **Google Fonts** for typography options
- **GitHub Pages** for free hosting
- **The open source community** for inspiration and tools

## 📞 Contact

- **Paper**: [arXiv Link](https://arxiv.org/abs/your-paper-id)
- **Code**: [GitHub Repository](https://github.com/IDEA-Research/Rex-Thinker)
- **Demo**: [Live Demo](https://rexthinker.github.io)
---

⭐ **Star this repository** if you find it helpful!

Made with ❤️ by the Rex-Thinker Team
