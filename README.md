# Custom GPT-2 with Instruction Fine-Tuning

This project presents a fully custom implementation of the GPT-2 architecture from scratch in PyTorch. All major architectural components—such as Multi-Head Attention, Transformer Blocks, GELU Activation, Layer Normalization, and Shortcut Connections—were engineered explicitly.

Beyond initial model development, the project extends GPT-2 with **Instruction Fine-Tuning** to align model outputs with user intentions, improving prompt-following and adaptability to domain-specific tasks. Model performance was evaluated using **Ollama**, focusing on instruction adherence and response quality with custom test prompts.

---

## 🚀 Features

### ✅ Custom GPT-2 Implementation
Designed and built all components from scratch:
- **Multi-Head Attention (MHA)**
- **Transformer Blocks**
- **GELU Activation**
- **Layer Normalization**
- **Shortcut (Residual) Connections**

### ✅ Instruction Fine-Tuning
- Fine-tuned the model using domain-specific instructions.
- Used pretrained GPT-2 weights as a foundation.
- Further trained the model to improve its ability to follow instructions and prompts tailored to specific tasks.

### ✅ Evaluation
- Utilized **Ollama** for rigorous benchmarking.
- Custom test prompts measured both:
  - Instruction-following behavior.
  - Output quality.

---

## 🧠 Use Cases
- Domain-adapted language generation
- Instruction-based chat models
- Research in LLM alignment

---

## 📦 Requirements
- Python 3.8+
- PyTorch
- Transformers
- Datasets
- Ollama

---

## 📊 Results
- Measured improvement in task-following ability
- Reduced hallucination on domain-specific queries
- Increased relevance of generated responses

---

## 🔍 Future Work
- Expand instruction tuning with Reinforcement Learning (e.g., PPO)
- Incorporate larger GPT variants
- Support multilingual and multimodal inputs

---

## 📜 License
MIT License
