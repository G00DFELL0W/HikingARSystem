# HikingARSystem

An Augmented Reality (AR) system for hikers, overlaying GPS-linked data and GIFs on a device’s camera feed. Labels plants and trailheads within 10 meters.

## Features
- GPS tracking and proximity-based overlays.
- GIF support for AR graphics.
- AI-driven labeling for plants.
- Modular design with mock modules.

## Setup
1. Clone: `git clone https://github.com/yourusername/HikingARSystem.git`
2. Install: `pip install -r requirements.txt`
3. Run: `python hiking_ar_system.py`

## Usage
```python
app = HikingARSystem()
app.link_data_to_position((37.7751, -122.4196, 0), {"type": "plant", "name": "Pine"}, "pine.gif")
asyncio.run(app.run())
