# 🎓 NUS SPH6004 — Machine Learning Assignments 🚀  

Welcome to my repository for **NUS SPH6004**! This repo contains my implementations for **Assignment 1** and **Assignment 2**, covering fundamental and advanced machine learning techniques. 🧠✨  

If you have any thoughts or suggestions, feel free to reach out! Happy coding! 🎉  

---

## 📌 What's Inside?  
### **📝 Assignment 1: Understanding ML from Scratch**  
🔹 **`models/`** — Implemented classic ML algorithms **from scratch** using only `numpy` & `pandas`:  
✔️ Linear Regression  
✔️ Logistic Regression  
✔️ Random Forest  
✔️ Decision Tree  
✔️ SVM (with SMO)  
✔️ AdaBoost  
✔️ Gradient Boosting (GBDT)  

🔹 **`baseline/`** — This contains the **step-by-step implementation** along with some **extra experiments**.  
For quick debugging, I used a **small-scale dataset**, but feel free to test on full data! 🚀  

### 📝 Assignment 2: Image Embedding Modeling (1376-dimensional CXR Tabular Vectors)

Developed a structure-aware multi-label classification model based on 1376-dimensional image embeddings derived from chest X-rays.

#### 🔹 Baseline Models
Implemented and tuned several strong baselines for tabular deep learning:

- MLP
- ResMLP
- SwinMLP
- TransformerMLP
- FTTransformer
- SAINT
- ViTLike
- Vanilla Transformer

#### 🔹 Advanced Model: ZLXC (Zoomable Label-guided eXpert Classifier)
A modular architecture designed for high-dimensional dense feature modeling.

- **FeatureReformer**: Gated projection and patchify for structural compression  
- **MlTrBlock1D**: Local window attention + cross-window global attention  
- **LabelGCN**: Label co-occurrence graph for semantic propagation  
- **Query2LabelDecoder**: Transformer decoder for label-aware attention  
- **Masked BCE Loss**: Skips missing labels during training for robust learning

#### 📊 Evaluation Metrics
- AUC (per-class & macro)
- F1 Score (micro & macro)
- mAP (mean average precision)
- Accuracy

---

## 💡 Why This Repo?  
This repository is designed to **help you truly understand ML algorithms** by implementing them from the ground up.  
If you're tired of just using `sklearn`, this is your chance to dive deep and **see how things really work!** 🔍🔥  

---

## 📢 Let's Connect!
Got any ideas, improvements, or just want to chat about ML? Drop me a message! 📬
Happy coding and keep exploring! 🚀🎯

---

## 🚀 How to Use?  
Clone the repo and start exploring:  
```bash
git clone https://github.com/yourusername/NUS-SPH6004.git
cd NUS-SPH6004
