# 🧠 PCL Detection

Binary classification of Patronising and Condescending Language (PCL).  
Based on SemEval 2022 Task 4 (Subtask 1).

### 🚀 Approach
- RoBERTa-based model
- Partial fine-tuning (half layers frozen)
- Synthetic data augmentation
- Decision threshold optimisation
- Cross-entropy training

### 📊 Result
**Dev F1: 0.618**  
(Official baseline: 0.48)

The model substantially outperforms the official baseline on the development set.

## 🛠 Tech Stack

Python  PyTorch  HuggingFace Transformers  Scikit-learn  

🔗 **Project Repository:**  
https://github.com/Yimingwang-Leon/pcl-text-classification.git
