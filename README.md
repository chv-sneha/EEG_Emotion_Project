# EEG Emotion Recognition Project

This project aims to **recognize human emotions using EEG (Electroencephalography) brain signals**.  
EEG captures electrical activity from the brain, and by processing these signals we can **detect emotional states** like positive/negative feelings (valence) and intensity (arousal).

## ✅ Problem Statement
Understanding emotions is important for:
- mental health monitoring
- stress detection
- brain–computer interfaces (BCI)
- human-centered AI systems

But EEG signals are:
- noisy
- high-dimensional
- hard to interpret directly

So the main problem is:

**How can we clean EEG signals, analyze them, and use them to predict emotions accurately?**

---

## 🎯 What This Project Does
This project provides a pipeline to:

✅ Load EEG emotion dataset (example: DREAMER)  
✅ Perform **EDA (Exploratory Data Analysis)** to understand trends  
✅ Apply **EEG preprocessing** (cleaning + formatting data)  
✅ Prepare data for **emotion prediction / classification models**  
✅ Generate plots, insights, and experimental results  

---

## 🧩 Workflow (High-Level)
1. **Dataset Loading**
   - Read EEG recordings + emotion labels

2. **EDA**
   - Explore valence/arousal distribution
   - Visualize patterns

3. **Preprocessing**
   - Cleaning EEG signals
   - Handling noise/artifacts
   - Organizing EEG samples for ML input

4. **Model Ready Output**
   - Processed data can be used for emotion recognition models

---

## 📂 Project Structure
EEG_Emotion_Project/
│── src/ # Source code (preprocessing, utilities, experiments)
│── notebooks/ # Jupyter notebooks for EDA + preprocessing
│── figures/ # Graphs / screenshots / output visuals
│── results/ # Saved results, metrics, outputs
│── data/ # Dataset folder (ignored on GitHub)
│── README.md
│── .gitignore

yaml
Copy code

---

## 📒 Notebooks Included
- `01_EDA_VAD.ipynb` → Exploratory Data Analysis (Valence / Arousal based insights)
- `02_EEG_Preprocessing.ipynb` → EEG signal preprocessing steps

---

## 📊 Dataset Note (IMPORTANT)
The dataset file is NOT uploaded to GitHub because it is too large for GitHub limits.

Place your dataset locally like this:
data/DREAMER.mat

yaml
Copy code

---

## 🚀 How to Run
```bash
git clone https://github.com/chv-sneha/EEG_Emotion_Project.git
cd EEG_Emotion_Project

jupyter notebook
