# Apple & Pear Detection (Freshness / Condition)

A small **computer vision** project that classifies **apples** and **pears** into simple freshness/condition categories using **OpenCV + HSV color thresholds**.

- **Apple**: classifies based on red tones (fresh / ripening / rotten).
- **Pear**: classifies based on detected **brown spots area (%)** (fresh / ripening / rotten).

> Note: This is a lightweight, rule-based approach (not ML). Results depend a lot on lighting, camera, and background.


## Project structure

- `manzana.py` → apple (manzana) classifier
- `pera_function.py` → pear (pera) classifier
- `main.py` → quick demo calls
- Sample images:
  - Apples: `manzana.jpg`, `manzana_not_fresh.jpg`, `manzana_podrida.jpg`
  - Pears: `pera_fresca.jpg`, `pera_3.jpg`, `image.png`

## Requirements

- Python **3.8+**
- Packages:
  - `opencv-python`
  - `numpy`
  - `matplotlib`


## Installation

(Optional) create and activate a virtual environment, then:

```bash
pip install opencv-python numpy matplotlib
