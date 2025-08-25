## 📊 Signal Testing & Comparison

Testing was conducted using:

- External USB Wi-Fi adapter with monitor mode (via `aircrack-ng`)
- `airodump-ng` for real-time signal strength (PWR)
- Controlled indoor setup with fixed placement
- ESSID "asdfgh"

| Antenna | Avg. PWR (dBm) | Notes |
|--------|----------------|-------|
| Omnidirectional | ~-33 dBm | Stable signal |
| 2.4GHz-Modular-Parabolic-Dish-Antenna | Peaks at **-26 dBm**, dips to -80 dBm | Strongest signal observed, but highly directional and sensitive to alignment |

### 🔍 Observations

- The custom antenna outperformed the omnidirectional one **in peak signal strength**.
- Oscillations in signal (from -26 to -80 dBm) were traced to:
  - **Environmental multipath reflections**
  - **Driver-level reporting variance** in `airodump-ng`
  - **High directionality**, making fine alignment crucial
- Polarization was correctly matched, and the feed was confirmed to be at the dish's focal point.

---

## 🧰 Tools Used

- `aircrack-ng` suite (`airodump-ng`, `airmon-ng`)
- `iwconfig` / `iw` for signal monitoring
- Linux (Debian-based distro)
- USB Wi-Fi adapter with monitor mode support


---


