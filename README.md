# Drift-Aware ML Monitoring & Auto-Retraining System

Most ML projects stop at training. In real-world systems, models degrade over time due to data distribution shifts.

This project simulates a production-style ML monitoring pipeline that:

- Processes incoming data in batches
- Detects feature drift using Population Stability Index (PSI)
- Monitors accuracy degradation
- Triggers automatic retraining
- Demonstrates performance recovery

## Dataset
German Credit Risk dataset (financial risk classification).

## Key Concepts
- Feature Drift
- Concept Drift
- PSI (Population Stability Index)
- Drift-triggered retraining

## How to Run

1. Clone the repository
2. Install dependencies:
   pip install -r requirements.txt
3. Run the notebook

## Why This Matters
Model monitoring and maintenance are critical in real production ML systems. This project focuses on reliability after deployment, not just model accuracy.

---

## Key Takeaway

Model development does not end at deployment. Monitoring, drift detection, and adaptive retraining are critical to maintaining long-term reliability in real-world ML systems.
