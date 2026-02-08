# 🧮 Advanced Animated Calculator

A fully functional, beautifully designed calculator with both **Simple** and **Scientific** modes, featuring stunning gradient animations and an intuitive user interface.


## ✨ Features

### 🎨 Visual Design
- **Animated Gradient Background** - Continuously shifting colors creating a mesmerizing effect
- **Glass-morphism UI** - Modern frosted glass design with blur effects
- **Smooth Animations** - Hover effects, button ripples, and transitions
- **Shine Animation** - Dynamic light effect on the display screen
- **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices

### 🔢 Simple Calculator Mode
- Basic arithmetic operations (+, -, ×, ÷)
- Clear (AC) and Delete (DEL) functions
- Decimal point support
- Clean, intuitive 4-column grid layout
- Real-time calculation display

### 🔬 Scientific Calculator Mode
- **Trigonometric Functions**: sin, cos, tan
- **Logarithmic Functions**: log (base 10), ln (natural log)
- **Power Functions**: 
  - x² (square)
  - √ (square root)
  - x^y (custom power)
- **Advanced Operations**:
  - 1/x (reciprocal)
  - n! (factorial)
  - % (percentage)
- **Mathematical Constants**: π (pi), e (Euler's number)
- **Memory Functions**: MC (clear), MR (recall), M+ (add), M- (subtract)
- **Parentheses Support**: ( ) for complex expressions

## 🎯 Key Highlights

- ⌨️ **Full Keyboard Support** - Use your keyboard for faster input
- 🎭 **Dual Mode Interface** - Seamlessly switch between Simple and Scientific modes
- 💾 **Memory Functionality** - Store and recall values with visual indicator
- 🚨 **Error Handling** - Graceful error display with shake animation
- 🔢 **Number Formatting** - Automatic thousands separator for better readability
- 📱 **Mobile Optimized** - Touch-friendly buttons and responsive layout

## 🚀 Live Demo

[View Live Calculator](#) *(Add your hosted link here)*

## 📸 Screenshots

### Simple Mode
*(Add screenshot here)*

### Scientific Mode
*(Add screenshot here)*

## 🛠️ Technologies Used

- **HTML5** - Semantic structure
- **CSS3** - Advanced animations and gradients
- **Vanilla JavaScript** - No dependencies, pure ES6+

## 💻 Usage

### Keyboard Shortcuts

| Key | Function |
|-----|----------|
| `0-9` | Number input |
| `.` | Decimal point |
| `+` `-` `*` `/` | Basic operators |
| `Enter` or `=` | Calculate result |
| `Backspace` | Delete last digit |
| `Escape` | Clear all |

### Mouse/Touch Controls

- Click mode toggle buttons to switch between Simple and Scientific
- Click any button to perform the corresponding operation
- Hover over buttons for visual feedback

## 🎨 Color Palette

The calculator features a dynamic gradient color scheme:
- Primary: `#ee7752` → `#e73c7e` → `#23a6d5` → `#23d5ab`
- Accent: Purple-pink gradients for active states
- Buttons: Custom gradients for different function categories

## 📦 Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/advanced-calculator.git
```

2. Navigate to the project directory
```bash
cd advanced-calculator
```

3. Open `calculator.html` in your browser
```bash
open calculator.html
# or
start calculator.html
# or simply double-click the file
```

That's it! No build process or dependencies required.

## 🔧 Customization

### Changing Colors
Edit the gradient values in the CSS section:
```css
background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);
```

### Modifying Button Layout
Adjust the grid layout in the JavaScript functions:
```javascript
buttonsContainer.className = 'buttons scientific';
// Modify grid-template-columns in CSS for different layouts
```

### Adding New Functions
Add new calculator methods in the `Calculator` class and corresponding buttons in the HTML structure.

## 🌟 Features Breakdown

### Animation Effects
- **Gradient Background**: 15-second infinite animation cycle
- **Pulse Effect**: Active mode button scaling animation
- **Ripple Effect**: Button click wave animation
- **Shine Effect**: 3-second diagonal light sweep on display
- **Shake Effect**: Error state animation
- **Expand-In**: Smooth button grid appearance transition

### Calculator Logic
- Precision handling for decimal calculations
- Division by zero error detection
- Negative number support for square root validation
- Factorial calculation for positive integers only
- Trigonometric calculations in degrees (auto-converted from radians)

## 📱 Browser Compatibility

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Opera (latest)

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Ideas for Contribution
- Add more scientific functions (hyperbolic trig, permutations, combinations)
- Implement calculation history
- Add theme customization options
- Create additional color schemes
- Improve accessibility features
- Add unit tests

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**priyanshuxls**

- GitHub: [@priyanshuxls](https://github.com/priyanshuxls)
- Created with ❤️ and lots of gradients

## 🙏 Acknowledgments

- Inspired by modern calculator designs
- Gradient color palette inspired by UI trends
- Animation techniques from CSS animation best practices

## 📝 Changelog

### Version 1.0.0 (Current)
- ✅ Initial release
- ✅ Simple calculator mode
- ✅ Scientific calculator mode
- ✅ Animated gradient background
- ✅ Full keyboard support
- ✅ Memory functions
- ✅ Responsive design
- ✅ Error handling

---

### ⭐ If you find this project useful, please consider giving it a star!

**Made with 💜 by priyanshuxls**
