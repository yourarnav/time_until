# Chrono Nova ⏳✨

![Chrono Nova Preview](https://via.placeholder.com/800x500.png?text=Add+Your+App+Screenshot+Here)

A modern countdown timer with glowing progress rings, confetti celebrations, and dynamic event tracking. Perfect for milestones, deadlines, or special moments.

## 🌟 Features
- **Gradient Progress Rings** - Animated circular timers with custom gradients
- **Editable Event Titles** - Click-to-edit with auto-save functionality
- **Smart Input Controls** - Scroll wheel, arrow keys, and direct input support
- **Confetti Animation** - Particle effects on timer completion
- **Audio Alerts** - Customizable notification sound
- **Responsive Design** - Mobile-first, touch-friendly interface
- **Live Updates** - Smooth animations and real-time progress

## 🚀 Quick Start
1. Clone repo:
```bash
git clone https://github.com/yourarnav/time_until.git
```
2. Open `index.html` in any modern browser

## 🎮 How to Use
| Action | Instructions |
|--------|--------------|
| Set Time | Click any circle → Scroll/type/use arrows |
| Start/Pause | Toggle the Start button |
| Reset | Click Reset to clear all values |
| Edit Event | Click title/pencil icon → Type → Press Enter |

## 🎨 Customization
Modify CSS variables in `:root`:
```css
:root {
  --gradient-start: #40E0D0;  /* Progress ring start color */
  --gradient-middle: #4169E1; /* Middle gradient color */
  --background: #0A0A1F;      /* Background color */
  --ring-color: rgba(255,255,255,0.2); /* Ring base color */
}
```

**Replace Notification Sound**:
1. Add your `sound.mp3` file
2. Update audio source in HTML:
```html
<source src="your-sound.mp3" type="audio/mp3">
```

## 🛠️ Tech Stack
- HTML5
- CSS3
- JavaScript
- Web Audio API

## 🤝 Contributing
1. Fork the repository
2. Create your feature branch:
```bash
git checkout -b feature/AmazingFeature
```
3. Commit changes:
```bash
git commit -m 'Add some AmazingFeature'
```
4. Push to branch:
```bash
git push origin feature/AmazingFeature
```
5. Open a Pull Request

## 📜 License
Distributed under the MIT License. See `LICENSE` for details.

---

Made with ❤️ by [Arnav Attri](https://github.com/yourarnav)
[🔗 Live Demo](https://yourarnav.github.io/time_until) | [📧 Contact](https://github.com/yourarnav) | [🐛 Report Issue](https://github.com/yourarnav/time_until/issues)
