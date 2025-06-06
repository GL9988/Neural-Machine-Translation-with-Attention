# Neural Machine Translation with Attention (PyTorch)

This project builds a custom English-to-French machine translation system using a GRU-based encoder-decoder architecture with attention. The solution was implemented end-to-end in PyTorch, with interactive support from ChatGPT and DeepSeek to debug, design, and refine the entire pipeline.

---

## 🔧 Tools & Libraries
- Python, PyTorch
- Matplotlib, Seaborn, BLEU (nltk)
- ChatGPT, DeepSeek (AI-assisted architecture clarification)

---

## 💡 Features
- Cleaned and normalized 18,000+ bilingual sentence pairs
- Encoder-Decoder model using GRUs with additive attention
- BLEU score evaluation and attention heatmap visualization
- Early stopping and loss tracking over training
- End-to-end translation and model saving pipeline

---

## 🚀 How to Run
```bash
# Clone the repository
https://github.com/yourusername/nmt-attention-pytorch

# Move into directory
cd nmt-attention-pytorch

# Install dependencies
pip install -r requirements.txt

# Run main training script
python main.py
```

---

## 📈 Sample Outputs
| Original Sentence               | Model Translation         | BLEU Score |
|--------------------------------|----------------------------|------------|
| tu es tres intelligent         | you're very intelligent    | 1.00       |
| elles sont sur le point de partir | they’re about to leave   | 1.00       |
| je suis en train de dormir     | i’m sleeping               | 0.00       |

---

## 🎯 Visualizations
### 🔥 Attention Heatmap
![Attention](visualizations/attention_sample.png)

### 📊 BLEU Score Plot
![BLEU Scores](visualizations/bleu_scores.png)

---

## 🧠 What This Project Shows
- My ability to build custom NLP architectures using PyTorch
- Effective use of AI agents like ChatGPT for project acceleration
- Visualization of model logic via attention weights
- Clear documentation and explainability across the project

---

## 👤 Author
**Guo Li**  
MS in Quantitative Management, Duke University (Fuqua School of Business)  
[LinkedIn →](https://www.linkedin.com/in/gl200)

---

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.
