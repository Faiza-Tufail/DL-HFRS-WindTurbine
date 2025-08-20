# Deep Learning-Based Hyperbolic Fuzzy Rough Sets (DL-HFRS) for Wind Turbine Health Monitoring

This repository contains the implementation of the **DL-HFRS framework**, which integrates **entropy-driven hyperbolic fuzzy rough sets** with **deep learning models** for **wind turbine health monitoring** using SCADA data.  
The goal is to achieve reliable fault detection, predictive maintenance, and interpretable results under uncertainty.

---

## 📌 Features
- ✅ **Entropy-weighted hyperbolic fuzzy rough set model**  
- ✅ **Deep learning integration** (MLP & LSTM)  
- ✅ **Fuzzy labels** (0.0, 0.5, 1.0) for uncertainty-aware prediction  
- ✅ **SHAP explainability** for feature interpretation  
- ✅ **Robust performance** under noisy SCADA data  

---

## 📂 Repository Structure
- `DLHFRS.ipynb` → Main Google Colab notebook for experiments  
- `requirements.txt` → Python dependencies  
- `README.md` → Project description and usage instructions  

---

## ⚙️ Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Faiza-Tufail/DL-HFRS-WindTurbine.git
cd DL-HFRS-WindTurbine
2️⃣ Install dependencies
```bash
pip install -r requirements.txt
3️⃣ Run on Google Colab
Open DLHFRS.ipynb in Google Colab

Upload your SCADA dataset or link from Google Drive

Run all cells to train and evaluate the model

📊 Results
📉 Achieved low prediction error (MAE ≈ 0.0241)

🔍 Demonstrated interpretability using SHAP

⚡ Showed robust fault detection under uncertainty in SCADA data

📝 Citation
If you use this code, please cite the following:

bibtex
@article{tufail2025dlhfrs,
  title={Deep Learning-Based Hyperbolic Fuzzy Rough Sets for Wind Turbine Health Monitoring},
  author={Tufail, Faiza and Collaborators},
  year={2025},
  journal={Under Review}
}
📧 Contact
Maintainer: Dr. Faiza Tufail
📩 Email: faizatufail85@gmail.com
🌐 GitHub: Faiza-Tufail
