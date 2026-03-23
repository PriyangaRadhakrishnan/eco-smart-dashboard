# Energy Waste Prototype Walkthrough

I have successfully built and verified the Energy Waste Prototype! The prototype features a modern, glassmorphic UI that simulates a smart home energy monitor.

## ✨ Features
- **Modern UI**: Dark mode with neon accents and glassmorphism.
- **Carbon Dashboard**: Real-time CO2 footprint calculation based on device usage.
- **Smart Logic**:
    - **Empty Room Check**: Detects if devices (Lights/AC) are on in an unoccupied room.
    - **Daylight Optimization**: Suggests turning off lights when natural sunlight is available.
- **Carbon Savings**: Displays potential CO2 reduction when inefficiencies are found.
- **One-Click Optimization**: "Apply Carbon Optimization" button automatically switches off unnecessary devices to reduce your footprint.

## 📺 Demo & Verification

## ⚡ Refined AI Logic
The dashboard now uses high-precision formulas:
- **LED Lighting**: 0.015 kg CO2/hr
- **Air Conditioning**: 0.850 kg CO2/hr
- **Combined (LED + AC)**: 0.863 kg CO2/hr
- **Energy Conversion**: 1 kWh = 0.82 kg CO2
- **Cost Metric**: ₹8 / kWh

### Smart Rules
- **Waste Detection**: If the room is empty and any device is running, it's flagged as waste.
- **Status Messages**:
  - `Carbon footprint minimized ✅` (No waste)
  - `Energy waste detected ⚠️ Turn off devices` (Waste active)

## 🛠️ Implementation Details
The entire application is contained within a single `index.html` file using:
- **HTML5**: For structure.
- **Vanilla CSS3**: For the premium glassmorphic styling and animations.
- **Vanilla JavaScript**: For the energy detection, carbon calculation, and "Apply Optimization" feature.

## 📁 Source Code
You can find the local source code at [index.html](file:///c:/hackathon/index.html).
