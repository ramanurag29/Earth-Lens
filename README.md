# 🌍 Earth-Lens

> **A cost-effective, real-time Earth observation system using publicly accessible satellite signals and open source technologies.**

---

## Overview

**Earth-Lens** presents the **design** and **implementation** of a complete system for **acquiring** and **enhancing real-time Earth imagery** transmitted by **NOAA (National Oceanic and Atmospheric Administration)** weather satellites — specifically **NOAA 15**, **NOAA 18**, and **NOAA 19** — via their **Automatic Picture Transmission (APT)** signals.

Utilizing publicly available **WebSDR platforms** and **open-source decoding tools**, analog **APT signals** are **captured**, **processed**, and **converted** into visible **satellite images**.

---

## Technical Highlights

###  Signal Processing
- **Capture:** NOAA **APT** signals are received from **WebSDR** sources.  
- **Decoding:** Signals are processed through **open-source decoding tools** to reconstruct visible imagery.  

###  Image Enhancement
- **Noise Reduction:** Implemented using **Gaussian** and **Median filtering**.  
- **Line Reconstruction:** The **Hough Transform** is used to detect and repair **corrupted line segments** in the imagery.  
- **Contrast Optimization:** Enhancement techniques improve overall **visual clarity** of received images.

### Image Segmentation & Mapping
- **K-Means Clustering:** Applied to classify and segment key **geographic features** such as:
  - **Land**
  - **Water bodies**
  - **Cloud formations**

---

##  Applications

The **Earth-Lens system** provides practical exposure to **satellite communication** and **remote sensing**, while promoting a **cost-effective approach** to **Earth observation** using **publicly accessible technologies**.

###  Educational Use
- Supports **learning** in fields like **signal processing**, **image enhancement**, and **geospatial analysis**.

###  Environmental Insights
- Enables **weather monitoring**, **environmental change detection**, and **geographic visualization** for research and analysis.

---

## Future Scope

- Integration with **real-time decoding pipelines** using **SDR hardware** or **WebSDR APIs**.  
- Implementation of **AI-based segmentation models** (e.g., U-Net) for improved accuracy.  
- Addition of **georeferencing modules** to map decoded imagery onto real-world coordinates.  
- Expansion toward **multi-satellite data fusion** for enhanced environmental analytics.

---

## 📖 Summary

**Earth-Lens** bridges the gap between **satellite signal acquisition**, **image processing**, and **geospatial analysis**, demonstrating that **open-source tools** and **accessible technologies** can be harnessed for meaningful **Earth observation** and **educational innovation**.

