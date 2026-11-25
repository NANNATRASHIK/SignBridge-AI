# SignBridge AI 🤟

**An AI-powered sign-language communication and learning platform.**

SignBridge AI aims to reduce communication barriers between sign-language users and non-signers by combining Computer Vision, Machine Learning, Deep Learning, and modern Generative AI technologies.

The platform is designed to recognize selected sign-language gestures, translate them into readable text and speech, and provide an interactive environment for learning and practicing sign language.

> 🚧 **Project Status: Under Development**

---

## 🎯 Project Objectives

- Recognize selected sign-language gestures through a webcam.
- Convert recognized signs into readable text.
- Convert translated text into speech.
- Support sign-language learning and practice.
- Provide an AI-powered assistant for sign-language-related questions.
- Develop an extensible architecture for future vocabulary expansion.

## 🧠 Technology Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Computer Vision | OpenCV, MediaPipe, NumPy |
| Machine Learning | Scikit-learn |
| Deep Learning | PyTorch |
| Backend | Django REST Framework |
| Frontend | React |
| Database | PostgreSQL |
| Generative AI | LLMs, RAG |
| AI Workflows | LangGraph |
| AI Integration | Model Context Protocol (MCP) |
| Version Control | Git, GitHub |

*Technologies listed include planned technologies that are still under investigation or implementation.*

## 🏗️ Planned Architecture

```text
                 User Interface
                       |
                       v
                Django REST API
                       |
                       v
             Application Orchestration
                       |
          +------------+-------------+
          |            |             |
          v            v             v
     Sign          Translation     RAG Knowledge
  Recognition       & Speech        Assistant
          |            |             |
          +------------+-------------+
                       |
              Agentic AI Workflows
                       |
                 MCP Integration
                       |
                       v
             Database & Model Storage
```

**Planned application technologies:**
- Frontend: React
- Backend: Django REST Framework
- Database: PostgreSQL

## 🔬 Core Modules

### 1. Computer Vision
- Webcam-based video capture.
- Hand and relevant body landmark detection.
- Landmark extraction and preprocessing.
- Visual data preparation for recognition models.

### 2. Machine Learning & Deep Learning
Models to investigate:
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest
- Convolutional Neural Networks (CNN)
- Long Short-Term Memory (LSTM)
- Transformers

### 3. Translation & Speech
- Sign-to-text translation.
- Text-to-speech conversion.
- Exploration of text-to-sign output using a curated sign library.

### 4. RAG Knowledge Assistant
- Retrieval from verified sign-language resources.
- Source-grounded answers.
- Sign-language learning assistance.

### 5. Agentic AI
- Guided sign-learning workflows.
- Interactive practice sessions.
- Learning progress tracking.

### 6. Model Context Protocol (MCP)
- MCP server development.
- Exposing recognition and learning capabilities as tools.
- Integration with compatible AI clients.

## 🗺️ Development Roadmap

- [x] Initial project scope and requirements
- [x] Git and GitHub repository setup
- [ ] Research and project foundation
- [ ] Computer vision and landmark extraction
- [ ] Dataset collection and preprocessing
- [ ] Traditional ML recognition models
- [ ] Deep learning recognition models
- [ ] Text and speech integration
- [ ] RAG knowledge assistant
- [ ] Agentic AI workflows
- [ ] MCP server integration
- [ ] Django REST API and React frontend
- [ ] Testing and deployment

*The roadmap will be updated as development progresses.*

## 📊 Model Evaluation

Recognition models will be evaluated using:

- Accuracy, Precision, Recall and F1-score.
- Confusion Matrix and class-wise performance.
- Recognition latency.
- Performance under different