# 🧬 Counter-Current Multiplier Simulator

An interactive, educational simulation of the **Counter-Current Multiplier System** in the kidney's **Loop of Henle**. This tool visualizes the step-by-step mechanism that creates the medullary osmotic gradient essential for urine concentration.

![Loop of Henle Animation](https://img.shields.io/badge/Education-Physiology-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![HTML5](https://img.shields.io/badge/HTML5-Canvas-orange)

## 🎯 Features

- **Step-by-step visualization** of the counter-current multiplication process
- **Interactive controls** for auto-play, step forward/backward, and reset
- **Adjustable physiological parameters**:
  - Pump strength (active transport capacity)
  - Maximum gradient cap (simulates diuretic effects)
  - Washout controls (vasa recta blood flow simulation)
  - Particle movement speed
- **Live gradient analysis graph** with real-time plotting
- **Mobile-responsive design** optimized for both desktop and mobile devices
- **Offline capability** - works without internet connection

## 📚 Educational Purpose

This simulation is designed for **MBBS/medical students** studying renal physiology. It demonstrates:

1. **Descending limb**: Water-permeable segment where water exits by osmosis
2. **Ascending limb**: Water-impermeable segment with active NaCl pumping
3. **Interstitium**: Gradual buildup of medullary hyperosmolarity
4. **Single effect multiplication**: How small gradients multiply into large ones

## 🚀 Quick Start

### Option 1: Direct Use
Simply open `index.html` in any modern web browser.

### Option 2: Local Server
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

Then navigate to `http://localhost:8000`

### Option 3: GitHub Pages
Fork this repository and enable GitHub Pages in your repository settings.

## 🎮 How to Use

1. **Auto Play** (▶): Automatically cycles through all steps
2. **Step Forward** (⏭): Advance one step at a time
3. **Step Back** (⏮): Go back to previous step
4. **Reset** (↺): Return to initial state

### Understanding the Display

| Element | Description |
|---------|-------------|
| 💧 Blue droplets | Water molecules leaving descending limb |
| Na⁺ Yellow ions | Sodium being actively pumped from ascending limb |
| ⚡ Green pumps | Active Na⁺/K⁺/2Cl⁻ transporters |
| Color gradient | Osmolarity (blue=300 mOsm → orange=1200 mOsm) |

## ⚙️ Parameters Explained

| Parameter | Effect | Clinical Relevance |
|-----------|--------|-------------------|
| **Pump Strength** | Controls Vmax of active transport | Reduced in hypoxia, metabolic disorders |
| **Max Gradient Cap** | Limits single-effect gradient | Loop diuretics (furosemide) reduce this |
| **Washout** | Simulates medullary blood flow | High flow = gradient washout |

## 🏗️ Technical Details

- **Pure HTML/CSS/JavaScript** - No dependencies required
- **Canvas-based rendering** for smooth animations
- **Responsive design** with mobile-first approach
- **PWA-ready** with manifest support

## 📁 Project Structure

```
ccm-loop-of-henle/
├── index.html          # Main application (self-contained)
├── README.md           # This file
├── LICENSE             # MIT License
├── CONTRIBUTING.md     # Contribution guidelines
└── .gitignore          # Git ignore rules
```

## 🤝 Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

### Ideas for Enhancement
- [ ] Add collecting duct visualization
- [ ] Include ADH (vasopressin) effects
- [ ] Add quiz/assessment mode
- [ ] Support multiple languages
- [ ] Add audio explanations

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 👨‍⚕️ Author

**Dr. Diveen Sen Geeth**

Created as an educational tool for medical students studying renal physiology.

## 🙏 Acknowledgments

- Inspired by classic physiology textbooks (Guyton & Hall, Ganong)
- Built for the medical education community

---

*If you find this tool helpful, please consider giving it a ⭐ on GitHub!*
