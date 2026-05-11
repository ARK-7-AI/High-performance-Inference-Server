# High-Performance Inference Server

Production-style AI inference server built using FastAPI, Docker, and optimized model-serving techniques.

## Features

- FastAPI inference APIs
- Quantized model support
- Dockerized deployment
- Async request handling
- Benchmarking utilities
- Low-latency inference serving

---

# Tech Stack

- Python
- FastAPI
- PyTorch
- Hugging Face Transformers
- Docker
- ONNX Runtime (planned)

---

# Project Goals

This project focuses on:
- scalable AI serving
- inference optimization
- deployment engineering
- ML infrastructure fundamentals

---

# Setup

## Clone Repo

```bash
git clone <repo-url>
cd high-performance-inference-server
```

## Create Virtual Environment

```bash
python -m venv venv
```

Activate:

```bash
source venv/bin/activate
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Run Server

```bash
uvicorn app.main:app --reload
```

Open:
```text
http://127.0.0.1:8000/docs
```

---

# Docker

Build:

```bash
docker build -t inference-server -f docker/Dockerfile .
```

Run:

```bash
docker run -p 8000:8000 inference-server
```

---

# Future Improvements

- ONNX optimization
- vLLM integration
- batching
- streaming responses
- GPU acceleration
- Prometheus monitoring

---

# Skills Demonstrated

- AI inference serving
- FastAPI backend engineering
- Docker deployment
- model optimization
- scalable AI infrastructure
