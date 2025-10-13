# Machine Learning Guided Multi-Parameter Design of 5G Sub-Band Antennas

**A simulation-based approach to optimize 5G sub-band microstrip patch antennas using machine learning for efficient wireless communication.**

---

## 📘 Overview
This project explores a **machine learning–guided design methodology** for optimizing **5G sub-band microstrip patch antennas**.  
By combining electromagnetic simulations with data-driven optimization, the approach accelerates the antenna design process, achieving better performance with fewer iterations.  
The target operating frequency is **around 3.5 GHz**, suitable for **5G, WiFi, and WiMAX** applications.

---

## 🚀 Key Features
- 🤖 Machine learning–assisted antenna optimization  
- ⚙️ Multi-parameter design exploration (patch size, substrate height, feed position, etc.)  
- 📡 Focused on the 3.5 GHz 5G sub-band  
- 📊 Predictive modeling for return loss and gain  
- ⏱️ Significant reduction in simulation time and manual tuning  
- 🧩 Simulation-based study without physical fabrication  

---

## 🧩 Design Methodology
1. **Parameter Definition:** Identify key antenna parameters influencing performance.  
2. **Data Generation:** Perform electromagnetic simulations to create a dataset of input parameters and output metrics.  
3. **Model Training:** Use regression and neural network models to learn parameter-performance relationships.  
4. **Optimization:** Predict and refine design parameters using trained ML models.  
5. **Validation:** Validate optimized results through additional simulations in HFSS or CST.

---

## ⚙️ Tools and Technologies
- **Ansys HFSS / CST Microwave Studio** — EM simulation and validation  
- **Python / MATLAB** — Machine learning model development  
- **Scikit-learn / TensorFlow / Keras** — Regression and prediction models  
- **NumPy / Pandas / Matplotlib** — Data handling and visualization  

---

## 📊 Performance Summary
| Parameter | Result |
|------------|---------|
| Frequency Band | ~3.5 GHz |
| Return Loss (S11) | < −25 dB |
| Gain | ~5.2 dBi |
| Bandwidth | ~500 MHz |
| Polarization | Linear |

---

## 🧠 Machine Learning Role
- Predicts performance metrics (S11, gain) for unseen parameter sets.  
- Enables **rapid optimization** without full simulation sweeps.  
- Reduces overall **design time by 60–70 %**.  
- Supports generalized antenna design across nearby sub-bands.

---
