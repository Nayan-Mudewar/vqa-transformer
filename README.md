# vqa-transformer
# Visual Question Answering (VQA) with ViT + BERT

## 📜 Project Overview
This project demonstrates a **Visual Question Answering (VQA)** model built using **Vision Transformer (ViT)** for image feature extraction and **BERT** for natural language processing. The model takes an image and a question, then predicts an answer from the image using a custom classifier.

### 🚀 Key Components:
- **Visual Encoder**: `ViT` (Vision Transformer) from HuggingFace
- **Text Encoder**: `BERT-base-uncased`
- **Classifier**: Custom MLP (Multi-Layer Perceptron)
- **Loss Function**: Cross-Entropy Loss
- **Dataset**: VQA v2 small subset (`merve/vqav2-small`)

---

## 🔧 Requirements

The following libraries are required to run the project:

- **Python 3.x**
- **PyTorch**
- **Transformers (HuggingFace)**
- **Datasets**
- **Pillow (PIL)**

To install these libraries, use the `requirements.txt`:

```bash
pip install -r requirements.txt
