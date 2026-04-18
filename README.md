# Fake Busters: Deepfake Detection Comparative Analysis 🛡️🤖

## 📌 Project Overview
Developed by the **Fake Busters** team at the University of Jeddah, this project presents a rigorous comparative study of five state-of-the-art architectures designed for Deepfake detection. Our research focuses on bridging the "generalization gap," ensuring that detection models remain effective against unseen and Out-Of-Domain (OOD) generative manipulations.

## 🔬 Collaborative Research & Methodology
Our team implemented a multi-faceted approach to evaluate different algorithmic vulnerabilities across the digital media landscape. We benchmarked five distinct architectural strategies to ensure a comprehensive evaluation:

1.  **SOA Baseline (ViT-CLIP):** Evaluating hybrid architectures as a benchmark for generalizable face forgery detection.
2.  **Dual-Branch Spatial & Spectral Analysis:** Combining ConvNeXt V2 with Patch-wise FFT to detect both visual and frequency-domain artifacts.
3.  **Unsupervised Anomaly Detection:** Implementing Deep Autoencoders to identify manipulated deviations from pristine data distributions.
4.  **Hybrid Feature Fusion:** Fusing spatial, frequency, and texture features evaluated by classical ML models (RBF SVM).
5.  **Mesoscopic Architecture Analysis:** Targeting intermediate-level visual artifacts and blending boundaries introduced by generative models.

## 📊 Key Achievements
* **Unified Pipeline:** Processed over 360,000 localized facial images from the FF++ and Celeb-DF v2 benchmarks.
* **Integrity & Validation:** Established a standardized GPU-accelerated extraction pipeline with video-level stratification to eliminate data leakage.
* **Comparative Benchmarking:** Evaluated models based on precision, recall, and F1-scores to determine the most robust solution for real-world deployment.

## 📂 Featured Documentation
* 📄 **[FakeBusters_Progress_Report.pdf](./FakeBusters%20(3).pdf)**: The complete technical manuscript detailing our research, methodology, and final comparative analysis.

## 🛠️ Tech Stack
* **Deep Learning:** PyTorch, TensorFlow, Keras.
* **Architectures:** ViT, CNNs, Inception Modules, Autoencoders.
* **Forensics:** Computer Vision, Digital Forensics, Frequency Domain Analysis.
