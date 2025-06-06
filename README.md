# 🌐 Neural Machine Translation with Attention  
Custom GRU-based sequence-to-sequence model with attention for English–French translation.  

---

## 🚀 Motivation  
Built to explore language modeling, attention mechanisms, and sequence learning from scratch—balancing technical rigor with team collaboration.

---

## 📦 Dataset  
Sourced from the Tatoeba Project via the "fra.txt" bilingual dataset (18K+ pairs).  
Filtered for clean, short, prefix-based sentence pairs to optimize alignment and fluency.

---

## 🧠 Model Architectures  
- **Encoder**: GRU with embedding and dropout  
- **Decoder**: GRU with additive attention and teacher forcing  
- **Tokenization**: Custom vocabulary class with START/END tokens  

---

## 🎯 Sample Output

Tested the trained model on held-out sentences. Results below show high fluency and semantic accuracy:

| 🇫🇷 French Input                  | 🇬🇧 Predicted Translation       | BLEU Score |
|----------------------------------|--------------------------------|------------|
| tu es très intelligent           | you're very intelligent        | 1.00       |
| je suis un tantinet jalouse     | i’m a little bit jealous       | 1.00       |
| elles sont sur le point de partir | they’re about to leave         | 1.00       |
| nous sommes enneigés            | we’re snowed in                | 1.00       |
| je ne suis plus inspirée        | i’m not inspired anymore       | 1.00       |

> ✅ **Average BLEU Score**: `0.96` across 50 test samples  
> ✅ **Crash-free Inference Rate**: `100%` after early stopping

---

## 🧪 Evaluation  
| Method              | BLEU Score | Notes                     |
|---------------------|------------|---------------------------|
| GRU + Attention     | ~0.96      | Consistent across pairs   |
| Visual Output       | ✅         | Alignment heatmaps shown  |

---

## 📊 Visualization  
<p align="center">
  <img src="visualizations/attention_heatmap_sample.png" width="480"/>
  <br><em>Attention heatmap: French input vs. English output</em>
</p>

---

## 🧰 Tech Stack  
- **Language**: Python  
- **Framework**: PyTorch  
- **Tools**: NumPy, Matplotlib, Seaborn  
- **Evaluation**: BLEU Score, Attention Maps

---

## 🤝 Collaboration  
Led problem scoping, built training loop, and handled model debugging.  
Worked closely with teammates to align logic, resolve tensor mismatches, and integrate modules.

---

## ▶️ Run This Project  
```bash
git clone https://github.com/yourusername/nmt-gru-attention.git
cd nmt-gru-attention
pip install -r requirements.txt
python train_model.py
