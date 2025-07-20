# Meta-heuristics-Feature-Selection-for-Endoscopic-Image-Classification


A robust pipeline for feature extraction and selection from multi-class gastrointestinal (GI) endoscopic images. Leveraging CNN-based deep feature embeddings, dimensionality reduction, and multiple feature selection techniques, the project significantly improves classification efficiency and model performance on the HyperKvasir dataset.

---

## 📌 Highlights

✅ Used the publicly available HyperKvasir dataset with 10,662 annotated endoscopic images across 23 classes.
✅ Employed pre-trained CNN architectures for extracting high-level visual features.
✅ Reduced feature space by 60% using Principal Component Analysis (PCA).
✅ Applied multiple feature selection methods:

* Particle Swarm Optimization (PSO)
* Chi-Square Test
* ANOVA (Analysis of Variance)

---

## 🧠 Methodology

### 1. Dataset

* Source: HyperKvasir
* Total Images: 10,662
* Classes: 23 (polyp, ulcerative colitis, esophagitis, etc.)

### 2. Feature Extraction

* Used pre-trained CNNs (e.g., VGG16, ResNet50) to extract deep features from images.
* Flattened and pooled features from final convolutional layers.

### 3. Dimensionality Reduction

* Applied PCA to reduce redundant and correlated features.
* Retained 40% of the original dimensions → 60% compression in feature size.

### 4. Feature Selection

To enhance classification performance and reduce overfitting, we applied:

* ✅ Particle Swarm Optimization (PSO)
* ✅ Chi-Square Test
* ✅ ANOVA (f-classif)

These methods were compared in terms of selected feature subset size and impact on model accuracy.


