# AI-Powered AR/VR for Analyzing Student Behavior

## 📚 Project Overview
This project aims to analyze students' cognitive performance by comparing two teaching methods: **Traditional Learning** and **VR-Based Learning**. Using EEG devices, brainwave data is collected from students during these sessions. The data is then processed using **TensorFlow**, **CNN models**, and **LSTM** to evaluate their cognitive thinking levels and learning effectiveness.

The project provides insights into the best teaching methods to improve students' engagement, attention span, and cognitive abilities by leveraging **AI-driven analysis** of EEG data.

---

## 🎯 Objectives
- To measure and compare students' cognitive performance during traditional learning and VR-based learning.
- To process and analyze brainwave data collected through EEG devices.
- To determine the teaching method that provides better learning outcomes.

---

## 📊 Dataset Description
The dataset consists of EEG data collected from **students**, divided into two groups:
1. **Traditional Learning Group** – Students taught using conventional teaching methods.
2. **VR-Based Learning Group** – Students taught using VR headsets and 3D videos.

The EEG device captures brainwave signals from **8 electrodes**, with each electrode recording voltage signals representing brain activity. The dataset includes:
- Raw EEG signals in CSV format.
- Data collected at during teaching sessions.
- Cognitive states such as attention, focus, and engagement levels.

### Example EEG Output 
The EEG output consists of **8 channels (electrodes)**, with values recorded in scientific notation. Each column represents the brainwave activity captured from a specific electrode. The dataset requires preprocessing to remove noise, normalize signals, and filter out irrelevant data for better accuracy in cognitive analysis.

---

## 🧰 Tech Stack
- **Python**
- **TensorFlow** (for building CNN models)
- **NumPy** (for data manipulation)
- **Pandas** (for handling EEG datasets)
- **Matplotlib/Seaborn** (for data visualization)
- **scikit-learn** (for data preprocessing and analysis)

---

## ⚙️ Installation and Setup
1. **Clone the Repository**  
   ```bash
   git clone https://github.com/DXLeGenD/ai-powered-ar-vr-study-behaviour-analysis.git
   cd ai-powered-ar-vr-study-behavior-analysis
