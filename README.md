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

- The feed is tuned **not by a simple 1/4 wavelength formula**, but based on real reflective path inside the can.
- The copper feed element is covered with **heat-shrink tubing** (less than 0.1mm thick) to prevent corrosion, without significantly impacting electrical properties.
- The dish surface is made conductive to **reduce energy loss** as signals reflect across it.


Preliminary signal strength tests show enhanced directional reception in the 2.4GHz Wi-Fi band, with measurable gain compared to typical router antennas. Results may vary depending on local interference and test environment.




---

## ✅ Skills Demonstrated

- RF theory: feed tuning, reflection, wavelength alignment
- Mechanical design: adjustable mounts, modular holders
- 3D modeling & printing: PLA, design for strength
- Signal performance testing (RSSI)
- Materials choice for conductivity and mechanical strength
- Documentation and open-source sharing


---

## 📝 License

This project is open source under the **MIT License** — feel free to modify, share, or build on it, with credit.

---

## 📬 Contact

Feel free to open an issue or fork the repo if you'd like to contribute or ask questions.

---

## PhotosOfAntenna

Complete antenna mounted on the tripod:
https://github.com/SudoTraceRoute/2.4GHz-Modular-Parabolic-Dish-Antenna/blob/main/Photos_of_antenna/IMG_20250824_152351%20(1).jpg

3D printed parts for the antenna:
https://github.com/SudoTraceRoute/2.4GHz-Modular-Parabolic-Dish-Antenna/blob/main/Photos_of_antenna/IMG_20250716_165126%20(1).jpg

---

## 🎯 Why I Built This

This project was part of my hands-on learning in preparation for a career in IT and wireless networking.  
I have no formal IT degree, but I'm building and testing real hardware to deepen my knowledge in RF behavior, Wi-Fi diagnostics, Linux tooling, and network infrastructure.  


---

---

## ✅ Project Status: Complete

This hardware build is finished and has successfully demonstrated directional Wi-Fi reception improvements compared to standard omnidirectional antennas.

Further experimentation, signal testing, and network analysis will be explored in future, related projects using this antenna.









