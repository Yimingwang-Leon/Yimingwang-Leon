## 🧠 Patronising and Condescending Language (PCL) Detection

Developed a binary classifier for **SemEval 2022 Task 4** to detect patronising and condescending language in text.

- **Official test F1:** 0.6144
- **Rank:** 6 / 233
- **Model:** RoBERTa large
- **Methods:** partial fine tuning, synthetic augmentation, threshold optimisation

**Tech:** Python · PyTorch · HuggingFace Transformers · Scikit learn  
**Repo:** [pcl-text-classification](https://github.com/Yimingwang-Leon/pcl-text-classification)


## 🏥 Real-Time AKI Detection System

Developed a real-time **Acute Kidney Injury (AKI)** detection service deployed on Kubernetes, processing live HL7 messages from a hospital simulator over a two-week assessment period.

- **Final F3 score:** 0.95
- **Model:** MLP classifier with NHS AKI algorithm-inspired feature engineering
- **Methods:** MLLP message parsing, state persistence, exponential backoff reconnection, Prometheus observability
- **Deployment:** Azure AKS with PersistentVolumeClaim, graceful SIGTERM shutdown

**Tech:** Python · scikit-learn · Docker · Kubernetes · HL7/MLLP · Prometheus  
**Repo:** [aki-detection-system](https://github.com/Yimingwang-Leon/aki-detection-system)

