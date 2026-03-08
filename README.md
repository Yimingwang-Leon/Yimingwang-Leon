## 🧠 Patronising and Condescending Language (PCL) Detection

Binary classification of Patronising and Condescending Language toward vulnerable social groups, based on **SemEval 2022 Task 4**.

- **Official test F1 (positive class): 0.614**
- **Final rank: 6 / 233**

### Highlights
- Fine tuned **RoBERTa large** for binary PCL detection
- Used **partial layer freezing** to reduce overfitting on the small positive class
- Improved minority class coverage through **synthetic data augmentation**
- Applied **decision threshold optimisation** to maximise positive class F1

### Tech Stack
Python · PyTorch · HuggingFace Transformers · Scikit learn

🔗 **Project Repository:**  
https://github.com/Yimingwang-Leon/pcl-text-classification
