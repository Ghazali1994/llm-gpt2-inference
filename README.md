# 🤖 GPT-2 Inference & Chatbot Playground

This project demonstrates basic usage of OpenAI's GPT-2 model via the Hugging Face Transformers library.  
You’ll find both terminal-based and web-based chatbot interfaces to interact with GPT-2.

## 📂 Project Structure

| File            | Description                                   |
|-----------------|-----------------------------------------------|
| `llm.py`        | Basic text generation using GPT-2             |
| `chatbot.py`    | Interactive terminal chatbot                  |
| `chatbot_ui.py` | Web UI chatbot using Gradio                   |
| `requirements.txt` | Required Python packages                  |

## 🚀 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/Ghazali1994/llm-gpt2-inference.git
cd llm-gpt2-inference
```

### 2. Set Up Virtual Environment
```bash
python -m venv venv
.\venv\Scripts\Activate.ps1       # PowerShell (Windows)
# OR
source venv/bin/activate          # macOS/Linux
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

## 💡 Example Usage

### ➤ Run basic inference:
```bash
python llm.py
```

### ➤ Run terminal chatbot:
```bash
python chatbot.py
```

### ➤ Launch web chatbot (Gradio UI):
```bash
python chatbot_ui.py
```

## 📌 Sample Output

```
Input: Hello, how are you?
Output: I'm doing well, thank you! How can I help you today?
```

> *Note: GPT-2 may sometimes produce repetitive or fictional responses — this is expected with base models.*

## 📦 Requirements

- Python 3.10+
- `transformers`
- `torch`
- `gradio`

> All handled via `requirements.txt`

## 🙋 Author

**Ghazali**  
Beginner AI Engineer — exploring LLMs, Prompt Engineering, and Fine-tuning  
📍 Chennai, India (Remote-friendly)  
🌐 [GitHub](https://github.com/Ghazali1994)

## ✅ What's Next?

This repo is part of a step-by-step learning journey into:
- Prompt Engineering
- Retrieval-Augmented Generation (RAG)
- Fine-tuning GPT models (LoRA/QLoRA)
- Building full-stack AI products

🧠 Follow along for more updates — and feel free to fork the repo, give it a ⭐ if it helped you, and build your own AI projects!
