# ⚠️ Seismic Sentinel CF — Campi Flegrei

[![GitHub last commit](https://img.shields.io/github/last-commit/RobertoAbbruzzese/seismic-sentinel-cf)](https://github.com/RobertoAbbruzzese/seismic-sentinel-cf)
[![GitHub repo size](https://img.shields.io/github/repo-size/RobertoAbbruzzese/seismic-sentinel-cf)](https://github.com/RobertoAbbruzzese/seismic-sentinel-cf)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PWA](https://img.shields.io/badge/PWA-Compatible-5A0FC8)](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Glossary/HTML5)

![Visitors](https://api.visitorbadge.io/api/visitors?path=RobertoAbbruzzese%2Fseismic-sentinel-cf&label=Visitatori&countColor=%23263759)

> **Real-time seismic monitoring, early warning, and bradyseism for the Campi Flegrei volcanic area (Naples).**

## 📱 Project Description

This application turns your smartphone into a **seismic detection node** for the Campi Flegrei. It listens to ground vibrations via the accelerometer, recognizes the signature of an incoming earthquake (P-wave), and triggers an **audible, visual, and vocal alarm** with an **estimated countdown** before the arrival of the S-wave (the strong shock).

Furthermore, the app mirrors in real-time the official data from **INGV** (earthquakes from the last 7 days) and the **Vesuvius Observatory** (ground uplift / bradyseism), displaying everything on 2D maps and in an interactive **3D scene of the volcano**.

## 🚀 Main Features

- **Local seismic sensor** (v2.2): listens to the ground and alarms in advance.
- **Official INGV Data**: mirror of the earthquake and micro-shock list.
- **Live Bradyseism**: automatic reading of ground uplift from the OV page.
- **2D Map**: your location, epicenters, safety zones, and assembly points.
- **3D Volcano**: immersive visualization with hypocenters, P/S waves, and crustal structure.
- **Pro Mode (optional)**: integration with Cloudflare Worker for multi-device confirmation.
- **APK included**: compiled with APK_BUILD to run the app on Android **without CORS errors** (no server required).

## 📦 Download the APK

If you want to install the app directly on your Android phone (resolving Cross-Origin network issues), download the file:

➡️ **[Download SeismicSentinel.apk](./SeismicSentinel.apk)**

*Note: you may need to enable "Install from unknown sources" in your phone's settings.*

## 🖥️ Hardware on which it was developed

| Component | Specification |
| :--- | :--- |
| **CPU** | AMD FX-4300 (4 core, 3.8 GHz) |
| **RAM** | 12 GB DDR3 |
| **GPU** | NVIDIA GT 1030 (2 GB GDDR5) |
| **Storage** | SSD 120 GB + HDD ~290 GB |
| **System** | Windows 10/11 |

## 🤖 How it was made

This project was **developed entirely in a browser environment**, without local IDEs or toolchains. The source code (single HTML + CSS + JS file) was generated and refined through AI assistance (Large Language Model). Compilation into an APK was performed using the personal tool `APK_BUILD`.

## 🔗 Useful Links

- **Live Demo (GitHub Pages)**: [https://robertoabbruzzese.github.io/seismic-sentinel-cf/](https://robertoabbruzzese.github.io/seismic-sentinel-cf/)
- **LinkedIn Profile**: [Roberto Abbruzzese](https://www.linkedin.com/in/roberto-abbruzzese-aa3b343b6/)
- **License**: MIT (see `LICENSE` file)

---

## 📷 Photo

https://github.com/user-attachments/assets/549e9ba8-eac3-4509-a276-54a766140f54

<img width="1836" height="807" alt="Immagine" src="https://github.com/user-attachments/assets/45c68ae0-ce8c-41dd-b814-06b34577232a" />
<img width="1823" height="805" alt="Immagine2" src="https://github.com/user-attachments/assets/7d583034-38e4-4e8d-8832-732a626bcd4f" />
<img width="1822" height="793" alt="Immagine23" src="https://github.com/user-attachments/assets/dd215ae5-75eb-4339-8164-6a7e5ed86941" />
<img width="1839" height="825" alt="Immagine234" src="https://github.com/user-attachments/assets/59edee9e-9ba3-4cfc-99ae-ed9ed93dd37f" />


**⚠️ Disclaimer:** This tool is a personal aid based on public INGV data. It **DOES NOT REPLACE** official Civil Protection alerts. In case of emergency, always follow the instructions of the authorities.
