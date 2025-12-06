# 🌠 Shooting Stars - Disney Style Animation

A beautiful, immersive night sky animation featuring shooting stars, a glowing moon, and twinkling stars created purely with HTML and CSS. This project showcases Disney-style smooth animations with dreamy clouds drifting across a moonlit sky.

## 🔗 Live Demo

**[View Live Demo](https://kiran-kata.github.io/shooting-stars/)**

Experience the magical night sky animation in action!

## ✨ Features

- **Shooting Stars Animation**: Multiple shooting stars with radiant glows moving diagonally across the sky
- **Glowing Moon**: A realistic moon with detailed craters and soft luminous glow
- **Dreamy Clouds**: Dark night clouds gently floating around the moon
- **Twinkling Stars**: 20+ static stars with magical Disney-style twinkle effects
- **Pure CSS**: No JavaScript required - all animations done with CSS keyframes
- **Responsive Design**: Adapts to different screen sizes

## 🎨 Visual Elements

### Night Sky
- Deep blue-black radial gradient background
- Creates realistic depth and atmosphere

### Moon
- 180px diameter with realistic coloring
- Multiple crater details for authenticity
- Multi-layered glow effect
- Positioned in top-left area

### Clouds
- Semi-transparent dark clouds with blur effects
- Smooth floating animation (45-second cycle)
- Strategically positioned around the moon

### Shooting Stars
- 8 shooting stars with varied trajectories
- Diagonal movement from top-right to bottom-left
- Radiant golden-white glow effects
- Staggered animation delays for natural appearance

### Static Stars
- 20 twinkling stars scattered across the sky
- Varied sizes and brightness levels
- Disney-style scale and opacity animations

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required!

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Kiran-kata/shooting-stars.git
cd shooting-stars
```

2. Open `index.html` in your web browser:
```bash
# On Linux/Mac
open index.html

# Or use a local server
python3 -m http.server 8000
# Then visit http://localhost:8000
```

## 📁 Project Structure

```
shooting-stars/
│
├── index.html          # Main HTML structure
├── styles.css          # All CSS animations and styling
└── README.md          # Project documentation
```

## 🎭 Animation Details

### Shooting Stars
- **Duration**: 2.8s - 3.5s per star
- **Timing Function**: ease-out for natural deceleration
- **Direction**: Top-right to bottom-left diagonal
- **Effect**: Fade-in at start, fade-out at end

### Twinkling Stars
- **Duration**: 3s per cycle
- **Timing Function**: ease-in-out
- **Effects**: Scale (0.8x - 1.4x) and opacity changes
- **Glow**: Dynamic box-shadow animation

### Clouds
- **Duration**: 45s per cycle
- **Movement**: Gentle horizontal and vertical drift
- **Blur**: 3px for dreamy effect
- **Opacity**: 0.7 - 0.8 for semi-transparency

## 🎨 Color Palette

- **Background**: `#0d1b2a`, `#08111a`, `#020408` (dark blue-black gradient)
- **Moon**: `#ffffff` to `#beb9a0` (white to beige gradient)
- **Stars**: Pure white (`#ffffff`) with warm glow
- **Clouds**: Dark blue-gray with 50-80% opacity

## 🛠️ Customization

### Adjust Number of Stars
Edit `index.html` to add or remove star elements:
```html
<div class="star star-21"></div>
```

Then add corresponding CSS positioning in `styles.css`:
```css
.star-21 { top: 40%; left: 55%; animation-delay: 1.4s; }
```

### Change Animation Speed
Modify animation durations in `styles.css`:
```css
/* Faster shooting stars */
animation: shoot 2s ease-out infinite;

/* Slower cloud movement */
animation: cloudFloat 60s ease-in-out infinite;
```

### Adjust Moon Size
Change moon dimensions:
```css
.moon {
    width: 250px;  /* Increase for larger moon */
    height: 250px;
}
```

## 🌟 Browser Compatibility

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Opera (latest)

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Kiran-kata**
- GitHub: [@Kiran-kata](https://github.com/Kiran-kata)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 💡 Inspiration

This project was inspired by Disney's magical animation style and the natural beauty of starry night skies. The goal was to create an immersive, peaceful atmosphere using only HTML and CSS.

## 📸 Screenshots

The animation features:
- A serene night sky with a glowing moon
- Shooting stars streaking across the darkness
- Twinkling static stars creating depth
- Dreamy clouds drifting past the moon

---

⭐ If you like this project, please give it a star on GitHub!
