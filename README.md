
# Panacea AI: IV Medication Safety Model

Panacea is a healthcare innovation aimed at reducing medication errors during IV drug administration. This repository contains a Random Forest AI model and performance report from our pilot implementation.

## Project Overview

- **Problem:** Medication errors, especially with intravenous (IV) administration, are a leading cause of patient harm in hospitals.
- **Solution:** A barcode-enabled AI verification system embedded in IV dressings that alerts clinicians in real time to potential mismatches in medication.
- **Pilot Site:** Nairobi-based hospital (300 beds)
- **Key Outcome:** Reduced IV drug error rate from 18% to 11%, with a 40% improvement overall.

## Contents

- `rf_model.pkl` - Trained Random Forest model
- `classification_report.txt` - Performance report (Accuracy, Precision, Recall, F1 Score)

## Model Details

- **Algorithm:** Random Forest Classifier
- **Use Case:** Predict likelihood of medication mismatch during IV administration
- **Accuracy:** 100% (on test data from pilot)

## 🧪 Deployment Strategy

This model is trained on real pilot hospital data and will be integrated into Panacea's full-stack platform, including:
- Barcode scanner interface
- EHR/EMR integration
- Real-time alerts and medication verification

## 🚀 Future Plans

- Scale pilot to 10 hospitals
- Regulatory approvals across East Africa
- Transition model to real-time cloud deployment

---

##  Contact

For inquiries, collaboration, or more details:  
📧 hello@panacea.healthcare  
🌍 https://www.panacea.healthcare
