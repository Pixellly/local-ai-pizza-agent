# 🍕 Local AI Pizza Agent

A simple local AI agent built using **LangChain** and **Ollama** to answer questions about a pizza restaurant.

## Features
- Runs fully locally using Ollama
- Uses LangChain prompt chaining
- Easy to extend with tools, memory, or real data

## Tech Stack
- Python
- LangChain
- Ollama
- LLaMA 3

## Setup

### 1. Create virtual environment
```bash
python -m venv venv
```

### 2.Activate the environment
```bash
# Windows
venv\Scripts\activate
```


### 3.Install dependencies
```bash
pip install langchain langchain-ollama
```

### 4.Run Ollama
```bash
ollama serve
```

### 5.Run the project
```bash
python main.py
```

## Example Usage
```python
result = chain.invoke({
    "reviews": "Customers love the crust and fast service.",
    "question": "What is the best pizza place in town?"
})
print(result)
```

## 📌 Notes
- Requires Ollama installed locally
- Model used: llama3.2

## 📄 License
MIT

