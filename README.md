# Comparative Analysis of Deepfake Detection Frameworks 🛡️🤖

## 📌 Project Overview (Final Results)
This initiative, conducted at the **University of Jeddah**, presents a rigorous comparative evaluation of five distinct architectural frameworks designed for deepfake detection. The research successfully addressed the **"generalization gap"** by benchmarking diverse ML inductive biases on a shared high-integrity pipeline, finalized on **May 10, 2026**.

## 📊 Final Performance Scoreboard
* **ConvNeXt V2 + FFT (Solution #1):** Achieved peak test accuracy of **97.39%**.
* **Foundation SOA (ViT-L/14):** Achieved **93.74%** accuracy.
* **Hybrid SVM Fusion (Solution #3):** Achieved **93.62%** accuracy with ultra-fast inference.
* **MesoInception-4 (Solution #4):** Achieved **83.35%** accuracy, optimized for edge deployment.
* **Data Scale:** Successfully processed **360,000+** localized facial images derived from FF++ and Celeb-DF v2.

## 🔬 Comparative Research Methodology
The project benchmarked four individual solutions against a hybrid **State-of-the-Art (SOA)** baseline:
1.  **SOA Benchmark:** A tri-branch architecture utilizing **CLIP ViT-L/14**, D3, and PatchFFT.
2.  **Solution #1 (ConvNeXt V2 + FFT):** Combined spatial features with spectral analysis to detect periodic upsampling artifacts.
3.  **Solution #2 (Autoencoder Anomaly):** Unsupervised approach focused on reconstruction error and latent-space deviation.
4.  **Solution #3 (Hybrid SVM):** Fused ResNet50, DCT, and LBP features into a high-speed RBF SVM classifier.
5.  **Solution #4 (MesoInception-4):** Specialized network targeting mesoscopic artifacts like blending boundaries and texture degradation.

## 📂 Documentation
Based on the final project submission, here are the core documents:
* 📄 **FakeBusters (3).pdf**: The comprehensive technical manuscript detailing research methodology and empirical metrics.
* 📊 **FakeBusters_Presentaion.pdf**: Final presentation including the performance scoreboard and comparative analysis.

## 🛠️ Technical Stack
* **Frameworks:** PyTorch 2.x, TensorFlow 2.x, Keras.
* **Architectures:** Vision Transformers (ViT), ConvNeXt V2, MesoInception-4, RBF SVM.
* **Domains:** Computer Vision, Digital Forensics, Signal Processing (FFT/DCT).
