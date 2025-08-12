# Fine-tune-BERT-for-Question-Answering


This project fine-tunes the **BERT** model for question answering using the **SQuAD** dataset. It supports both training and inference, and is compatible with Google Colab and local environments (e.g., VS Code).

---

## 🚀 Features

- Load and preprocess the SQuAD dataset  
- Tokenization with answer span alignment for training  
- Fine-tune BERT for question answering with HuggingFace `Trainer` API  
- Evaluate model performance during training  
- Save and load the fine-tuned model for inference  
- Perform question answering with a trained pipeline  

---

## 🔧 Technologies

| Tool / Library          | Purpose                          |
|------------------------|---------------------------------|
| [Transformers](https://huggingface.co/docs/transformers/) | BERT model and tokenizer        |
| [Datasets](https://huggingface.co/docs/datasets/)        | Load SQuAD dataset              |
| PyTorch                 | Deep learning framework          |
| HuggingFace Trainer API | Simplified training loop         |
| Python                  | Scripting and preprocessing      |

---
## 📁 Project Structure

- `main.py`                        # Script for training and evaluation  
- `Fine-tune-BERT-for-Question-Answering/`  # Project folder  
- `requirements.txt`               # Required Python packages  
- `README.md`                     # Project documentation  
