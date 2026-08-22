# 👋 Hi, I'm Kiarash

### Machine Learning Engineer · Deep Learning · NLP/LLMs · RAG

I'm a final-year Computer Engineering student and Machine Learning Engineer
based in Tehran, Iran, with 1.5+ years of hands-on experience building
applied ML/DL systems through remote, project-based work with a robotics
engineering team.

I enjoy taking ML projects beyond notebooks — from raw data and
experimentation to evaluation, testing, deployment, and documentation.

**Current interests:** Machine Learning Engineering · Deep Learning ·
NLP · LLM Applications · RAG · MLOps

📍 Tehran, Iran · Open to Full-time · Contract · Remote opportunities

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kiarash-shayegani/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kiarash.shayegani.st@gmail.com)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/kiarashshayegani)

---

## 💼 Current Experience

**Machine Learning Engineer — Borna Noandishan Sina**

*Remote · Project-Based · Nov 2024 – Present*

Working with a robotics engineering team on applied ML/DL projects
involving real-world robotic sensor data.

- Neural-network-based attitude estimation and sensor fusion
- Vehicle dynamics modeling
- BLDC motor performance prediction
- Model evaluation and deployment-oriented workflows
- Webots simulation integration
- Technical documentation and reproducible ML pipelines

---

## 🚀 Featured Projects

### 🧭 Virtual-AHRS
**Neural Network-Based Attitude & Heading Reference System**

A deep-learning approach to estimating **Yaw, Roll, and Pitch** directly
from accelerometer, gyroscope, and magnetometer measurements.

**Highlights**
- 3 architecture iterations: Feed-Forward → LSTM → Multi-Branch Feed-Forward
- Custom `CircularLoss` using sin/cos targets for angular wraparound
- Sensor-specific branches with a shared neural network trunk
- **Yaw:** 3.17° MAE · R² = 0.845
- **Roll:** 2.57° MAE · R² = 0.928
- **Pitch:** 2.44° MAE · R² = 0.914
- 91 automated tests with `pytest`
- Reproducible, config-driven training pipeline
- TensorFlow → ONNX deployment path
- Webots robotics simulator integration
- Gradio demo on Hugging Face
- MkDocs Material technical documentation

🔗 [Repository](https://github.com/KiarashShayegani/Virtual-AHRS)  
🤗 [Live Demo](https://huggingface.co/spaces/kiarash2077/AHRS-v3.0-lite)

**Stack:** `Python` `TensorFlow` `scikit-learn` `ONNX` `pytest` `Webots` `Gradio` `MkDocs`

---

### 🚗 Iran Car Market Intelligence

**End-to-end ML pipeline for Iranian automotive market analytics.**

ICMI continuously collects, validates, cleans, and models vehicle listings
from the Iranian market before serving price estimates and market analytics
through a Gradio application.

**Highlights**
- 14 popular Iranian vehicle brands
- Daily automated scraping and model retraining
- Self-growing historical dataset
- Best-of-4 model selection per brand:
  `CatBoost` · `XGBoost` · `Random Forest` · `MLP`
- Cross-validation-based model selection
- Global-model fallback for low-data brands
- Auditable validation with rejected-row tracking
- Shamsi/Gregorian calendar normalization
- GitHub Actions scheduled pipeline
- Modular scraping → validation → cleaning → training architecture
- Gradio price-estimation and market-analysis application

🔗 [Repository](https://github.com/KiarashShayegani/Iran-Car-Market-Intelligence)  
🤗 [Live Demo](https://huggingface.co/spaces/kiarash2077/Iran_Car_Market_Intelligence)

**Stack:** `Python` `Pandas` `scikit-learn` `CatBoost` `XGBoost`
`SQLite` `Gradio` `GitHub Actions`

---

### 🤖 SRU Academic Assistant

**Persian-first FAQ + RAG assistant for university regulations.**

A modular academic assistant combining deterministic FAQ retrieval with
LLM-powered Retrieval-Augmented Generation.

**Highlights**
- Dual retrieval modes: FAQ + RAG
- MiniLM embeddings
- LanceDB vector search
- Page-aware retrieval over regulation documents
- Streaming LLM responses
- Persian RTL interface
- Offline retrieval evaluation and golden-question set
- Reproducible index-building CLI tools
- Modular Python package architecture
- Automated testing and documentation

🔗 [Repository](https://github.com/KiarashShayegani/SRU-Academic-Assistant)

**Stack:** `Python` `RAG` `LLMs` `Sentence Transformers`
`LanceDB` `Streamlit`

---

### 🎬 ParSent Cinema

**Persian sentiment analysis for movie & series comments.**

An end-to-end Persian NLP project comparing classical deep-learning
architectures with fine-tuned ParsBERT.

**Results**

| Model | Accuracy | Macro F1 |
|---|---:|---:|
| ParsBERT | **73.7%** | **0.704** |
| TextCNN | 65.1% | 0.619 |
| BiLSTM | 60.3% | 0.537 |

The project also includes a deliberately difficult evaluation set
containing sarcasm, irony, dialectal Persian, Latin-script Persian,
and rhetorical opinions to investigate model robustness.

🔗 [Repository](https://github.com/KiarashShayegani/parSent_Cinema)  
🤗 [Live Demo](https://huggingface.co/spaces/kiarash2077/parSent_Cinema)

**Stack:** `Python` `PyTorch` `ParsBERT` `TextCNN` `BiLSTM`
`NLP` `Gradio`

---

### ⚡ BLDC Motor Performance Prediction

**Applied ML for robotics using real-world motor sensor logs.**

A multi-phase collaboration with a robotics engineering team to predict
BLDC motor current from real time-series sensor data.

**Highlights**
- Progressive modeling from regression baselines to neural networks
- Real robotic sensor logs
- Targeted signal engineering
- Regularized neural-network architecture
- RobustScaler-based preprocessing
- Final model: Dense `128 → 64 → 32 → 1`
- Typical R² ≈ **0.94**
- Reusable training/evaluation/prediction pipeline
- Unit tests and technical documentation
- Gradio deployment

🔗 [Repository](https://github.com/KiarashShayegani/BLDC-Motor-Performance-Prediction)

**Stack:** `Python` `TensorFlow` `scikit-learn` `Pandas`
`pytest` `Gradio`

---

## 🛠️ Technical Stack

### Machine Learning & Deep Learning

`Python` · `TensorFlow` · `PyTorch` · `scikit-learn` · `XGBoost`
`CatBoost` · `Random Forest` · `Transformers` · `ParsBERT`

### NLP / LLM Applications

`NLP` · `Embeddings` · `Sentence Transformers` · `RAG`
`Vector Search` · `LanceDB` · `LLM Applications`

### Data

`NumPy` · `Pandas` · `SQL` · `MySQL` · `SQLite`
`Parquet` · Feature Engineering · Data Validation

### Engineering & Deployment

`Git` · `GitHub` · `GitLab` · `Docker` · `Linux`
`GitHub Actions` · `CI/CD` · `pytest` · `ONNX`

### Applications & Simulation

`Gradio` · `Streamlit` · `Hugging Face`
`Webots` · `Matplotlib` · `Plotly`

---

## 🧠 Engineering Approach

I care about the part of ML that happens **after the notebook**.

My projects usually follow:

```text
Raw Data
   ↓
Validation & Preprocessing
   ↓
Experimentation
   ↓
Model Selection
   ↓
Evaluation
   ↓
Testing
   ↓
Deployment
   ↓
Documentation & Iteration
