## 🛍️ ShopSite AI — Natural Language-Driven Storefront Generation

Developed a zero-code AI website builder for non-technical small business owners to generate, edit, and deploy complete mobile-first storefronts using natural language only.

- **Demo:** [huggingface.co/spaces/Yiming-Leon/html_generator](https://huggingface.co/spaces/Yiming-Leon/html_generator)
- **Models:** Qwen2.5-7B-Instruct (intent parsing), Qwen2.5-Coder-14B-Instruct (HTML generation), SD-Turbo (poster generation)
- **Methods:** Multi-model pipeline, structured HTML template generation, menu item extraction from ZIP uploads, promotional poster synthesis with PIL text overlay
- **Features:** Create shop pages from text description, edit blocks via natural language, generate promotional posters, export full website as ZIP

**Tech:** Python · Gradio · HuggingFace Transformers · Diffusers · PyTorch · PIL


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

