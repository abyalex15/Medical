# MEWS (Modified Early Warning Score) System

This project implements a Modified Early Warning Score (MEWS) system using ballistocardiography (BCG) data to assess patient vitals and provide early warnings for timely medical intervention.

## 🚀 Features

- ✅ Reads mock BCG data from a CSV file.
- ✅ Calculates MEWS based on key physiological parameters:
  - Respiration Rate
  - SpO₂ (Oxygen Saturation)
  - Heart Rate (Pulse)
  - Systolic Blood Pressure
  - Temperature
  - Level of Consciousness
- ✅ Outputs MEWS scores and generates clinical response recommendations.
- ✅ Escalation alerts based on severity thresholds.

## 🛠 Usage

1. **Download the mock patient data CSV**  
   Use the provided sample file or connect to a real-time data source in future enhancements.

2. **Run the Python script**  
   Open the notebook or script in [Google Colab](https://colab.research.google.com/) or a Jupyter environment and execute the cells to:
   - Load and analyze patient vitals
   - Calculate MEWS scores
   - Generate clinical response alerts

## 💻 Requirements

- Python 3.0
- pandas
