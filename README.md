# Image-Captioning
This project focuses on image captioning by integrating deep learning and NLP. Using the Flickr8k dataset, we apply SVD and Laplace filters for preprocessing, DenseNet201 for feature extraction, and LSTM for caption generation. The model achieves efficient, accurate results with reduced computational complexity.

## 📌 Image Captioning using Deep Learning and NLP

### 🧠 Overview (STAR Method)

**🔹 Situation:**
Image captioning is a challenging task that merges **computer vision** and **natural language processing** to generate meaningful textual descriptions of images. Traditional methods require high-end hardware due to computational complexity, especially with large datasets like MS-COCO.

**🔹 Task:**
The goal was to develop a **computationally efficient image captioning system** that performs well even on modest hardware. It should accurately generate captions that are contextually relevant, using a well-balanced dataset and optimized deep learning workflow.

**🔹 Action:**

* Shifted from COCO to **Flickr8k** for manageable yet diverse data.
* **Image Preprocessing:** Applied **Singular Value Decomposition (SVD)** for dimensionality reduction and used **Laplace Wavelet Filtering** to retain features and reduce noise.
* **Feature Extraction:** Used **DenseNet201**, a pre-trained CNN, to extract high-level image features.
* **Caption Generation:** Deployed **LSTM-based RNNs** to generate descriptive, coherent captions.
* Implemented **early stopping** and **learning rate tuning** to avoid overfitting and optimize training.
* Incorporated **ImageDataGenerator** to streamline the feeding of image-caption pairs into the model.

**🔹 Result:**

* Achieved high accuracy in caption generation while **significantly reducing processing time and resource usage**.
* Demonstrated effective feature learning even without complex, deep CNN stacks.
* The model generalizes well to unseen images and provides natural, grammatically correct captions.
* Set a foundation for future enhancements like **Attention Mechanisms**, **custom CNN models**, and **BLEU/CIDEr/ROUGE evaluation metrics**.

---

### 📂 Key Features

* 📷 **Wavelet-based preprocessing** for better visual feature preservation.
* 🧩 **DenseNet201 + LSTM architecture** for visual-to-text transformation.
* 🗂️ Uses **Flickr8k** dataset with 8,000+ images and human-written captions.
* 🚀 **Lightweight yet powerful model**, suitable for systems without GPUs.
* ✅ Modular design for extensibility and performance tuning.

---

### 🔮 Future Improvements

* Introduce **Attention Layers** to focus on relevant image regions.
* Use **BLEU, METEOR, ROUGE, and CIDEr** scores for better evaluation.
* Experiment with **transformer-based models** (e.g., Vision Transformers, BERT for captions).
* Design a **custom CNN** with fewer layers for even more efficiency.

---


