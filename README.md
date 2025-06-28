# 🦖 Chrome Dino Game Bot 🤖

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)
![License](https://img.shields.io/badge/License-MIT-green)
![AutoPilot](https://img.shields.io/badge/AutoPilot-Enabled-red)

An intelligent bot that automates Google Chrome's dinosaur game using computer vision and precise input control.

## 🚀 Features

- **Pixel-perfect obstacle detection** using numpy array processing
- **Adjustable sensitivity** for different screen setups
- **Day/Night mode** compatible (configurable thresholds)
- **Efficient scanning** at 50-60 FPS
- **Clean interrupt handling** (Ctrl+C to stop)

## ⚙️ Installation

```bash
pip install -r requirements.txt
Requirements:

pyautogui>=0.9.53
pillow>=9.0.0
numpy>=1.22.0

Usage
Open Chrome and visit chrome://dino

Run the bot:
python dino_bot.py

Switch to game window within 3 seconds

🛠️ Configuration (in code)
python
# Detection parameters (adjust as needed)
self.dino_top = 400       # Vertical position
self.obstacle_left = 500   # Start of detection area
self.pixel_threshold = 50  # Lower = more sensitive (30-70)
self.cluster_threshold = 15 # Higher = more strict (10-20)
📊 Performance Metrics
Metric	Value
Avg Score	1500-2500
Reaction Time	15-25ms
Max Speed	60 FPS
