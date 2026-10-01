# 🌍 Weather Model Sandbox Game

An interactive, web-based meteorology simulation where you play with atmospheric physics and trigger immediate forecast duels between global and regional weather models. Inspired by *2D Weather Sandbox* and *Cyclone Simulator*.

## 🚀 Play Now

**[Click here to play the game!](https://github.io)**

## 🎮 How to Play
1. **Select a Grid Point:** Click anywhere on the global dark-themed map.
2. **Modify Environment:** Adjust the sliders in the sidebar panel:
   * **Temperature (°C):** Control the ambient heat.
   * **Dew Point (°C):** Set the moisture availability (cannot exceed temperature).
   * **Wind Speed (kt):** Increase synoptic dynamics and kinetic energy.
   * **SRH (m²/s²):** Crank up Storm-Relative Helicity for severe rotation.
3. **Run the Models:** Click **"Initialize Forecast Models"** to instantly generate and compare outputs.

## 🧠 Supported Weather Models
The sandbox simulates the distinct "personalities" and physical biases of the world's leading numerical forecast engines:
* **MONAN (Brazil):** Highly tuned for tropical monsoon convection and South American heat dynamics.
* **HRRR (USA):** Mesoscale specialist focused on CAPE/SRH interaction for severe convective outbreaks and tornadoes.
* **ECMWF (Europe):** Globally robust system highlighting structured frontal dynamics and cold-core snowfall setup.
* **GFS (USA):** Aggressive cyclogenesis simulation for rapid low-pressure developments and tropical waves.
* **ICON (Germany):** Crisp boundary layer physics detecting heatwaves and severe airmass boundaries.
* **ACCESS (Australia):** Tailored for southern hemisphere anomalies and extreme bushfire hazards.
* **GDPS (Canada):** Cold airmass specialist managing intense wind chills and blizzards.
* **MSM (Japan):** Hyper-focused on rapid orographic lift and devastating coastal rain deluge.

## 🛠️ Tech Stack
* **Language:** Vanilla JavaScript (ES6+)
* **Map Rendering:** [Leaflet.js](https://leafletjs.com) via OpenStreetMap & CartoDB Dark Matter tiles.
* **Styling:** CSS3 Flexbox with modern developer UI colors.

## 📜 License
This project is open-source under the MIT License. Feel free to fork, add complex parameterizations, or plug in live APIs!
