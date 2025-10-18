# 🌐 PixMetron

**PixMetron** is a imaging and measurement platform designed for precision, performance, and extensibility.
It provides developers and engineers with a powerful foundation for industrial and scientific image analysis — from interactive measurement to calibration, visualization, and data export.

---

## ✨ Core Features

* **High-Precision Measurement** — pixel-accurate tools for distance, angle, circle, and ROI measurement.
* **Calibration Engine** — multi-point and scale-based calibration for true-to-unit geometry.
* **Viewport System** — smooth pan-zoom interaction with sub-pixel accuracy and DPI awareness.
* **PMX Format** — lightweight, structured container for images, calibration data, and measurements.
* **Quality Scoring** — assess image sharpness, tilt, and clarity for optimal measurement accuracy.
* **Extensible Architecture** — plug-in modules for CAD import, large-image handling, reporting, and automation.

---

## 🧱 Architecture Highlights

PixMetron follows a modular, layered design:

```
Core  →  Geometry  →  Measurement
        ↑         ↘
   Transform     Rendering
        ↑             ↘
     IO / PMX      Studio (UI)
```

Each module is self-contained, versioned, and designed for long-term compatibility — ensuring that developers can extend, embed, or integrate PixMetron in their own systems.

---

## 🔒 Editions

PixMetron offers multiple editions sharing the same core:

| Edition    | Description                                                       |
| ---------- | ----------------------------------------------------------------- |
| **Free**   | Essential measurement tools, calibration, and PMX format support. |
| **Pro**    | Adds large-image support, reporting, and CAD import.              |
| **Studio** | Full professional suite with point-cloud and automation modules.  |

---

## ⚙️ Technology Stack

* **.NET 8 / WPF** for desktop precision rendering
* **C# modular architecture** with strong separation of domains
* **Open configuration system** using JSON and signed capability policies
* **Cross-module extensibility** for developers and OEMs

---

## 🌍 Vision

PixMetron aims to make **industrial-grade image measurement** accessible, reliable, and developer-friendly —
a toolkit that empowers engineers, researchers, and creators to measure, analyze, and visualize the world with accuracy.

---

© 2025 PixMetron Project — Precision Beyond Pixels
