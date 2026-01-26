# 👋 Hi, I'm Nguyen Hong Nhat Linh

## 🚀 AI & Machine Learning Engineer | Computer Vision & Data Science
**Bridging AI Research and Industrial Production with Real-world Data & Automation**

I am an AI Engineer specializing in Computer Vision, Natural Language Processing (NLP), and Large Language Model (LLM) systems, with a strong focus on real-world deployment and **AI workflow automation**.

My work centers on building models that remain reliable under noisy data, class imbalance, and hardware limitations, while leveraging **Low-code Automation (n8n)** to streamline AI operations and data pipelines.

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
    - **Model:** Leveraged **ResNet-50** for robust product code classification, achieving **95% Accuracy**.
    - **Performance:** Optimized via **TensorRT** to maintain a stable **12 FPS** on edge computing resources.
    - **Hardware:** Integrated **Dino-Lite** digital microscopy cameras to capture high-resolution details, effectively mitigating character deformation and surface reflections.
- **Industrial Integration:**
    - Developed a real-time alert control module utilizing **RS485 (Modbus RTU)** protocol.
    - Synchronized industrial buzzers for instantaneous audible alerts upon detecting defective or mismatched products.
- **Deployment:** Field-tested on **NVIDIA Jetson Orin & Jetson Nano**, balancing power efficiency with high-performance inference at the edge.
- **Tech Stack:** `ResNet-50` · `YOLO` · `OpenCV` · `RS485 (Modbus)` · `TensorRT` · `Dino-Lite`

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

## 🛠 Tech Stack & Expertise

| Category | Technologies |
|------|------|
| **Deep Learning Architectures** | **CNNs, ResNet, U-Net (Segmentation), Faster R-CNN, YOLO (v8–v11)**, Transformers, PhoBERT, Vision-Language Models |
| **Model Optimization & Deployment** | **ONNX Runtime, TensorRT (FP16/INT8 Quantization), Engine File Serialization**, OpenVINO |
| **Automation & Orchestration** | **n8n**, LangChain, Workflow Automation, Webhooks |
| **Computer Vision** | OpenCV, Keyence, Basler Pylon, Cognex Vision, Dino-Lite |
| **LLM Systems** | OpenAI API, Amazon Bedrock, Hugging Face, RAG Pipelines |
| **Edge AI** | **Jetson Orin, Jetson Nano**, TensorRT Acceleration |
| **Industrial Communication** | RS485, Modbus RTU |
| **Data & Backend** | PostgreSQL, NAS/FTP, Selenium, Docker |

---

## 🌱 Current Focus
**Industrial Computer Vision:** Developing high-precision defect detection systems for high-speed conveyor belts, leveraging state-of-the-art architectures like YOLOv11 to solve complex quality control challenges.

**Model Optimization & Deployment:** Streamlining the end-to-end deployment pipeline by converting Deep Learning models to ONNX and TensorRT (Engine) formats to achieve ultra-low latency on industrial PCs and Edge AI platforms (NVIDIA Jetson).

**Factory Automation Integration:** Deepening expertise in integrating AI software with industrial hardware, including Basler/Keyence cameras and RS485 communication protocols for real-time automated alerts.

**Practical Deep Learning:** Bridging the gap between research and production by applying Machine Learning and NLP to build robust, scalable AI solutions for real-world industrial environments.

---

## 🤝 Open for Collaboration
- Edge AI & Industrial Automation
- **AI Workflow Automation & n8n Implementation**
- Computer Vision in manufacturing (Defect detection & OCR)
- Applied NLP for low-resource languages

---

## 📫 Contact
<p align="left">
  <a href="mailto:nlinh.nh7@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>
