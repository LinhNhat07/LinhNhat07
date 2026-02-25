# 👋 Hi, I'm Nguyen Hong Nhat Linh

## 🚀 AI & Machine Learning Engineer | Computer Vision & Data Science
**Bridging AI Research and Industrial Production with Real-world Data & Automation**

Industrial AI Engineer specializing in Computer Vision and applied AI solutions. Hands-on experience in real-world industrial environments, including data collection, annotation, preprocessing, model training, fine-tuning, and high-performance deployment on edge devices (NVIDIA Jetson, Linux-based systems). Proficient in converting models to ONNX and TensorRT for optimized inference, integrating industrial cameras, PLC systems, and alarm mechanisms to deliver reliable, production-ready AI applications that enhance manufacturing automation, quality control, and operational efficiency.

---

## 🔬 Research & Publication

### **VR-TSD: A Real-World Dataset and a Lightweight YOLOv8n Model for Traffic Sign Recognition in Vietnam**
📌 *Published at **CSA 2025 Conference***

- **Dataset:** Built **VR-TSD**, a real-world traffic sign dataset (58 classes) collected under harsh conditions: rain, fog, low-light, occlusion.
- **Model:** Proposed a **Lightweight YOLOv8n** architecture (≈6MB).
- **Performance:** - **mAP@0.5:** 0.9434  
  - **Inference speed:** 77.5 FPS on mobile devices
- **Contribution:** Demonstrated high-accuracy edge deployment under constrained resources.

---

## 💡 Industrial & Real-world Projects

### 🏭 **Industrial Smart Quality Control System**
- **Objective:** Automated defect detection and packaging inspection (wrong label, misalignment).
- **Data Pipeline:** Real-time image acquisition from production lines using **Keyence, Basler, Cognex** cameras.
- **Key Challenges:** Rare defect detection, class imbalance, unstable lighting.
- **Tech Stack:** `YOLOv11s · YOLOv8n · OpenCV · PostgreSQL · NVIDIA RTX 5060`

---

### 🧴 **Real-time Product Code Recognition & Industrial Alert System**

- **Objective:** Deploy an automated system for product code identification and surface defect detection on small-scale cosmetic production lines.
- **Core Technology:**
    - **Hybrid Architecture:** Combined **YOLOv8** for high-speed region proposal (ROI detection) with **ResNet-50** for precise product code classification.
    - **Model Performance:** Achieved a classification **Accuracy of 95%** and a detection **mAP of 0.89**, ensuring reliable defect filtering.
    - **Optimization:** Streamlined the pipeline via **TensorRT** to maintain a stable **12 FPS** on resource-constrained edge devices.
    - **Hardware:** Integrated **Dino-Lite** digital microscopy cameras to capture high-resolution details, effectively mitigating character deformation and surface reflections.
- **Industrial Integration:**
    - Developed a real-time alert control module utilizing **RS485 (Modbus RTU)** protocol.
    - Synchronized industrial buzzers for instantaneous audible alerts upon detecting defective or mismatched products.
- **Deployment:** Field-tested on **NVIDIA Jetson Orin & Jetson Nano**, balancing power efficiency with high-performance inference at the edge.
- **Tech Stack:** `YOLOv8` · `ResNet-50` · `OpenCV` · `RS485 (Modbus)` · `TensorRT` · `Dino-Lite`
  
---

### 📝 **Vietnamese NLP & Sentiment Analysis System**
- **Dataset:** Collected and cleaned **19,000+ real-world Vietnamese samples** from news and social platforms.
- **Modeling:** Fine-tuned **PhoBERT** for sentiment classification.
- **Focus:** Domain noise, slang, informal Vietnamese language.
- **Tech Stack:** `PhoBERT · PyTorch · Hugging Face Transformers`

---

## 🧠 LLM, API & RAG Systems Experience

### 🔗 **LLM API & Orchestration**
- Designed systems using **OpenAI API**, **Amazon Bedrock**, and **Hugging Face**.
- Orchestrated complex AI tasks using **n8n**, enabling seamless interaction between LLMs and external tools.
- Experience with: Prompt engineering, Token optimization, and Async inference.

### 📚 **RAG (Retrieval-Augmented Generation)**
- Built RAG pipelines for **enterprise knowledge systems**.
- **n8n Integration:** Building visual RAG workflows using Vector Store nodes (FAISS, Pinecone/Chroma) and Document Loaders.
- Use cases: Internal document QA, Technical knowledge assistants.

---

### Tech Stack & Expertise

| Category                                      | Technologies & Tools                                                                 |
|-----------------------------------------------|--------------------------------------------------------------------------------------|
| **Programming Languages & Core Libraries**    | Python, NumPy, Pandas, Matplotlib, Seaborn                                           |
| **Machine Learning & Deep Learning Frameworks** | **PyTorch**, **TensorFlow** / Keras, **scikit-learn**, Hugging Face Transformers |
| **Classical Machine Learning Models & Algorithms** | Linear Regression, Logistic Regression, **Support Vector Machines (SVM)**, Decision Trees, **Random Forest**, Gradient Boosting (XGBoost, LightGBM, CatBoost), K-Nearest Neighbors (KNN), Ensemble methods |
| **Deep Learning Architectures & Models**      | CNNs, ResNet, EfficientNet, MobileNet, **U-Net** (semantic/instance segmentation), **YOLO** series, **Faster R-CNN**, Darknet, Vision Transformers (ViT), BERT, PhoBERT, Vision-Language Models |
| **Computer Vision Libraries & Tools**         | **OpenCV**, Albumentations (data augmentation), Keyence vision systems, Basler Pylon SDK, Cognex VisionPro, Dino-Lite microscopy integration |
| **Model Optimization & Inference Engines**    | **TensorRT** (FP16/INT8 quantization, engine serialization), **ONNX Runtime** |
| **Deployment & Edge AI**                      | **NVIDIA Jetson Orin / Jetson Nano**, TensorRT acceleration, **TensorFlow Lite**, PyTorch Mobile, Docker containerization |
| **Large Language Model & Generative AI Systems** | OpenAI API, Amazon Bedrock, Hugging Face ecosystem, Retrieval-Augmented Generation (**RAG**) pipelines |
| **Automation, Orchestration & Workflows**     | **n8n**, **LangChain**, Webhooks, workflow automation                               |
| **Industrial & Hardware Integration**         | RS-485, **Modbus RTU**, industrial cameras & vision controllers (Keyence, Basler, Cognex) |
| **Data Management & Backend**                 | **PostgreSQL**, NAS/FTP servers, Selenium (web scraping/automation), Docker         |

---

## 🌱 Current Focus
- **Industrial Computer Vision** — Designing and deploying high-precision, real-time defect detection systems for high-speed production lines using state-of-the-art object detection architectures (e.g., **YOLOv11**), addressing complex quality assurance challenges in manufacturing.
- **Model Optimization & Edge Deployment** — Optimizing deep learning pipelines through ONNX export, **TensorRT** engine building (FP16/INT8 quantization), and low-latency inference on industrial PCs and NVIDIA Jetson platforms (Orin/Nano) to enable ultra-fast, reliable production deployment.
- **Factory Automation & Hardware Integration** — Integrating AI vision solutions with industrial ecosystems, including Basler/Keyence cameras, RS-485/Modbus RTU protocols, and real-time alerting mechanisms for automated quality control and process optimization.
- **Applied Deep Learning & Production ML** — Bridging cutting-edge research with scalable, robust production systems by applying computer vision, machine learning, and NLP techniques to solve practical problems in industrial environments.

## 🤝 Open to Collaboration
- Edge AI deployment and optimization for industrial applications
- AI-driven workflow automation (n8n, LangChain, custom pipelines)
- Computer Vision solutions in manufacturing — including defect detection, OCR, and visual inspection
- Applied NLP projects, particularly for low-resource languages (e.g., Vietnamese-focused models like PhoBERT)

---

## 📫 Contact
<p align="left">
  <a href="mailto:nlinh.nh7@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>
