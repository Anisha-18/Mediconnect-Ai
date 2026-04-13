
🚀

🧠 MediConnect AI
A Privacy-Preserving Federated and Agentic Intelligence Framework for Autonomous Healthcare Supply Chain Optimization
📌 Overview

MediConnect AI is an advanced AI-powered framework designed to optimize healthcare supply chain management across multi-hospital networks. The system addresses critical challenges such as drug shortages, near-expiry wastage, counterfeit medicines, and inefficient procurement processes.

It integrates Federated Learning, Agentic AI, Generative AI, and Computer Vision into a unified architecture that ensures data privacy, automation, and intelligent decision-making without sharing sensitive hospital data.

🚀 Key Features
🔐 Privacy-Preserving Federated Learning
Enables collaborative model training across hospitals without sharing raw data.
🤖 Agentic AI Automation
Autonomous agents perform tasks like:
Demand prediction
Inventory monitoring
Procurement automation
Risk detection
📊 Accurate Demand Forecasting
LSTM-based models achieve 93.6% accuracy in predicting medicine demand.
👁️ Drug Verification (Computer Vision)
Uses YOLOv8 + OCR to detect and verify drug packaging in real time.
🧾 Generative AI Reports (RAG)
Automatically generates weekly reports and answers supply-related queries.
🎤 Multilingual Voice Assistant
Supports Tamil, Hindi, and English using speech recognition.
📈 Explainable AI (XAI)
SHAP-based explanations provide transparency in decision-making.
🏗️ System Architecture

The system consists of the following layers:

Hospital Nodes – Local data storage and training
Federated Learning Layer – Model aggregation (Flower + Opacus)
Agentic AI Layer – Autonomous decision-making (LangGraph + LLMs)
Computer Vision Layer – Drug verification (YOLOv8 + OCR)
Generative AI Layer – Reporting and query answering (RAG + FAISS)
User Interface – Dashboard and voice interaction
⚙️ Tech Stack
🔹 Backend
Python, Flask
Flower (Federated Learning)
PyTorch (LSTM Models)
🔹 AI & ML
LSTM (Demand Forecasting)
SHAP (Explainability)
FAISS (RAG Pipeline)
🔹 Agentic AI
LangGraph
GPT-4o / LLaMA 3
🔹 Computer Vision
YOLOv8
PaddleOCR
🔹 Frontend
HTML, CSS, JavaScript
🔹 Voice Processing
Whisper (Speech-to-Text)
📊 Results
Metric	Value
Demand Forecast Accuracy	93.6%
Stockout Reduction	34.2%
Wastage Reduction	28.7%
Drug Detection Accuracy (mAP)	91.3%
🧪 Testing

The system has been extensively tested using:

Unit Testing
Integration Testing
System Testing
Performance Testing
Security Testing
AI Model Testing

All modules demonstrated high reliability, scalability, and security.

📂 Project Structure
MediConnect-AI/
│── models/              # ML models
│── agents/              # Agentic AI modules
│── federated/           # Federated learning scripts
│── vision/              # YOLO + OCR modules
│── api/                 # Flask backend
│── templates/           # Frontend UI
│── static/              # CSS & assets
│── reports/             # Generated reports
│── app.py               # Main application
🔮 Future Enhancements
Integration with IoT-based real-time inventory tracking
Blockchain for supply chain transparency
Reinforcement learning for dynamic procurement optimization
Large-scale deployment across national healthcare systems
👩‍💻 Authors
Anisha S
Vetrivel L
Chandru D
Abishek M
Karthick V

Karpagam Institute of Technology, Coimbatore

📜 License

This project is developed for academic and research purposes.

⭐ Contribution

Feel free to fork, contribute, and improve the project!
