# Comparative Analysis of State-of-the-Art Deepfake Detection Frameworks 🛡️🤖

## 📌 Project Overview (Final Development Phase)
This initiative, conducted at the University of Jeddah, presents a rigorous comparative evaluation of five distinct architectural frameworks designed for deepfake detection. The research focuses on addressing the **"generalization gap"**—the performance degradation of detection models when confronted with unseen, Out-Of-Domain (OOD) generative manipulations.

## 🔬 Comparative Research Methodology
The project executes a multi-faceted analysis, benchmarking four individual architectural solutions against a hybrid **State-of-the-Art (SOA)** baseline to ensure comprehensive coverage of algorithmic vulnerabilities:

* **SOA Benchmark (Hybrid Tri-Branch Architecture):** A novel model synthesizing spatial analysis (CLIP ViT-L/14), structural discrepancy ($D^{3}$), and frequency-domain analysis (PatchFFT).
* **Solution #1 (Dual-Branch ConvNeXt V2 + FFT):** A deep learning classifier combining spatial features with patch-wise FFT log-magnitude spectrums to detect periodic upsampling artifacts.
* **Solution #2 (Autoencoder-Based Anomaly Detection):** An unsupervised approach trained strictly on authentic data to identify manipulated samples through reconstruction error and latent-space deviation.
* **Solution #3 (Hybrid Feature Fusion with SVM):** A classical machine learning pipeline fusing spatial (ResNet50), frequency (DCT), and texture (LBP) features evaluated via an RBF SVM.
* **Solution #4 (Mesoscopic Feature Extraction via MesoInception-4):** A network specifically engineered to target intermediate-level visual artifacts, such as unnatural blending boundaries and texture degradation.

## 📊 Technical Status & Milestones
* **Data Engineering:** Successfully processed a standardized master dataset of **360,000+** localized facial images derived from **FF++** and **Celeb-DF v2**.
* **Pipeline Integrity:** Implemented a GPU-accelerated extraction pipeline with **video-level stratification** to eliminate temporal data leakage.
* **Current Status:** The project is in its final optimization phase. Preliminary results are highly promising, with ConvNeXt V2 currently achieving **97.39%** test accuracy.

## 📂 Documentation
* 📄 **[Deepfake_Detection_Report.pdf](./Deepfake_Detection_Report.pdf)**: The comprehensive technical manuscript detailing research methodology, literature review, and empirical performance metrics.

## 🛠️ Technical Stack
* **Frameworks:** PyTorch 2.x, TensorFlow 2.x, Keras.
* **Architectures:** Vision Transformers (ViT), ConvNeXt V2, Autoencoders, Inception Modules, RBF SVM.
* **Domains:** Computer Vision, Digital Forensics, Signal Processing (FFT/DCT).
