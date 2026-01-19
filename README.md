
# AI-Powered Paraphrasing Tool 🤖✍️

This project is a **console-based AI-powered paraphrasing tool** built using **Python** and **Transformer models** from Hugging Face.  
It generates paraphrased text while preserving meaning, improving clarity, and ensuring grammatical correctness.

---

## 🚀 Features

- 🔄 Text paraphrasing using **T5 Transformer (t5-small)**
- ✍️ Grammar and fluency correction using a **Transformer-based grammar model**
- 📊 Evaluation using **BLEU** and **ROUGE** metrics
- 🖥️ Fully **console / notebook-based** (No GUI, No Web App)
- ⚡ No Java dependency

---

## 🧠 Models Used

| Task | Model |
|----|------|
| Paraphrasing | `t5-small` |
| Grammar Correction | `prithivida/grammar_error_correcter_v1` |

---

## 🛠️ Technologies

- Python 3.x  
- Hugging Face Transformers  
- PyTorch  
- NLTK  
- ROUGE Score  

---

## 📦 Installation

```bash
pip install transformers torch sentencepiece nltk rouge-score
```

---

## ▶️ How to Run

```bash
git clone https://github.com/your-username/ai-paraphrasing-tool.git
cd ai-paraphrasing-tool
jupyter notebook AI_Paraphrasing_Tool.ipynb
```

---

## 🧪 Sample Input

```
now a days Artificial industries  booming in all area of the life.
```

## ✅ Sample Output

```
Now a days Artificial industries are booming in all areas of the life.
```

---

## 📈 Evaluation Metrics

- **BLEU Score**
- **ROUGE-1**
- **ROUGE-L**

---

## 📁 Project Structure

```
├── AI_Paraphrasing_Tool.ipynb
├── README.md
└── Paraphrasing_Tool_Report.txt
```

