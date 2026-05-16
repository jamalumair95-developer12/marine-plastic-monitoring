# 🚁 Automated Marine Plastic Monitoring
> *MSc Research Project | Cranfield University*

## 📌 Overview
This project presents an integrated system combining **Drone Technology, YOLOv11 Deep Learning, and TSP Route Optimization** to automatically detect, map, and monitor marine plastic pollution. Validated at **Sand Haven Beach, UK**, covering 6 high-risk pollution hotspots.

## ✨ Key Features
✅ **AI Detection**: Custom-trained YOLOv11 model → **97.3% Precision | 97.6% Recall | 98.7% mAP@50**
✅ **Route Optimization**: TSP algorithm → **68% reduction** in flight distance (10.8km → 3.4km), **32% energy saved**
✅ **Spatial Mapping**: Interactive maps showing hotspots & optimized flight paths
✅ **Temporal Analysis**: Compare pollution levels between surveys 📉📈
✅ **Visual Dashboard**: Folium-based interactive visualization

## 📊 Results
- Domain-specific dataset performed **149.2% better** than general-purpose datasets (e.g. TACO)
- Flight time reduced from 40 mins → 18 mins
- System can distinguish real pollution changes from natural variation

## 🛠️ Tech Stack
- Python, YOLOv11 (Ultralytics), Roboflow
- Folium, NumPy, SciPy
- Google Colab, NVIDIA A100 GPU

## 📄 Publication
**Title**: *Automated Marine Plastic Monitoring*
**Authors**: Jamal Umair Mohammed, Venkatraman Renganathan, Sabyasachi Mondal
**Affiliation**: Cranfield University, UK

---

### 📂 Files Included
- `Marine_Plastic_Monitoring.ipynb` → Full Colab notebook
- `Jamal_Rita_Conference_2025.pdf` → Full research paper
- `/images/` → Maps, detection outputs, and results
