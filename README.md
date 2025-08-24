# 2.4GHz-Modular-Parabolic-Dish-Antenna
3D-printed directional Wi-Fi antenna project with possibilities of various upgrades

This project showcases a **modular, 3D-printed parabolic dish antenna** optimized for 2.4GHz (Wi-Fi band) frequencies. Designed for experimentation and adaptability, it allows easy replacement of the dish, feed, and structural parts to support different frequencies and setups — including potential use cases in 5GHz or 5G ranges.

The antenna combines RF engineering principles with practical, low-cost materials and is intended for students, hobbyists, and network engineers interested in wireless signal enhancement.


-**ProjectGoal**

To create a functional, low-cost 2.4GHz directional antenna that is:
- **Modular** – parts can be swapped, resized, or upgraded
- **3D printable** – accessible and replicable with desktop 3D printers
- **Practical** – shows real signal gain in Wi-Fi environments

  


---

## 🛠️ Materials & Hardware

| Component                | Details                                                                 |
|--------------------------|-------------------------------------------------------------------------|
| **3D Printer**           | Creality Ender 3 V3 SE                                                   |
| **Filament**             | PLA                                                                     |
| **Dish Diameter**        | 30 cm                                                                    |
| **Feed Element (Dipole)**| ~31.5 mm copper wire (~1 mm diameter) with heat-shrink insulation       |
| **Can (Waveguide)**      | Tin can (82 mm diameter, ~116 mm depth), RP-SMA male connector attached |
| **Feed Placement**       | ~49 mm from can bottom (optimized for wave reflection and resonance)    |
| **Reflective Surface**   | Aluminum tape with electrically conductive adhesive                     |
| **Dish Shaft**           | Stainless steel rod (recommended over PLA for strength)                 |
| **Tripod Mount**         | 3D-printed nut adapter for phone/laser tripod compatibility             |
| **Adjustable Tilt**      | Wheel-based angle adjustment on the stand                               |

---

## ⚙️ Design Features

- **Modular construction**: All parts are designed for **easy assembly and replacement**:
  - Swap out dishes of different sizes by unscrewing the holder.
  - Replace or upgrade the feed can for higher frequencies (e.g., 5GHz).
  - Cantenna holder accepts different can diameters.
- **RF-Aware Feed Positioning**: Feed is carefully placed **~49 mm from the can bottom**, accounting for **reflected wave propagation**, not just 1/4 λ. This corrects a common mistake in similar builds.
- **Insulated Feed Element**: Copper feed is protected with heat-shrink tubing (<0.1 mm thick) to **prevent corrosion** while minimizing any capacitive interference.
- **Effective Reflector Surface**: Dish covered with **aluminum tape featuring conductive adhesive**, ensuring minimal signal loss across the parabolic surface.
- **Robust Stand Design**: Dish and shaft mount on a **metal support rod**, providing the strength to hold larger or heavier components.

---

## 📊 Performance Notes

Preliminary signal strength tests show enhanced directional reception in the 2.4GHz Wi-Fi band, with measurable gain compared to typical router antennas. Results may vary depending on local interference and test environment.

> *Further testing and dB gain measurements will be added in the `/Measurements/` folder.*

---

## 📁 Project Structure



