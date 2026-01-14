# 🛠️ Tech Cart Inventory Management System

<div align="center">

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

**A single-file, browser-based inventory management system for industrial maintenance tech carts.**

[View Demo](#demo) • [Features](#features) • [Installation](#installation) • [Customization](#customization)

</div>

---

## 📖 The Problem

In industrial maintenance environments, technicians work across multiple shifts with different laptops and mobile tech carts. Each cart contains:

- **Specialized cables** (RS232, PLC interfaces, HMI cables, etc.)
- **Laptops** with varying software configurations
- **Different software versions** for automation systems

**The challenge:** When troubleshooting on the factory floor, technicians waste valuable time:
- Searching for the right cable
- Checking if specific software is installed
- Finding which cart has what equipment
- Remembering software versions across different machines

## 💡 The Solution

This **single HTML file** provides instant access to:
- Complete cable inventory for each cart
- Laptop specifications and storage info
- Full software lists with version numbers
- Real-time search across all categories

**No server required. No installation. Just open and use.**

---

## ✨ Features

### 🔍 Smart Search
Search across cables, software, and specifications instantly. Find exactly what you need without scrolling through lists.

### 📊 Multi-Shift Support
Track inventory for multiple carts/shifts with easy tab navigation. Each cart maintains its own:
- Cable inventory
- Laptop specs
- Installed software

### 🎯 Real-Time Stats
Quick glance dashboard showing:
- Total cables
- Software packages
- Available storage
- System RAM

### 📱 Responsive Design
Works on desktop browsers, tablets, and mobile devices. Perfect for the factory floor.

### 🎮 Hidden Easter Eggs
Because maintenance technicians deserve some fun too:
- **Konami Code** (↑↑↓↓←→←→BA) - Matrix effect
- **Secret Game** (Hold T+R+J+K, tap L twice) - Fat Maintenance Man mini-game

---

## 🚀 Installation

### Option 1: Direct Use
1. Download `index.html`
2. Double-click to open in any browser
3. Done!

### Option 2: Deploy to Cart Laptops
1. Copy `index.html` to each maintenance laptop
2. Create a desktop shortcut
3. Optionally set as browser homepage

### Option 3: Network Share
1. Place `index.html` on a shared network drive
2. All technicians can access the same version

---

## ⚙️ Customization

### Adding Your Equipment

Edit the `shiftData` object in the JavaScript section:

```javascript
const shiftData = {
    '1st': {
        name: '1st Shift Cart - Station A',
        laptop: 'Laptop A',
        computer: 'MAINT-LAPTOP-01',
        cables: [
            'Your Cable 1',
            'Your Cable 2',
            // Add more cables...
        ],
        specs: {
            manufacturer: 'LENOVO',
            model: 'Your Model',
            processor: 'Your Processor',
            ram: '16.0 GB',
            os: 'Windows 11 Enterprise',
            totalSpace: '951.65 GB',
            freeSpace: '700.00 GB',
            percentFree: '73.57%',
            ip: '(Network Configured)',
            subnet: '/24',
            gateway: '(Gateway Configured)'
        },
        software: {
            'Category Name': [
                'Software 1 (v1.0)',
                'Software 2 (v2.5)',
            ],
            // Add more categories...
        }
    },
    // Add more shifts/carts...
};
```

### Customizing Appearance

The CSS is fully contained in the `<style>` block. Key customization points:

```css
/* Main gradient background */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Accent color (teal) */
color: #4fd3a7;

/* Change company branding */
.company-brand { /* Your company styling */ }
```

---

## 🎮 Easter Eggs

### Matrix Effect
Enter the Konami Code: `↑ ↑ ↓ ↓ ← → ← → B A`

### Fat Maintenance Man Game
1. Hold down: `T + R + J + K`
2. While holding, tap `L` twice
3. Catch food before time runs out!

**Game Controls:**
- `A/D` or `Arrow Keys` - Move left/right
- `Spacebar` - Jump (double-tap for fast fall)
- `R` - Restart after game over
- `ESC` - Exit game

---

## 📋 Industrial Software Supported

This system is designed to track common industrial automation software including:

| Category | Examples |
|----------|----------|
| **PLC Programming** | GX Works2/3, CX-One, KV Studio, Sysmac Studio |
| **HMI Design** | GT Designer3, EBPro, EZTouch Editor |
| **Vision Systems** | IV-Navigator, pylon Camera Suite |
| **Servo/Motion** | RT ToolBox3, MR Configurator |
| **Networking** | AutoID Network Navigator |

---

## 🏭 Use Cases

- **Manufacturing Plants** - Track PLC/HMI programming cables and software
- **Automotive** - Manage robot programming interfaces
- **Food & Beverage** - Track clean-room compliant equipment
- **Pharmaceutical** - Maintain validated software inventories
- **Logistics** - Track barcode/vision system equipment

---

## 🤝 Contributing

Contributions welcome! Ideas for improvement:

- [ ] Print-friendly inventory reports
- [ ] QR code generation for cart labels
- [ ] Export to CSV/Excel
- [ ] Multi-language support
- [ ] Dark/light theme toggle
- [ ] Local storage for preferences

---

## 📄 License

MIT License - Use freely for personal or commercial purposes.

---

## 🙏 Acknowledgments

**Made by Technicians, for Technicians.**

Built to solve a real-world problem: wasting time searching for the right cable or wondering which laptop has what software. This tool pays for itself the first time it saves a technician from walking back to the office.

---

<div align="center">

**⭐ Star this repo if it saves you time on the factory floor! ⭐**

</div>
