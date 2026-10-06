<h1 align="center">Róbert Hagovský</h1>

<p align="center">
  <strong>CNC Motion Control • ESP32-S3 • grblHAL • CAD/CAM • Computer Vision • Automation</strong>
</p>

<p align="center">
  I build practical systems where mechanics, electronics, firmware and software have to work together on real machines.
</p>

<p align="center">
  <img alt="C" src="https://img.shields.io/badge/C-embedded-informational">
  <img alt="C++" src="https://img.shields.io/badge/C%2B%2B-firmware-informational">
  <img alt="Python" src="https://img.shields.io/badge/Python-automation-informational">
  <img alt="ESP32-S3" src="https://img.shields.io/badge/ESP32--S3-motion_control-informational">
  <img alt="grblHAL" src="https://img.shields.io/badge/grblHAL-CNC-informational">
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-tools-informational">
</p>

---

## 🚧 Project Alfa 2030

**Project Alfa** is my long-term autonomous robotic woodworking workshop project.

The target is a modular production chain where the machine does more than execute G-code:

```text
CAD → CAM → motion control → sensing / vision → automation → production
```

The work spans CNC mechanics, embedded control, ESP32 firmware, custom CAM, computer vision, laser systems, 3D printing and production automation.

## 🔬 Current upstream work

I am currently developing and physically testing an **experimental ESP32-S3 motion stack for grblHAL**.

The work explores:

- analytic **S-curve / jerk-limited motion**
- **Fixed-Time Motion** at a 1 kHz sampling grid
- **ZV input shaping**
- trajectory smoothing
- ESP32-S3 STEP/DIR integration
- host-side motion, timing and safety regression tests

The work is being discussed publicly with the grblHAL project:

- **grblHAL Discussion #222:** [ESP32-S3 experimental motion stack](https://github.com/grblHAL/ESP32/discussions/222)
- **Review branch:** [experimental-motion-s3](https://github.com/Robik123445/ESP32/tree/experimental-motion-s3)
- **Full experimental snapshot:** [ESP32-Experimental](https://github.com/Robik123445/ESP32-Experimental)

> Current hardware status: initial tests on a real CNC show smoother and quieter NEMA23 motion with TB6600-class drivers. Performance tuning and broader physical acceptance testing are still in progress.

## 🧰 Featured engineering projects

| Project | What it is | Stack / focus |
|---|---|---|
| [**ESP32-Experimental**](https://github.com/Robik123445/ESP32-Experimental) | Experimental grblHAL motion-control stack for ESP32-S3 | C, ESP-IDF, grblHAL, S-curve, FTM, input shaping |
| [**ESP32**](https://github.com/Robik123445/ESP32) | My grblHAL ESP32 fork used for upstream-comparable development | C, ESP32-S3, grblHAL |
| [**Cam-slicer-2.0**](https://github.com/Robik123445/Cam-slicer-2.0) | Custom CAM / machine workflow tooling with GRBL sender, probing and vision integration | Python, CAM, G-code, FastAPI |
| [**Vision-cnc**](https://github.com/Robik123445/Vision-cnc) | CNC vision subsystem with YOLO segmentation, calibration and operator tooling | Python, YOLO, OpenCV, PySide6 |
| [**Polarne-cnc**](https://github.com/Robik123445/Polarne-cnc) | SVG-to-polar GRBL laser workspace | Python, PySide6, GRBL, geometry |
| [**Web-vizualizer**](https://github.com/Robik123445/Web-vizualizer) | Browser-based visual editor for arranging decorative elements | JavaScript, Node.js |

## ⚙️ What I work on

- CNC motion planning, jerk control and STEP/DIR execution
- ESP32 / ESP32-S3 firmware and hardware integration
- grblHAL experiments and machine-control features
- custom CAD/CAM workflows and G-code generation
- Python tooling, APIs and production automation
- computer vision for CNC and robotics
- laser systems, sensors and embedded electronics
- AI-assisted engineering workflows

## 🧪 Engineering approach

I prefer systems that can be **built, measured and tested on hardware**.

A typical loop is:

```text
prototype → instrument → test → break assumptions → fix → automate → repeat
```

Software-only validation is useful, but the final judge is the machine.

## 🧱 Tech stack

`ESP32` `ESP32-S3` `grblHAL` `C` `C++` `Python` `FastAPI` `PySide6` `OpenCV` `YOLO` `Onshape` `FeatureScript` `G-code` `CNC` `Laser` `3D Printing` `Automation`

---

<p align="center">
  <strong>Róbert Hagovský • Slovakia</strong><br>
  <em>Build it. Measure it. Break it. Fix it. Automate it.</em>
</p>
