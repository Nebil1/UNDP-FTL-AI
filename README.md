# Frontier Tech Leaders Programme – AI & Machine Learning Projects

This repository documents my journey through the **Frontier Tech Leaders (FTL) Programme**, a UNDP-powered initiative aimed at empowering young technologists—especially from Least Developed Countries (LDCs)—with AI and Machine Learning skills to build solutions aligned with the **United Nations Sustainable Development Goals (SDGs)**.

---

## 🌍 About the Programme

The **Frontier Tech Leaders Programme**, run by **UNDP ICPSD’s SDG AI Lab** and the **UN Technology Bank for LDCs**, supports youth in building AI-powered solutions to sustainable development challenges.

The program is aligned with the **UNDP Digital Strategy**, advancing:

* Youth empowerment in technology,
* Digital innovation in least developed countries,
* Open-source AI solutions for the SDGs.

> 📚 Learn more at [undp.org](https://www.undp.org/policy-centre/istanbul/press-releases/frontier-tech-leaders-programme-launches-empower-ldcs-youth-digital-transformation)

---

## 🚀 Highlight Projects

### 1. Plastic Waste Classifier (CNN + Web App)

* Classifies plastic images into **HDPE**, **LDPE**, **PET**, **PP**.
* VGG16-based CNN trained on real-world image dataset.
* **Gradio-based web interface** for interactive predictions.
* Confidence scoring + user feedback logging (✅ / ❌).
* Dockerized and deployed on **AWS EC2 (t3.micro)** with Nginx reverse proxy.
* Auto-start enabled with Docker `--restart unless-stopped`.

### 2. Logistic Regression (Lab 1)

* Performed binary classification of rivers based on plastic contribution levels.
* Feature scaling, threshold tuning, and model evaluation using accuracy, precision, recall.

### 3. K-Means Clustering (Lab 2)

* Applied unsupervised clustering to river datasets.
* Used Elbow method to select optimal **K**, interpreted clusters with visualizations.

### 4. BERT Tweet Sentiment Classifier (Lab 3)

* Fine-tuned `bert-base-uncased` on synthetic tweet dataset.
* Classified sentiment as positive or negative for sustainability-related text.
* Evaluated using F1-score, confusion matrix, and model saving/loading.

---

## Tech Stack

* **Languages**: Python 3.10+
* **Libraries**: TensorFlow, Keras, Scikit-learn, HuggingFace Transformers, Gradio, NumPy, Matplotlib
* **Tools**: Docker, AWS EC2, tmux, Nginx, Certbot (HTTPS), GitHub
* **Deployment**: Dockerized Gradio app with reverse proxy + optional HTTPS
* **Platform**: [GitHub Profile](https://github.com/Nebil1)

---

## 🌟 UNDP SDG Alignment

| Goal       | Description                                                               |
| ---------- | ------------------------------------------------------------------------- |
| **SDG 12** | Responsible Consumption & Production → via plastic classification tool    |
| **SDG 13** | Climate Action → models built to monitor and reduce environmental harm    |
| **SDG 17** | Partnerships for the Goals → trained and deployed with UNDP collaboration |

---

## 📬 Contact

* 🔗 GitHub: [@Nebil1](https://github.com/Nebil1)
* 🌍 Built as part of the **Frontier Tech Leaders Programme** with support from **UNDP ICPSD** and the **UN Technology Bank**.
