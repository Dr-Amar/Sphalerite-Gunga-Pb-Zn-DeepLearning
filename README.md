
# Ore Genesis and Critical Metal Enrichment in Gunga Pb-Zn Deposit, Pakistan (Deep Learning Study)

This repository accompanies the peer-reviewed article:

**Ore genesis and critical metal enrichment using deep learning algorithms in Gunga Pb-Zn deposit, Southern Pakistan: Constraints from sphalerite geochemistry and isotopic compositions**  
📝 *Published in Journal of Geochemical Exploration (2025)*  
🔗 [DOI: 10.1016/j.gexplo.2025.107771](https://doi.org/10.1016/j.gexplo.2025.107771)

---

## 📌 Project Summary

This study presents a novel integration of **deep learning algorithms** with **sphalerite geochemistry** and **S–Pb isotopes** to classify ore genesis and assess critical metal enrichment in the Gunga Pb-Zn deposit, part of the Lasbela-Khuzdar metallogenic province in Southern Pakistan.

A deep neural network model was trained on a global dataset of 99 Pb-Zn deposits (n ≈ 3800) and applied to new in-situ trace element data from Gunga sphalerite samples. The results offer robust insights into:

- Metallogenic classification (CD-type)
- Formation conditions (temperature, redox, sulfur fugacity)
- Geochemical indicators of **Ge, Cd, Ag, Sb** enrichment

---

## 📁 Repository Structure

```
Gunga-Pb-Zn-DeepLearning/
│
├── paper/        → Published article PDF
├── data/         → Geochemical datasets (trace elements, S & Pb isotopes)
├── figures/      → High-res figures from the publication
├── notebooks/    → Jupyter notebooks or model training scripts
├── LICENSE       → MIT / CC BY 4.0 License
└── README.md     → This file
```

---

## 🧠 Machine Learning Highlights

- **Model**: Deep Neural Network (12 inputs → 2 hidden layers → 5-class output)
- **Accuracy**: 94.73% on test set
- **Classes**: SEDEX, MVT, Skarn, VMS, Epithermal
- **Key Discriminators**: Cd, Ge, Sb, Ag (enriched); In, Ga (depleted)

---

## 🔍 Key Findings

- **Deposit Type**: Clastic-dominated (CD-type), supported by geochemistry and ML
- **Mineralization Temperatures**:
  - Lower Zone: 180–200°C
  - Upper Zone: 130–180°C
- **S Sources**: Combination of Bacterial and Thermochemical Sulfate Reduction (BSR + TSR)
- **Pb Source**: Upper continental crust (based on isotopic signatures)
- **Ge Enrichment Drivers**: High sulfur fugacity, low temperature, and reduced environment

---

## 🧪 Data Contents

- Sphalerite minor and trace element data (LA-ICP-MS)
- δ34S values for sphalerite and barite
- Pb isotope ratios (²⁰⁶Pb/²⁰⁴Pb, ²⁰⁷Pb/²⁰⁴Pb, ²⁰⁸Pb/²⁰⁴Pb)
- Classification labels from model output

---

## 🛠️ Technologies Used

- Python, NumPy, Pandas, Scikit-learn
- Keras (TensorFlow backend)
- LA-ICP-MS and EPMA data acquisition
- Geological and isotopic interpretation

---

## 📚 Citation

If you use this work, please cite the original publication:

```
Gul, M. A., Zhang, H., Yang, Y., et al. (2025). Ore genesis and critical metal enrichment using deep learning algorithms in Gunga Pb-Zn deposit, Southern Pakistan. Journal of Geochemical Exploration, 275, 107771. https://doi.org/10.1016/j.gexplo.2025.107771
```

---

## 🔓 License

- **Code**: [MIT License](https://opensource.org/licenses/MIT)
- **Data & Figures**: [CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/)

---

## 🙋‍♂️ Contact

For questions, collaborations, or data access, please contact:

**Dr. Muhammad Amar Gul**  
Email: `amar_geologist@yahoo.com`  
Affiliations: University of Science and Technology of China 

---
