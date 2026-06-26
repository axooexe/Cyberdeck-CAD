<h1 align="center">Cyberdeck CAD</h1>

### Serial Experiments Lain Cyberdeck

A custom, compact cyberdeck built around the Raspberry Pi 3 B+ and a 2.8" SPI touch display, featuring laser-cut housing panels inspired by the classic anime *Serial Experiments Lain*.

> "Present Day, Present Time. HAHAHAHA..."

---

## 🛠 Features & Specifications

* **Single Board Computer:** Raspberry Pi 3 Model B+
* **Display:** 2.8-inch SPI TFT Touch Screen Display
* **Chassis Design:** Custom interlocking laser-cut plates featuring custom line art (Lain portrait, Navi theme elements, and iconic quotes).
* **Portability:** Designed as a compact, standalone terminal unit.

---

## 📐 Hardware Components & Bill of Materials (BOM)

| Component | Description | Qty |
| :--- | :--- | :--- |
| **Raspberry Pi 3 B+** | Main single-board computer | 1 |
| **2.8" SPI Display** | ILI9341-based SPI screen (with resistive touch) | 1 |
| **Laser-cut Panels** | 3mm acrylic or plywood panels (Top, Bottom, Spacers) | 1 set |
| **M2.5 / M3 Standoffs** | For mounting the Pi and stacking the frame panels | As needed |
| **Micro SD Card** | 32GB+ pre-loaded with Raspberry Pi OS | 1 |

---

## ⚙️ Software Setup & Display Configuration

Because the 2.8" display runs over the **SPI interface** (rather than HDMI), you will need to configure the driver overlays to get a display output.

