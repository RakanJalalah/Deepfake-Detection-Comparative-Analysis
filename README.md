# Comparative Analysis of Deepfake Detection Frameworks 🛡️🤖

## 📌 Project Overview (Final Development Phase)
This initiative, conducted at the University of Jeddah, presents a rigorous comparative evaluation of five distinct architectural frameworks designed for deepfake detection. The research focuses on addressing the "generalization gap"—the performance degradation of detection models when confronted with unseen, Out-Of-Domain (OOD) generative manipulations.

## 🔬 Comparative Research Methodology
The project executes a multi-faceted analysis, benchmarking four individual architectural solutions against a hybrid State-of-the-Art (SOA) baseline to ensure comprehensive coverage of various algorithmic vulnerabilities:

* **SOA Baseline (Hybrid ViT-CLIP):** An architecture integrating GenD Layer Normalization and D³ discrepancy learning for enhanced semantic and structural analysis.
* **Solution #1 (ConvNeXt V2 + FFT):** A dual-branch model utilizing Patch-wise FFT to analyze both spatial artifacts and spectral frequency patterns.
* **Solution #2 (Autoencoder Anomaly Detection):** An unsupervised approach trained on pristine data to identify manipulated samples through reconstruction error analysis.
* **Solution #3 (Hybrid Feature Fusion):** A classical machine learning pipeline fusing spatial, frequency, and texture features evaluated via RBF SVM.
* **Solution #4 (MesoInception-4):** A deep CNN architecture specifically engineered to target mesoscopic blending boundaries and texture degradation.

## 📊 Technical Status & Milestones
* **Data Engineering:** Successfully processed a standardized master dataset of 360,000+ localized facial images derived from FF++ and Celeb-DF v2.
* **Pipeline Integrity:** Implemented a GPU-accelerated extraction pipeline with video-level stratification to eliminate temporal data leakage.
* **Current Status:** The project is in the final optimization and synthesis phase. Preliminary empirical results demonstrate high efficacy across the evaluated architectures.

## 📂 Documentation
* 📄 **[Deepfake_Detection_Report.pdf](./Deepfake_Detection_Report.pdf)**: The comprehensive technical manuscript detailing research methodology, literature review, and performance metrics.

## 🛠️ Technical Stack
* **Frameworks:** PyTorch, TensorFlow, Keras.
* **Architectures:** Vision Transformers (ViT), CNNs, Inception Modules, Autoencoders.
* **Domains:** Computer Vision, Digital Forensics, Signal Processing (FFT/DCT).
